# ZX Dandanator MTD

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

* If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
* You may not use the material for commercial purposes.
* You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

Original Design by Dandare, mad3001 and OverClk

ZX Dandanator MTD & MTD_TH PCB's are designs by MerlinKV

Special thanks to cacharreo, mad3001 & jjsaenz1969 from the Va de Retro Forum (see links bellow).

This project is a mix of the ZX Dandanator Mini! & the Multiply add-on.

# ATTENTION

This project was made for the retro community and not for commercial purposes. So only retro hardware forums and individual people can build this project.

THE SALE OF THIS PROJECT ON EBAY OR OTHER AUCTION SITES IS PROHIBITED

# Note

I take no responsibiltiy for any damage to any equipment that results from the use of this board.
USE AT YOUR OWN RISK!

# Updates

* 02-04-2024
   - v1.5 & v1.5s: Fixed some bugs. The two boards has been rerouted.
* 31-03-2024
   - mSD socket moved to the back side of the PCB.
   - Now you can solder two sockets (SD and mSD) but, remember, they cannot be used simultaneously. Use only an SD or mSD when using the interface.
* 29-03-2024
   - Fixed a mistake on U10 and SD/mSD 3.3v power supply
   - If you have the first boards of version 1.5 or 1.5s you must solder a wire between pin 1 and pin 8 of U10.
   - Now, everything is working fine. 
* 04-01-2024 - Added two new versions of the interface.
   - Version 1.5 is full lenght and have a rear ZX Spectrum Edge connector.
   - Version 1.5s is smaller with only one mSD socket and without rear ZX Spectrum Edge connector.
   - Most of the componentes are now SMD/SMT.
   - GAL replaced by 74HCT IC's series.
   - Added connector to allow the programming of the PIC (if needed).
   - Now you can programm the Arduino Nano directly (you don't need to disable the joystick).
   - Now you have only three switches: ROM SELECT, JOYSTIC ON-OFF & PAUSE.
   - Some users find the power LED light too bright. This has an easy solution by replacing R10 (680 Ohms) with one of a higher value, ie: 1K, 1K2, ...
* 31-12-2023 - Added a new preliminary scheme for replacing GAL with 74HCT IC series.
* 26-08-2023 - Added 3D Printer files (STL) for those who wants to put the arduino in a socket.

# Boards

* I have made two different boards, one with a PIC in True Hole format, and second with the PIC in SMD format (these ones are cheap).

# Functionalities of my boards

* Multiply upgradeable from ROMSet's creator. Just put the switch in programming mode, connect the device to a USB port on the PC. Launch ROMSet's creator and update.
* If you put the Multiply switch in programming mode, the Multyply is deactivated. It could also be considered as a Multiply ON-OFF. That is, in OFF the Multiply does not work, but the ROMSet's of the Dandanator do.
* Joystick ON-OFF
* Dual ROMSet. You can select one ROMSet or another, simply by changing a position switch. If you change the ROMSet switch position and it does not take the change, just press the right button of the ZX Dandanator MTD (or do a reset) and the other ROMSet is already selected.
* The two ROMSet's can be updated, either from the integrated Multiply, or from a DivIDE, DIVMMC, etc.
* "Pause" switch for games.
* Power LED.

In short, the ZX Dandanator MTD is a Dandanator 2.1b with Double ROMSet, Multiply integrated and some updates.

A few thoughts about my "Pause" switch:

* The Dandanator already includes a programmed pause. If during a game, the left button is pressed briefly, the game is stopped and will be resumed by pressing any key.
* When loading TAP or Z80 games from the Multiply, the "scheduled pause" leaves some screen corruption in the lower right corner. That screen corruption does not occur if we use the slide switch.
* The pause switch is designed for + 2A, + 2B and +3, although it will probably also work on 128K; but in the 48K it will not work as it should.
* The two pause methods do not interfere.

# Links

https://www.va-de-retro.com/foros/viewtopic.php?p=189412#p189412

https://www.winuaespanol.com/phpbb3/viewtopic.php?f=32&t=1168

http://www.dandare.es

https://github.com/mad3001/Multiply

# Images

![Version 1.5 Front](https://github.com/merlinkv/ZX_Dandanator_MTD/blob/main/ZX_Dandanator_MTD_1_5_Front.jpg)

![Version 1.5 Front](https://github.com/merlinkv/ZX_Dandanator_MTD/blob/main/ZX_Dandanator_MTD_1_5_Back.jpg)

![Version 1.5 Front](https://github.com/merlinkv/ZX_Dandanator_MTD/blob/main/ZX_Dandanator_MTD_1_5s_Front.jpg)

![Version 1.5 Front](https://github.com/merlinkv/ZX_Dandanator_MTD/blob/main/ZX_Dandanator_MTD_1_5s_Back.jpg)


