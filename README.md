Intelligent Matrix Display library
===================================

Intelligent Matrix Display library for Arduino and Teensy 3. This library use a GPIO chip from Microchip, MCP23s17 or MCP23S17
for drive 1 to 4 modules (normally each module it's 4 chars), if more modules needed another chip is needed for addressing
(see library comments).
Intelligent Matrix Display are led matrix alphanumeric display with logic incorporated used during the 80/90's, they
was expensive but actually there's a lot of NOS in internet so they are affordable. They need several lines for driving
so I wroted an universal library that need only 2 o 3 wires.
Library can use MCP23xxx chip or 2 shift register (595) chip but this was never tested yet, only implemented.
Library it's for my purposes and still in development so bugs exists.
Since every display differ a little from each other I have to write a wiki to explain how to connect and choose
the best way to address modules.

Supported Display:

  DLR3416
	DLO3416
  DLG3416
		  
	DLR2416
	DLO2416 
	DLG2416
		  
	HDLA2416
	HDLS2416
	HDLO2416
	HDLG2416
	HPDL1414
	DL3416
	DL2416
