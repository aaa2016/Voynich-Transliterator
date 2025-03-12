# Voynich-Transliterator
 
## Purpose

This tool takes text from the Voynich manuscript (which has already been transcribed into Eva format) then converts it according to a mapping provided by the user in the configuration table.

This allows the user to quickly test the effects of letter substitutions on specific parts of the Voynich text.

Fundamentally, this tool implements a simple substitution cipher.

## How to use

1. Enter a substitution configuration for each letter in the Configuration table, eg. 'a' should convert to 'o'.
2. Paste your Voynich text (in Eva format) into the Input text box.
3. Click 'Transliterate'.
4. The output with the relevant substitutions will appear in the Output text box.

## Missing features and bugs

- Does not work with digraphs (eg. 'ii'='u', or 'sh'), so-called 'capitalised' Eva characters, or more complex/rare characters.
- Future version will include option to automatically use any text from the manuscript from a larger transliteration file.

## Screenshot

 ![Screenshot of tool](https://github.com/aaa2016/Voynich-Transliterator/blob/master/screenshot.png)
 
## Sources

Image source: VonHaarberg, CC BY-SA 4.0 via Wikimedia Commons (https://commons.wikimedia.org/wiki/File:Voynich_EVA.svg)

Source of example configuration: Bax, S. A proposed partial decoding of the Voynich script (2014) - https://stephenbax.net/wp-content/uploads/2014/01/Voynich-a-provisional-partial-decoding-BAX.pdf

Source of example text (f1v 1-10): http://www.voynich.nu/data/VT0e-n.txt (More info: http://www.voynich.nu/transcr.html#links)