Here is one valid solution, there are other ways to solve this than breaking out the layers and putting it back together.

Read in the gif image and break the layers into individual .bmp images

`
from PIL import Image, ImageMath
im = Image.open("/home/kali/Desktop/horse.gif")

# To iterate through the entire gif
try:
    while 1:
        im.seek(im.tell()+1) 
        # do something to im
        #  Never do this im.show()
        num=im.tell()
        im.save(("/home/kali/Desktop/horse/" + str(num) + ".bmp"))
        
except EOFError:
    pass # end of sequence
`

Run this code on the 734 layers to put it back together

`
with open('1.bmp', 'rb') as f:
    answer = f.read()
for layer in range(2, 734):
    with open(str(layer) + '.bmp', 'rb') as f:
        layer = f.read()
    next_answer = ''
    for x in range(len(answer)):
        next_answer += chr(ord(answer[x]) | ord(layer[x]))
    answer = next_answer
with open('answer.bmp', 'wb') as f:
    f.write(answer)
print(answer)
`