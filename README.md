# MegaCD-Connect-BD-Remake
 This is the Schematics, PCB and Logic for the Mega-CD Connect BD.

It is to replace the 837-8327-01 IC BD MEGA-CD CONNECT BD with a failed ASIC to the older Logic version of the board that has the Peel IC.

** UNTESTED **

( PCB's have been ordered, will update with results )

The Gerbers have been created using the recommendations from JLCPCB.

This board uses a GAL22V10 to achieve the same logic functions as the Peel IC. Jed file is provided.


## Compiling the Logic

The software i used to make the Jed file was GALasm. It can be downloaded from here https://github.com/daveho/GALasm

Only source files is provide, so you will need to compile GALasm first. I used MacOS to do this, Linux should work and maybe Windows ???

Once GALasm is compiled, use the following command to compile the Logic into a Jed file from within the GAL22V10 folder.

```
galasm ./GAL22V10.pld
```

## Thanks to

With thanks to @fabiodl for decoding the logic of the Peel IC
https://github.com/fabiodl/peelDecoder


## !!!!! WARNING !!!!!

Use at your own risk. I accept no responsibility if this damages any of your equipment.
