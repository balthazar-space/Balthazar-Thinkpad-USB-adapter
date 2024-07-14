# Balthazar Thinkpad USB adapter

![Adapter](pic/PCB.png)

# About

This project will make a USB keyboard/Trackpoint controller and enclosure for the non-chiclet Thinkpad keyboard (from the 10/20 generation, such as the T410, W520, etc.). 

[Keyboard3](https://github.com/balthazar-space/Balthazar-Keyboard-3) and the Thinkpad over this adapter connect over a USB cable to the Balthazar Unifying board.

https://github.com/balthazar-space/Unifying-PCB

That will give users more options for customizations, and also the possibility to reuse some old Thinkpad keyboards.

You can also use this adapter to connect the Thinkpad keyboard on your PC,  connect the keyboard to the adapter, and use USBC for connection with your PC.

# Controller

The current plan is to use an RP2040 microcontroller running QMK to handle the key matrix scanning and Trackpoint.

# Project origin

Differences from the original project

We have removed parts that the Balthazar Keyboard does not need.

We have removed the USB HUB on the board as we already have HUB on the unifying board. 

We only need one USB TYPE C connector, so we have removed the second one.

We have removed parts, and we made the PCB smaller.

Removing parts will lower production costs.

You can check the original project here: 

https://github.com/bluepylons/A-Thinkpad-USB-keyboard

Here you can find new [BOM](https://github.com/balthazar-space/Balthazar-Thinkpad-USB-adapter/tree/main/PCB/bom)

Adapter is stil not produced but we should have some prototypes soon!

## License

CERN Open Hardware Licence Version 2 - Weakly Reciprocal

## Funding

This project is funded through the [NGI Zero Entrust Fund](https://nlnet.nl/entrust), a fund
established by [NLnet](https://nlnet.nl) with financial support from the European Commission's
[Next Generation Internet](https://ngi.eu) program. Learn more on the [NLnet project page](https://nlnet.nl/project/Balthazar-Casing/).

[<img src="https://nlnet.nl/logo/banner.png" alt="NLNet foundation logo" width="300" />](https://nlnet.nl)
[<img src="https://nlnet.nl/image/logos/NGI0Entrust_tag.svg" alt="NGI0 Entrust Logo" width="300" />](https://nlnet.nl/entrust)