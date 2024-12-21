# NAND-gate

Two transistors are set up so that the emitter of one (transistor A) is in the same row with the collector of the another (transistor B).
A's collector is connected to GND (blue rail) with a jumper wire.
The bases of both transistors are connected to power supply (red rail) with resistors.
The anode of the LED is connected to the emitter of the transistor B, and also to red rail with a resistor.
The cathode is connected to the GND.

When both transistors are on, the current from the third resistor, which connects the emitter of B and the anode of the LED to the power supply, goes through both transistors to GND. So, the current doesn't go to the LED.
If we take one or both resistors connected to the bases of the transistors, the current cannot go though them. So it should go to the LED which then lights up.
