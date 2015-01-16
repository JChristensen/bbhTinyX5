# ATtinyX5 Breadboard Helper #
http://github.com/JChristensen/bbhTinyX5  
ReadMe file  
Jack Christensen Jan 2015  

![](https://raw.githubusercontent.com/JChristensen/bbhTinyX5/master/bbh1.jpg)

## Introduction ##

ATtiny Breadboard Helpers are the easiest way to breadboard Atmel ATtiny24/44/84 and ATtiny25/45/85 micrcontrollers! These small boards contain everything needed to run an ATtiny microcontroller, including:
- ICSP header
- Filter and bypass capacitors
- Reset button with pullup resistor
- LED with current-limiting resistor

The Breadboard Helper breaks out all the MCU's pins to a header and also connects to the breadboard's power rails. Plug the Breadboard Helper into a breadboard, add power, connect a programmer, and the microcontroller is ready to go!

PC boards can be ordered [from OSH Park](https://oshpark.com/shared_projects/kbM0Jfiz).  
A Bill of Materials with Mouser part numbers is part of this repo.  
See the ATtinyX4 Breadboard Helper [here](https://github.com/JChristensen/bbhTinyX4).

## Power Connection (see photos below)##

A two-pin header connects the Breadboard Helper to the breadboard's power rails. This header should be soldered ***either*** into the position labeled **"a"** ***or*** into the position labeled **"b"**.

Use position **"a"** for breadboards where the power rail holes line up with those in the main part of the breadboard (most full-size breadboards). Use position **"b"** for breadboards where the power rail holes are staggered between those in the main part of the breadboard (most half-size breadboards).

Observe polarity carefully and ***do not*** solder headers into both positions **"a"** and **"b"**, as the result will likely not fit into any breadboard!

## Arduino Pin Mapping ##

The 6-pin header is labeled with Arduino pin numbers 0-4 plus RESET, using the pin mapping from the [Arduino-Tiny core](https://code.google.com/p/arduino-tiny/). Other cores may be used with the Breadboard Helper but be aware that the pin mapping may be different. The AVR port and pin numbers are also labeled for easy reference.

The LED is connected to Arduino pin 2 or PB2 (SCK/USCK/SCL/ADC1/T0/INT0/PCINT2).

## Make the right power connection ##

Some breadboards have holes in the power rails that line up with those in the main part of the breadboard -- this is **Type "a"**.  

Some breadboards have holes in the power rails that are staggered between those in the main part of the breadboard -- this is **Type "b"**.  

![](https://raw.githubusercontent.com/JChristensen/bbhTinyX4/master/bbh2.jpg)

![](https://raw.githubusercontent.com/JChristensen/bbhTinyX4/master/bbh3.jpg)

Solder the two-pin power rail header into position **"a"** *or* position **"b"**, *NOT BOTH!*

![](https://raw.githubusercontent.com/JChristensen/bbhTinyX4/master/bbh4.jpg)

Add power (observe polarity!), connect a programmer and the ATtiny is ready to go!

![](https://raw.githubusercontent.com/JChristensen/bbhTinyX4/master/bbh5.jpg)

## CC BY-SA ##
"ATtinyX5 Breadboard Helper" by Jack Christensen is licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).
