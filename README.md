# PU2CLR TEF668X Arduino Library

The TEF6686 and TEF6688, are single-chip radio ICs including an AM/FM radio tuner and software-defined radio signal processing from NXP Semiconductors. This project is about an Arduino Library to control the TEF668X family devices. 

This library is under construction...

![Under construction](extras/images/under_construction.png)


This library can be freely distributed using the MIT Free Software model. 

[Copyright (c) 2019 Ricardo Lima Caratti](https://pu2clr.github.io/RDA5807/#mit-license). 

Contact: __pu2clr@gmail.com__.


## Contents

1. [Preface](https://pu2clr.github.io/TEF668X#preface)
2. [Library Installation]()
3. [API Documentation]()
4. [Schematic]()
5. [Sketch examples]()



## Preface 

The TEF6686 and TEF6688 are digital receivers with tuner and software-defined radio processing (SDR). This family of IC can be controlled via high-level commands using I2C protocol. This feature makes the TEF668X a great device to be controlled by Arduino compatible boards.  

The TEF668X Arduino Library covers all functionalities of the TEF668X.

## Main features

1. FM receiver with a tuning range of 65 MHz to 108 MHz;
2. AM receiver 2.300 KHz to 2.7000 KHz;
3. FM LNA with AGC
4. FM Channel Equalization;
5. Soft Mute on Modulation;
6. Stereo High Blend;
7. FM mixer for frequency conversion to a low IF complex signal (AM SW);
8. AM LNA with AGC, matching active and passive antenna applications;
9. AM mixer for frequency conversion to a low IF complex signal;
10. Digital IF signal processing including decimation, shift to baseband, AGC control, I/Q correction, variable IF bandwidth filtering (PACS) and demodulation;
11. FM stereo decoding;
12. TEF6688 baseband I2S output supporting HD Radio and DRM1 with external digital radio coprocessor (SAF356X or SAF360X);
13. Blending function for HD Radio reception (TEF6688);
14. AM and FM noise blanking, Signal quality detection and weak signal processing;
15. Advanced RDS and RBDS demodulation and decoding;
16. One I2S input and one I2S output;
17. Single 3.3 V supply voltage;
18. Fast mode I2C-bus (400 kHz)
19. Configurable GPIO pins for RDS, Quality Status Interrupt and generic I2C-bus
controlled I/O;





