# K64F-Datalogger
A Datalogger implementation using FRDM-K64F board. This device acquires data at 200Hz from 6 analog channels, 2 digital channels (frequency), 1 internal accelerometer (and a magnetometer, not used) and 1 external accelerometer and gyroscope.

### Notes:
- The digital inputs were tested to and work with high precision to frequencys under 2000Hz. Up to 20000Hz, has around 7% of error rate.
