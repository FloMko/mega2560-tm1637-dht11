# TM1637 dh11 arduino Meda2560

Description
-----------
Displaying data from sensor DH11 to 7-segment display modules based on the TM1637 chip, base on arduino mega 2560. Source .zip library included. This is copy of http://www.instructables.com/id/Arduino-TM1637-7-Segment-Display-DHT11-Temp-Sensor/

Connection
-----------

Connecting dh11 to Arduino:

```
Arduino              dh11
PIN #52 ------------------ CLK
5V   ------------------ VCC
GND    ------------------ GND
```

Connecting TM1637 to Arduino:

```
Arduino              TM1637 display
PIN #50 ------------------ CLK
PIN #48 ------------------ DIO
5V   ------------------ VCC
GND    ------------------ GND
```