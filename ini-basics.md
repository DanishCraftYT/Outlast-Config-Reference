# ini Basics

Unreal Engine 3 (the Game Engine Outlast and Outlast 2 are made in) uses .ini files to store configurations for different things in the game.
it could be anything from player movement speed and enemy behavior to keybinds and GUI configurations.<br>

## Outlast and Outlast 2 Config Files

Outlast and it's sequel uses many config files althrough only a few are actually important to us. these being:
* DefaultGame.ini
* DefaultInput.ini
* DefaultEnemy.ini
* DefaultUI.ini

## Sections

".ini" files are split into sections. a section is defined by putting text between a pair of sqaure brackets. here's an example of a section: `[SectionName]`.<br>

## Varibles

each section in a ".ini" file contains varibles. varibles look like this: `'VaribleName'='Value'`.<br>
'VaribleName' is the name of the varible.<br>
'Value' is the value of the varible.<br>

here's a example of a varible from "DefaultGame.ini" from Outlast: `StruggleNoFail=False`.<br>
`StruggleNoFail` is the name of the varible.<br>
`False` is the value of the varible.<br>

Varibles are sometimes also referred to as "Key Value Pairs" where the "VaribleName" is the Key and the "Value" is the Value. together they form a "Key Value Pair".<br>

## Comments

use a semicolon to make comments in ".ini" files. example of a comment would be:
```
; COMMENT: determines how fast the player walks.
NormalWalkSpeed=200
```
