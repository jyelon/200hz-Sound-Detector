Frequency detector:

Use an ADXL345 accelerometer to detect sound waves propagating
through a solid medium.  The program currently detects a fixed
200hz frequency, but it's possible to change the target frequency
by reconfiguring the accelerometer's sample rate and the
divisor of the StreamingGoertzel object.



