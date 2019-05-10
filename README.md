# Cable Test V0.02

You want a PCB to exercise or learn to solder THT components, here you have one of many.
This provides you with a device to test network cables (RJ45) and telephone cables (RJ12 / 11),
made with normal components, (the most complicated being the LED bar).
You can be complemented with more diodes 1N4148 in anti-parallel soldiers under the LEDS (2, 5..9) to allow to check all cable faults.

Buy PCB in [PCBWAY]


![Top view][PHT]
![Render][RENDER]

#B.O.M.
Qty	Value	 Device	        Package	        Parts	Description

2		 DS1128-S80BP	DS1128-S80BP	J1, J3	Ethernet Connector
1		 BATTERY9V	BATTCON_9V	BAT1	Battery Holders
1	100nF	 C2.5/2	        C2.5-2	        C2	CAPACITOR
2	10K	 1/4 Watt	0204/7	        R1, R3	RESISTOR
1	10uF/16V 2.5mm � 6mm	E2,5-6	        C1	POLARIZED CAPACITOR
1	1K	 R-EU_0204/7	0204/7	        R4	RESISTOR
6	1N4148	 DIODE-D-2.5	D-2.5	        D1...D6	DIODE
1	4017N	 4017N	        DIL16	        IC2	COUNTER/DIVIDER
1	47K	 TRIM_EU-CA6V	CA6V	        R2	POTENTIOMETER
1	NE555	 ICM555	        DIL08	        IC1	TIMER
2	LB10	 LB10	        LB10	        LB1,LB2	10 LED BLOCK
1	SW	 PB7-0	        PB07_0	SW1	8x8mm   DPDT Self-locking Switch
2	RJ11	 RJ11-6PTH	95001-6P6C	J2, J4	RJ12 Socket 95001-6P6C Female



## Author and license
* Author: [XDeSIG][TWI01]
* License: [Attribution-ShareAlike 4.0 International] [CCBY-SA4.0]

<!-- links -->

[CCBY-SA4.0]: http://creativecommons.org/licenses/by-sa/4.0/
[TWI01]: https://twitter.com/xdesig
[PHT]: test_rj45_THT_Master_up.png
[RENDER]: test_rj45_THT_Remote.png

[PCBWAY]: https://www.pcbway.com/project/shareproject/Cable_Test_RJ45___RJ12.html


