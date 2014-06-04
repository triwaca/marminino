Marminino, o Arduino Cearense!
by Daniel Almeida Chagas

The marminino project is an arduino minimal, mounted in an very simple PCB, focused to be very simple to build, cheep, and easy to use. The marminino is an open hardware fork from the Nanino project, initially made by Johan von Konon, and updated by Brad Luyster.The project goals are:

- Single side PCB, who can be made for beginners and still with great results (big traces, with big spaces between).
- Minimal components, just the essencial. 
- Some capacitors for a better battery powered experience.
- Jumper for selectiong the power source (FTDI or Batteries).
- Mounting holes attach a 4 AA battery support. 
- Better led position.
- New component organisation.
- New switch position
- Two new female bar pins for easy prototyping with or without mini breadboard.
- Complete information about pins on silk screen.

The board was created using DipTrace software, who is freeely available for small projects.

The list of components:
1x single sided PCB board (etch, mill or order)
1x ATmega328P (28 pin DIL)
1x IC socket 28 pin DIL (optional)
2x 6×1 0.1” female pin header
2x 8×1 0.1” female pin header
2x 5×1 0.1” female pin header (optional)
1x 6×1 0.1” pin header (FTDI connector)
1x 3×1 0.1” pin header (Power jumper)
1x jumper
1x 10k resistor (reset pull up – 1/4W)
2x 1k resistor (power and pin 13 LED – 1/4W)
1x yellow 3mm LED (pin 13)
1x green 3mm LED (power)
1x 16 MHz crystal (0.2” pitch)
2x 22pF decoupling caps
1x 6mm miniature switch (reset)
3x 0.1uF decoupling cap 0.1/0.2”
1x 1uF cap 0.1/0.2” (optional if not using batteries)
1x AA battery support (optional if not using batteries) 

This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License.