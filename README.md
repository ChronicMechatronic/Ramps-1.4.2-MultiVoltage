# Ramps-1.4.2-MultiVoltage

Special version of Ramps 1.4.2 allowing use of multiple power adapters to power a 3D printer.

Contains 5 seperate voltage rails for:
a 19.5V heated bed
a 12V hotend
one separate 12V stepper motor
two steppers running on 24V
one 5V stepper

The fifth stepper motor driver can be set to run off either the 5V, 12V, or 24V rail via 0 ohm links to be soldered on as necessary (add R30 for 5V; R29 for 12V; or R28 for 24V)
If you have a sufficiently powerful power supply the two 12V rails can be combined to run off a single barrel jack by populating R10 and R11 with 0 ohm links.

None of the voltage rails are constrained by anything other than the voltage rating of its capacitor, so repurpose as you please.


For pretty much everything else the standard documentation on https://reprap.org/wiki/RAMPS_1.4 applies
