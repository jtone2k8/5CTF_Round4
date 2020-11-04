```
#!/bin/bash

lines=$(grep "192.168.1.205" ./access.log | awk -F " " '{print $7}' | uniq | cut -c 2-)

output=""

for line in $lines

do

	output=$output$line

done

#echo $output > ./output.dat

echo $output | base64 --decode > jurassic_awk.jpg

echo "What's the sha1 of the file?"

cat access.log | awk '{print $0}' | sha1sum

echo -n "What's the sha1 of the file if you remove all HEAD requests?	
	"
cat access.log | awk '{if ($6 ~ /"HEAD/ ){next} else {print $0}}' | sha1sum

echo -n "What's the sha1 of the file if you uppercase all GET requests?
		"
cat access.log | awk '{if ($6 ~ /"GET/  ){print toupper($0)} else {print $0}}' | sha1sum

echo -n "What's the sha1 of the file if you lowercase all POST requests?
	"
cat access.log | awk '{if ($6 ~ /"POST/ ){ print tolower($0)} else {print $0}}' | sha1sum

echo -n "What's the sha1 of the file if you reverse all TRACE requests?
		"
cat access.log | awk '{if ($6 ~ /"TRACE/){for (i = length($0); i > 0; i--){printf substr($0,i,1)}; print ""}else {print $0}}' | sha1sum

echo -n "What's the sha1 of the file if you remove all HEAD requests, uppercase GET requests, lowercase POSTS requests, and reverse all TRACE requests?	
	"
cat access.log | awk '{if ($6 ~ /"HEAD/ ){next} if ($6 ~ /"TRACE/){for (i = length($0); i > 0; i--){printf substr($0,i,1)}; print ""; next} if ($6 ~ /"GET/  ){print toupper($0); next} if ($6 ~ /"POST/ ){ print tolower($0); next} else {print $0}}' | sha1sum


```