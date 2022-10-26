# SMD LED Sample Boards
 A selection of PCB files to let you create sample reference cards for surface mount LEDs

After recently purchasing a quantity of SMD LEDs in various sizes and colours, I wanted a board that to which I could apply power via a USB cable and see them all lit up. This lets me quickly and easily pick which LEDs I want to use in future projects and also lets me have a handy reference board of resistor values for different LEDs (when fed 5v) in order to give a level of brightness that would be suitable for things like indicator LEDs.

In order to determine the resistor values, I used my variable benchtop power supply (the Eventek KPS1505D) as demonstrated in the video below. This is a handy way to determine the forward voltage and resistors you'll need when you don't have a datasheet handy - and sometimes even if you do.

[![Watch how it all comes together on YouTube](http://www.johnaldred.com/wp-content/uploads/2022/09/led-sample-board-play-button.jpg)](https://youtu.be/bLPhpMwc5_M)

The Gerber files contained in this repository are all zipped up and ready to go for you to order from companies like JLCPCB, PCBWay, etc. with no changes required. All of the board and drill files are included and the only thing you might want to change when you upload the zip file to a PCB service is the colour of the silk screen. Personally, I prefer black. It prevents the colours from muddying each other.

Several iterations of the board will eventually be uploaded and each will have two versions. There's the standard version (e.g. "1.1") and then there's a "b" version (e.g. "1.1b"). The standard version of the board uses a Type-C USB socket that features two surface mount pads for mechanically fixing the socket to the board. The "b" version uses a Type-C USB socket that has four throughhole pins for the same purpose. This is mostly because I had a couple of hundred of the SMD type lying around in a box before I realised that the throughole ("b" board) variant is more common.

![USB-C Footpring comparison](https://github.com/Kaouthia/LED-Sample-Board/blob/main/Documentation/1-1-vs-1-1b.jpg?raw=true)

If you need this board with a different USB-C footprint, let me know and I'll see what I can do!

![Board layout](https://github.com/Kaouthia/LED-Sample-Board/blob/main/Documentation/led-sample-board-board-layout.jpg?raw=true)

*This documentation will be updated and added to as I get chance*
