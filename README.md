# k3ng_cw_keyer on PIC32-PINGUINO
This is my clone of wonderfull cw keyer project from K3NG

I designed a schematic and circuit board on my own needs (1 PTT out, 4 memory buttons, 16x2 LCD) and to use an Olimex PIC32-PINGUINO just because I had one left from a previous project ;-)
Hardware documentation can be found here https://github.com/iz3gme/k3ng_cw_keyer/wiki

The code in my final configuration use about 50% of available program memory so there's plenty of space for future improvements and to enable more features

Refer to Olimex documentation to program the board with Arduino IDE (see specific section at https://www.olimex.com/Products/Duino/PIC32/PIC32-PINGUINO/open-source-hardware)

BTW PIC32-PINGUINO is told to be pin to pin compatible with Arduino but use of my design with different board is on your own risk.

Original intro text from k3ng follows

73 de IZ3GME Marco

# K3NG Arduino CW Keyer

The K3NG Keyer is an open source Arduino based CW (Morse Code) keyer with a lot of features and flexibility, rivaling commercial keyers which often cost significantly more. The code can be used with a full blown Arduino board or an AVR microcontroller chip can be programmed and used directly in a circuit. This keyer is suitable as a standalone keyer or for use permanently installed inside a rig, especially homebrew QRP rigs. It’s open source code so you can fully customize it to fit your needs and also perhaps learn from it or find coding ideas for other projects.

Documentation is located here:
https://github.com/k3ng/k3ng_cw_keyer/wiki
