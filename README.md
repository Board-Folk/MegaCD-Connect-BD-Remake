# MegaCD-Connect-BD-Remake
 This is the Schematics, PCB and Logic for the Mega-CD Connect BD Targeting the 315-5547 (MCE V1) MegaCD.

It is to replace the 837-8327-01 IC BD MEGA-CD CONNECT BD with a failed ASIC to the older Logic version of the board that has the Peel IC.

The board is not a clone, rather a remake as i do not have access to an original logic board version to do an exact replica of traces.

** UNTESTED **

( PCB's have been ordered, will update with results )

* The Gerbers have been created using the recommendations from JLCPCB.

* This board uses a GAL22V10 to achieve the same logic functions as the Peel IC. Jed file is provided. 
  Use a MiniPro to write the Jed file to the GAL Chip.

<br>

### Compiling the Logic

The software i used to make the Jed file was GALasm. It can be downloaded from here https://github.com/daveho/GALasm

Only source files is provide, so you will need to compile GALasm first. I used MacOS to do this, Linux should work and maybe Windows ???

Once GALasm is compiled, use the following command to compile the Logic into a Jed file from within the GAL22V10 folder.

```
galasm ./GAL22V10.pld
```

<br>

### Thanks to

@fabiodl for decoding the logic of the Peel IC

https://github.com/fabiodl/peelDecoder

#### Other Resources

* https://circuit-board.de/forum/index.php/Thread/25582-SEGA-MEGA-CD-1-Reparatur-PEEL-18CV8-PLD-auslesen/

* https://www.eevblog.com/forum/projects/help-with-reverse-engineering-unexpected-behavior-of-peel18cv8-223204/


### !!!!! WARNING !!!!!

Use at your own risk. I accept no responsibility if this damages any of your equipment.
