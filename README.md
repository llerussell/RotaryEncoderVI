# RotaryEncoderVI

LabView VI. Processes gray code input from a rotary encoder and outputs an analog voltage corresponding to rotation speed and direction. External devices can be triggered based on speed or distance.
Pre-built executable also included.

![Imgur](http://i.imgur.com/cnR4giW.png)

### Tested hardware
* Kubler 05.2400.1122.1024 encoder
* National Instruments 6343 card
* Windows 7 (64-bit)

##### Encoder pinout
Signal: | GND | +5V | A | B | Z
--- | --- | --- | --- | --- | ---
Colour: | white | brown | green | grey | blue
##### DAQ card pinout
Signal | Pin Number (Name) 
--- | ---
GND | 94
+5V | 96 
CTR0 A | 81 (PFI 8) 
CTR0 B | 85 (PFI 10) 
CTR0 Z | 83 (PFI 9) 

### Contributors
[Adam Packer](https://github.com/apacker83/PackIO)

