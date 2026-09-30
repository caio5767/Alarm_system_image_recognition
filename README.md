
Python and Micropython code from an ongoing project. It's an alarm system, webcam and ESP-32 based - with a simple sensor and a passive buzzer. Uses Ultralytics image recognition for detection of cats, sending a request (by socket server) to an embedded system - that's the alarm.
Can be repurposed for other goals.  

The requirements are obviously:
1. The ESP has to be able to connect to wifi.
2. Micropython firmware has to be installed in the ESP.

This works in a local IP, be sure to include it. Other bits as the alarm song, and the object to be detected can be changed.

   
