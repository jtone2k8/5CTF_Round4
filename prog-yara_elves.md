Level 1 Questions

Santa had a backlog of toys that needed to be made, so he had to put his crew of elves to work. He assigned each elf randomly three items to make and handed them a piece of paper, but he forgot to write down the totals for toys that he assigned them. You have been tasked with creating an inventory.

1 - 

Can you tell Santa how many Dominoes that were made?

Flag - 3

2 - 

Santa needs a total count of Sound toys that were made. How many Sound toys got made?

flag - 20

3 - 

One of Santa's favorite toys is a toy train, how many Toy Trains were made?

flag - 2

>>>

```
rule Dominoes

{

    strings:

	$dominoes = "Dominoes" nocase wide

    condition:

        any of them

}
```
/*

.\yara64.exe -r .\level1.yar .\elves_level1 | Select-String Dominoes | measure

Flag - 3

*/
```

rule Sound

{

    strings:

	$sound = "sound" nocase wide

    condition:

        $sound

}
```

/*

.\yara64.exe -r .\level1.yar .\elves_level1 | Select-String sound | measure

Flag - 20

*/

```
rule Train
{
    strings:
	$train = "toy train" nocase wide

    condition:
        any of them
}
```

/*

.\yara64.exe -r .\level1.yar .\elves_level1 | Select-String Train | measure

Flag - 2

*/
>>>


Level 2 Questions

Santa outsourced this list making ability to head elf, Peppermint Candy, But her ability to spell seems off. Can you help Santa Make use of her notes to the elves?

1 - 

Santa was hoping for lots of small toy to cut out of control costs, how many Shopkins were made?

Flag - 1

2 - 

Santa wants kids these days to be creative, how many Creative toys got made?

flag - 13

3 - 

One of Santa's favorite toys to keep his calm is a Fidget Spinner, how many Fidget Spinner were made?

flag - 3

>>>

```
rule shopkins

{

    strings:

	$shopkin = /sh\(*\)*\(*\)*\(*\)*o\(*\)*\(*\)*\(*\)*pk1*i1*ns/ nocase wide

    condition:

        any of them

}
```

/*

.\yara64.exe -r .\level2.yar .\elves_level2 | Select-String shopkins | measure

flag: 0

*/
```
rule creative

{

    strings:

	$creative = /cr!*e!*@*a@*t1*i1*v!*e!*/ nocase wide

    condition:

        any of them

}
```

/*

.\yara64.exe -r .\level2.yar .\elves_level2 | Select-String creative | measure

flag: 13

*/

```
rule fidget

{

    strings:

	$fidget = /f1*i1*dg!*e!*t sp1*i1*nn!*e!*r/ nocase wide

    condition:

        any of them

}
```

/*

.\yara64.exe -r .\level2.yar .\elves_level2 | Select-String fidget | measure

flag: 3

*/

>>>

Level 3 Questions

Santa found an online resource to create the list this time, but he went with the cheapest quote, and he got some crazy wording back. Santa handed these notes out to the elves, in hopes that they can read what they were asked to make.

1 - 

Can you tell Santa how generous he is this year with the number of Xbox consoles that were made?

Flag - 3 

2 - 

Santa needs a total count of Educational toys that were made so he can write off for taxes next year. How many Educational toys got made?

flag - 13

3 - 

Santa wants to jump for joy when this is all over, and he needs a pair of Moon Shoes. how many Moon Shoes were made?

flag - 8

>>>
```
rule xbox

{

    strings:

	$xbox = "><|3()><" wide

    condition:

        any of them

}

rule xboxhex

{

    strings:

	$c = {3e ?? 3c ?? 7c ?? 33}

	$b = {3e 3c 7c 33 28 29 3e 3c}

    condition:

        any of them

}
```

/*

.\yara64.exe -r .\level3.yar .\elves_level3 | Select-String xbox| measure

flag: 3

*/

```
rule educational

{

    strings:

	$educational = {5b ?? 2d ?? 5b ?? 29 ?? 7c ?? 5f ?? 7c ?? 5b ?? 2f ?? 2d ?? 5c ?? 37 ?? 5d ?? 5b ?? 28 ?? 29 ?? 7c ?? 5c ?? 7c ?? 2f ?? 2d ?? 5c ?? 7c ?? 5f ?? 20 ?? 37 ?? 28 ?? 29 ?? 2f ?? 35}

    condition:

        any of them

}
```

/*

.\yara64.exe -r .\level3.yar .\elves_level3 | Select-String educational | measure

flag: 10

*/

```
rule moonshoes

{

    strings:

	$moon_hex = {7c ?? 76 ?? 7c ?? 28 ?? 29 ?? 28 ?? 29 ?? 7c ?? 5c ?? 7c}

    condition:

        any of them

}
```

/*

.\yara64.exe -r .\level3.yar .\elves_level3 | Select-String moonshoes | measure

flag: 8

*/
>>>

Level 4 Questions 

Santa found sdrowkcab the elf to transcribe his order this time, but apparently he hired the one elf that can not seem to do anything right.
​
1-

How many Batman Action Figures did he have sdrowkcab write down?

flag: 2

2-

Which elves were assigned? first names only with a common and no space separating.

flag: 

tangy,lucky or lucky,tangy

3-

How many Rainbowcorn dolls were added to the list??

flag: 

7

4:

How many elves had to make toys in the sound category?

flag:

57

rule batman
{
	strings:
		$bat1 = /-\|-ab|tab/ wide ascii nocase
		$bat2 = /nann|nam/ wide ascii nocase
		$bat3 = /-\|-ca|tca/ wide ascii nocase
/*
		$bat5 = "nam-|-ab" fullword wide ascii nocase
		$bat6 = "nannttab" fullword wide ascii nocase
		$bat7 = "namtaB" fullword wide ascii nocase
*/
	condition:
		all of them
}
rule rainbowcorn
{
	strings:
		$rainbow1 = "nrocwobniaR" fullword wide ascii nocase
		$rainbow2 = "nrocmobniaR" fullword wide ascii nocase
		$rainbow3 = "nrocmwmobniaR" fullword wide ascii nocase
	condition:
		any of them
}
rule sound
{
	strings:
		$music1 = /\)nuos*|bnuos*|dnuos*/ nocase wide ascii
	condition:
		any of them
}