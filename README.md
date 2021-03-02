# Cable Test V0.4

You want a PCB to exercise or learn to solder THT components, here you have one of many.
This provides you with a device to test network cables (RJ45) and telephone cables (RJ12 / 11),
made with normal components, (the most complicated being the LED bar).
You can be complemented with more diodes 1N4148 in anti-parallel soldiers under the LEDS (2, 5..9) to allow to check all cable faults.

Buy PCB in [PCBWAY]


![Top view][PHT]
![Render][RENDER]

#B.O.M.
<table cellspacing="0" border="0">
	<colgroup width="38"></colgroup>
	<colgroup width="70"></colgroup>
	<colgroup span="2" width="133"></colgroup>
	<colgroup width="122"></colgroup>
	<colgroup width="85"></colgroup>
	<tr>
		<td height="17" align="left">Qty </td>
		<td align="left">Value</td>
		<td align="left">Device</td>
		<td align="left">Package</td>
		<td align="left">Parts</td>
		<td align="left">Description</td>
	</tr>
	<tr>
		<td height="17" align="left"><br></td>
		<td align="left"><br></td>
		<td align="left"><br></td>
		<td align="left"><br></td>
		<td align="left"><br></td>
		<td align="left"><br></td>
	</tr>
	<tr>
		<td height="17" align="right" sdval="2" sdnum="1110;">2</td>
		<td align="left"><br></td>
		<td align="left"> DS1128-S80BP</td>
		<td align="left">DS1128-S80BP</td>
		<td align="left">J1, J3</td>
		<td align="left">Ethernet Connector</td>
	</tr>
	<tr>
		<td height="17" align="right" sdval="1" sdnum="1110;">1</td>
		<td align="left"><br></td>
		<td align="left"> BATTERY9V</td>
		<td align="left">BATTCON_9V</td>
		<td align="left">BAT1</td>
		<td align="left">Battery Holders</td>
	</tr>
	<tr>
		<td height="17" align="right" sdval="1" sdnum="1110;">2</td>
		<td align="left">100nF</td>
		<td align="left"> C2.5/2</td>
		<td align="left">C2.5-2</td>
		<td align="left">C2, C3</td>
		<td align="left">CAPACITOR</td>
	</tr>
	<tr>
		<td height="17" align="right" sdval="2" sdnum="1110;">2</td>
		<td align="left">10K</td>
		<td align="left"> 1/4 Watt</td>
		<td align="left">0204/7</td>
		<td align="left">R1, R3</td>
		<td align="left">RESISTOR</td>
	</tr>
	<tr>
		<td height="17" align="right" sdval="1" sdnum="1110;">1</td>
		<td align="left">10uF/16V</td>
		<td align="left">2.5mm&ndash;6mm</td>
		<td align="left">E2,5-6</td>
		<td align="left">C1</td>
		<td align="left">POLARIZED CAPACITOR</td>
	</tr>
	<tr>
		<td height="17" align="right" sdval="1" sdnum="1110;">1</td>
		<td align="left">1K</td>
		<td align="left"> R-EU_0204/7</td>
		<td align="left">0204/7</td>
		<td align="left">R4</td>
		<td align="left">RESISTOR</td>
	</tr>
	<tr>
		<td height="17" align="right" sdval="1" sdnum="1110;">8</td>
		<td align="left">1N4148</td>
		<td align="left"> DIODE-D-2.5</td>
		<td align="left">D-2.5</td>
		<td align="left">D1...D8</td>
		<td align="left">DIODE</td>
	</tr>
	<tr>
		<td height="17" align="right" sdval="1" sdnum="1110;">1</td>
		<td align="left">4017N</td>
		<td align="left"> 4017N</td>
		<td align="left">DIL16</td>
		<td align="left">IC2</td>
		<td align="left">COUNTER/DIVIDER</td>
	</tr>
	<tr>
		<td height="17" align="right" sdval="1" sdnum="1110;">1</td>
		<td align="left">47K</td>
		<td align="left"> TRIM_EU-CA6V</td>
		<td align="left">CA6V</td>
		<td align="left">R2</td>
		<td align="left">POTENTIOMETER</td>
	</tr>
	<tr>
		<td height="17" align="right" sdval="1" sdnum="1110;">1</td>
		<td align="left">NE555</td>
		<td align="left"> ICM555</td>
		<td align="left">DIL08</td>
		<td align="left">IC1</td>
		<td align="left">TIMER</td>
	</tr>
	<tr>
		<td height="17" align="right" sdval="1" sdnum="1110;">2</td>
		<td align="left">LB10</td>
		<td align="left"> LB10</td>
		<td align="left">LB10</td>
		<td align="left">LB1,LB2</td>
		<td align="left">10 LED BLOCK</td>
	</tr>
	<tr>
		<td height="17" align="right" sdval="1" sdnum="1110;">1</td>
		<td align="left">SW</td>
		<td align="left"> PB7-0</td>
		<td align="left">PB07_0</td>
		<td align="left">SW1</td>
		<td align="left">8x8mm   DPDT Self-locking Switch</td>
	</tr>
	<tr>
		<td height="17" align="right" sdval="2" sdnum="1110;">2</td>
		<td align="left">RJ11</td>
		<td align="left"> RJ11-6PTH</td>
		<td align="left">95001-6P6C</td>
		<td align="left">J2, J4</td>
		<td align="left">RJ12 Socket 95001-6P6C Female</td>
	</tr>
</table>


## Author and license
* Author: [XDeSIG][TWI01]
* License: CERN-OHL-W V2 [CERN-OHL] and Attribution-ShareAlike 4.0 International [CCBY-SA4.0]


<!-- links -->

[CERN-OHL]: https://ohwr.org/cernohl
[CCBY-SA4.0]: http://creativecommons.org/licenses/by-sa/4.0/
[TWI01]: https://twitter.com/xdesig
[PHT]: Cable-Test-RJ45-RJ12_Master_up.png
[RENDER]: Cable-Test-RJ45-RJ12_Remote.png

[PCBWAY]: https://www.pcbway.com/project/shareproject/Cable_Test_RJ45___RJ12.html


