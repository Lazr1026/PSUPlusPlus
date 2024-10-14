# wiiu-psu
The wiiu-psu (or PSU++) is a regulator board for the Wii U, minus the core rails (1v/1.15v).
It is based off the PSU-Plus, so all rails have a limit of 3A (this only really matters for 5v).

### Features
- All low-current regulators required for the Wii U to function.
- Bonus 3v3 rail (STBY) for the RTC to power on the system.
- 1.25v regulator for WUP-01 motherboards (or if you wanted to remove the stock one).
    - 1.25v can be enabled/disabled with a simple jumper.

![](https://raw.githubusercontent.com/Lazr1026/PSUPlusPlus/blob/main/img/psu.png)

The intent is to be used for the Wii U Mini, but if you find another use for this board, have at it!
There are two VIN pads. The smaller one is used to power the STBY regulator, while the bigger one is to power all of the other regulators.

### Credits
[CrazyGadget](https://github.com/CrazyGadgetMods) / [YveltalGriffin](https://github.com/mackieks): The original PSU-Plus regulator board.
[BitBuilt](https://bitbuilt.net/): Being pretty fucking cool.
