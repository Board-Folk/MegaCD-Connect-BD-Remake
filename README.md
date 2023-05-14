# MegaCD-Connect-BD-Remake
 This is the Schematics, PCB and Logic for the Mega-CD Connect BD.

** UNTESTED **

It is to replace the 837-8327-01 IC BD MEGA-CD CONNECT BD with a failed ASIC to the older Logic version of the board that has the Peel IC.

This board uses a GAL22V10 to achieve the same logic functions as the Peel IC. Jed file is provided, but if you want to compile your own....

To compile the Logic i used GALasm from https://github.com/daveho/GALasm This will need compiling from source.

Once GALasm is compiled use the following command to compile the Logic into a Jed file from within the GAL22V10 folder.

galasm ./GAL22V10.pld


With thanks to @fabiodl for decoding the logic of the Peel IC
https://github.com/fabiodl/peelDecoder
