Frequency detector:

Use an ADXL345 accelerometer to detect sound waves propagating
through a solid medium.  The program currently detects a fixed
200hz frequency, but it's possible to change the target frequency
by reconfiguring the accelerometer's sample rate and the
divisor of the StreamingGoertzel object.

This program is part of a bigger project - a strange gadge to
detect when a CNC router's bit is touching the workpiece.  The gadget
works like this: you attach a 200hz vibration generator to the
bed of the router.  You attach a 200hz frequency detector to the
spindle.  When the vibration travels from the bed, up the bit, and
into the spindle, you know the bit is touching the workpiece.
The 200hz waveform generator and the 200hz frequency detector are
separate github projects, but they're meant to go hand in hand.

