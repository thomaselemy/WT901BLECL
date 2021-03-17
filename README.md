# WT901BLECL

This is an app allowing you to record sensor data from the WT901BLECL 9-DOF Sensor (accelerometer, gyroscope, magnetometer). The sensor is manufactured by WitMotion and I used their code as a starting but but am in no way affiliated with them.

In particular, I made sure the app can record in the background for an extended period of time using a foreground service. With a sampling rate of 0.1Hz, the battery should last for way beyond 10 hours of recording.

Tested under Google Pixel 2 with Android 10.

Using vrublack's code as a starting point, want to us the accelerometer data to trigger android notifications for movement detected primarily on x and y axis. Need to lookup how to create notifications for android and then it should just be reading data from there.
