# Bible Verse ¹⁶ Formatter
A simple script for the macOS Services menu that convert selected bible verse numbers into unicode superscript characters.

## How it works
The script is a Automator Service menu item that uses a bit of JXA to transform any numbers into unicode superscript caractors.

So paste in your bible verse:
```
16 For God so loved the world that he gave his one and only Son, that whoever believes in him shall not perish but have eternal life. 17 For God did not send his Son into the world to condemn the world, but to save the world through him. 18 Whoever believes in him is not condemned...
```

Then select all, right-click and go to `Services` → `Format Bible Verse`
```
¹⁶ For God so loved the world that he gave his one and only Son, that whoever believes in him shall not perish but have eternal life. ¹⁷ For God did not send his Son into the world to condemn the world, but to save the world through him. ¹⁸ Whoever believes in him is not condemned...
```

## Installation
Download and double click the 

## Usage:  
![Demo](https://uploads-ssl.webflow.com/60e9efc80070ba3c631a2ac6/60eef1f780d2a86ae83a9e43_bible-verse-formatter.gif)

## Limitations and disclamer
*The script is not perfect and do not work with all scriptures. Fx. if there is mention at number in the bible vers the script will convert those numbers too. The unicode caractors also do not display correct in all fonts, so not all fonts do have these caractors, many have 1, 2 and 3 but not the rest fx.*
