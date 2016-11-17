
Specifications
##############

SDR specifications
Highlights:

+-------------------------------+------------------------------------------------------------------------------------------------------------+
| Architecture:			| direct sampling / internal high performance 14-bit A/D and D/A 125Msps converters (no sound card required) |
+-------------------------------+------------------------------------------------------------------------------------------------------------+
| Band coverage:		| All band receiver with 5 bands transmitter (80,40,20,12/10m)						     |
+-------------------------------+------------------------------------------------------------------------------------------------------------+
| Transmit power: 		|	up to 10W											     |
+-------------------------------+------------------------------------------------------------------------------------------------------------+
| Wideband Frequency Coverage:  |	25 kHz - 62.25 MHz										     |
+-------------------------------+------------------------------------------------------------------------------------------------------------+
| Connection to PC: 		|	1Gbit ethernet or WIFI connection							             |
+-------------------------------+------------------------------------------------------------------------------------------------------------+
| Software: 			|	Power SDR, HDSPR, Gqrx, GNU Radio, GNU Radio Companion and Pothos				     |
+-------------------------------+------------------------------------------------------------------------------------------------------------+
| Phones and MIC connection: 	|	available on the front panel				                                             |
+-------------------------------+------------------------------------------------------------------------------------------------------------+
| Secondary Rx and Tx channel:  |	available through back panel BNC connectors (RX2 IN, XVTX) 					     |
+-------------------------------+------------------------------------------------------------------------------------------------------------+
| CW key and paddle input: 	|	available through front panel jack connector	 						     |
+-------------------------------+------------------------------------------------------------------------------------------------------------+

Receiver Specifications:

+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Architecture:					| Direct Digital Sampling 									|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|ADC Sampling Rate:				| 125Msps 											|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|ADC Resolution:				| 14 bits											| 
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Wideband Frequency Coverage:			| 25 kHz - 62.25 MHz										|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|MDS (min. detectable signal):			| MDS (typ)@ 500Hz BW										|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Preamp OFF at 14MHz				| -113dBm											|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Preamp +15dB at 14MHz				| -130dBm											|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Preamp +30dB at 50MHz				| NA												|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|						| More MDS measurements. 									|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Preselectors:					| Available as add-on module (comming soon)							|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|						| User can also connect own preselectors/filters to back panel BNC connectors (RX1 IN, RX1 OUT) |   
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+

Transmitter Specifications:			

+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Architecture:					| Direct Digital Up-conversion									|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|TX DAC Sampling Rate:				| 125Msps											|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|TX DAC Resolution:				| 14 bits											|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|RF Output Power:				| up to 10W CW and SSB at @ 13.8V input voltage (max. 15V)					|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Transmitter Frequency Range:			|	80 - 10m (amateur bands only)								|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Low Pass PA Filter Bands:			| 80, 40, 20, 12/10 m (possibility to changed it to any range 1.8 - 50MHz)			|	
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Emission Modes Types:				| not limited by HAMlab hw, depending on 3rd party SDR software used				|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Harmonic Radiation:				| better than -45 dB										|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|3rd-Order IMD:					| better than -35 dB below PEP @ 14.2 MHz 10 Watts PEP						|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Cooling:					| copper heat spreader										|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Microphone connector:				| RJ45												|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Microphone impedance:		         	|	600 ohm unbalanced									|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+

General Specifications:		        		 										

+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Frequency Stability:			        | TBD 												|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Antenna Connector:		                | SO-239 UHF or BNC back panel connector (ANT1, ANT2) 						|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Antenna Impedance:			        | 50 Ohm Unbalanced 										|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|RF Output Power:		                | up to 10W CW and SSB at 13.8V input voltage (max. 15V) 					|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Maximum Interconnect Cable Length Ethernet:    |	100 meters (328 feet), Category 5 cable 						|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+
|Power connector:			        |	PowerPole 										|
+-----------------------------------------------+-----------------------------------------------------------------------------------------------+

HAMlab system architecture
##########################

SDR block diagram r2

!!!!!!!!!!!!inset image!!!!!!!!!!!


Front panel controls and connecrions 
####################################

!!!!!!!!!!!!inset image!!!!!!!!!!!


1 - power button 
Momentarily pressing will turn the HAMlab ON. It normally takes 30s from the button press until the HAMlab is ready to be used. Once HAMlab is ON, momentarily pressing will cause the proper shut down of the device. Blue LED indication on the power button indicates that device is turned on.

.. note::
	In case that system halts and becomes unresponsive, device can be turned off by holding power button for a few seconds / until the blue LED is turned off. 


SDR
2 - Microphone connector (RJ45)
Front panel view

!!!!!!!!!!!!inset image!!!!!!!!!!!


Pin 1 NC
Pin 2 8V DC
Pin 3 Ground
Pin 4 PTT 
Pin 5 Ground
Pin 6 MIC
Pin 7 NC
Pin 8 NC
The HAMlab 80-10 10W front microphone connector can support Kenwood HM-152 electret microphone
or compatible types.


3 - Phones


The HAMlab 80-10 10W supports a stereo headset with headphone ¼ inch TRS phone plug.
Mono or TS connector that grounds the “ring” portion of the connector should not be used!


4 - CW Key / paddle jack
The CW key/paddle jack is a ¼ inch TRS phone plug. 
Tip - DOT
Ring - DASH
The common is connected to the sleeve. 


.. note::
	3.3V Max input.


For an iambic paddle, the tip is connected to the dot paddle, the ring is connected to the dash paddle and the sleeve is connected to the common. For a straight key or a keyer output, connect to the tip and leave the ring floating. The common is connected to the sleeve. 


Oscilloscope
5 - IN1
6 - IN2
7 - EXT. TRIG.
IN1, IN2 and EXT. TRIG. are oscilloscope inputs. 

.. note::

	These inputs are active and can be used only when Oscilloscope+Signal generator WEB application is running. 


Signal generator
8 - OUT1
9 - OUT2
OUT1 and OUT2 are signal generator outputs. 

.. note::

	These two outputs are active and can be controlled only when Oscilloscope+Signal generator WEB application is running.


.. note::

	To get expected signals from the signal generator, outputs must be 50ohm terminated.


Logic analyzer

0-7 are logic analyzer inputs. 
G - common ground. 


.. note::
	
	Logic analyzer inputs can only be used when running Logic analyzer WEB app.





Back panel controls and connections 
###################################

1 - ANT - TRANSCEIVER ANTENNA PORTS [1,2] 
ANT1 is SO-239 50 ohm connector, while ANT2 is BNC 50 ohm connector. 


User can connect transmitter output to ANT1 or ANT2 by properly connecting SMA cable inside the chassis to one of ANT connectors. Software switching between ANT1 and ANT2 is not available in HAMlab 80-10 10W version.

.. caution::

	THIS UNIT GENERATES RADIO FREQUENCY (RF) ENERGY. USE CAUTION AND OBSERVE PROPER SAFETY PRACTICES REGARDING YOUR SYSTEM CONFIGURATION. WHEN ATTACHED TO AN ANTENNA, THIS RADIO IS CAPABLE OF GENERATING RF ELECTROMAGNETIC FIELDS WHICH REQUIRE EVALUATION ACCORDING TO YOUR NATIONAL LAW TO PROVIDE ANY NECESSARY ISOLATION OR PROTECTION REQUIRED, WITH RESPECT TO HUMAN EXPOSURE! 

.. caution::

	NEVER CONNECT OR DISCONNECT ANTENNAS WHILE IN TRANSMIT MODE. THIS MAY CAUSE ELECTRICAL SHOCK OR RF BURNS TO YOUR SKIN AND DAMAGE TO THE UNIT. 


2 - AUX1
RX1 IN - direct feed to the first receiver pre-amp and attenuators.
RX1 OUT - an output from the antenna feeding 


By default HAMlab 80-10 10W comes with loopback cable connected from RX1 IN to RX1 OUT. User can also use this two connectors to insert external filters or preamplifier.


.. note::
	this input is not protected by any ESD circuitry, therefore device connected to the RX1 OUT Output is susceptible to possible damage by ESD from an EMP event if the connected device does not have adequate ESD protection circuitry. 


3 - AUX2
RX2 IN - secondary 50ohm receiver input that can be used as a second panadapter in Power SDR software
or to as feedback signal for pre-distortions (Pure Signal tool). 


XVTR (TX2 OUT)  - secondary transmitter can be used to drive external PA
Max. output power is around 10 dBm @ 50ohm


4 - DC POWER INPUT
The HAMlab 80-10 10W  is designed to operate from a 13.8 volt nominal DC supply and required at least 3A.

.. caution::

	This unit must only be operated with the electrical power described in this manual. NEVER CONNECT THE +13.8VDC POWER CONNECTOR DIRECTLY TO AN AC OUTLET. This may cause a fire, injury, or electrical shock. 


The HAMlab 80-10 10W requires 13.8 VDC @ 3 amps measured at the radio in order to transmit maximum wattage. Multiple power cable connections between the power supply and the HAMlab 80-10 10W, a poorly regulated power supply, undersized power cable and very long power cable lengths will result in a voltage drop, especially under load. Any voltage deviation from 13.8 VDC will result in lower power output that the 10W nominal specification. 


For best results, select a linear or switching power supply that is well regulated and free of internally generated radio frequency noise. “Birdies” generated by a poorly filtered supply can often appear as signals in the Power SDR Panadapter display. 


The Anderson Powerpole™ connector contains 45 Amp pins to minimize voltage drop during transmit. The RED connection should be connected to the positive (+) lead of the power source. The BLACK connection should be connected to the negative (-) lead of the power source. 


I - If you choose to use your own Powerpole cabling, be sure to properly size the wire and the Powerpole connector to minimize voltage drop during transmit. Excessive voltage drop can cause lower transmit power output levels. 


Fuse
There are two internal fuses in the HAMlab. One is protecting whole system while the other one is just for the transceiver. If you ever need to replace the internal fuse, remove the top cover and the shield of the power board.  


!!!!!!!!!!!!inset image!!!!!!!!!!!

.. caution::

	FUSE CURRENT RATING SHOULD NOT BE HIGHER THAN ?? AMPS! FAILURE TO PROPERLY USE THIS SAFETY DEVICE COULD RESULT IN DAMAGE TO YOUR RADIO, POWER SUPPLY, OR CREATE A FIRE RISK. 


5- Chassis ground
This is a thumbscrew for attaching an earth ground to the chassis of the radio. Grounding is the most important safety enhancement you can make to your shack. Always ground the HAMlab to your station RF ground using high quality wiring with the length being as short as possible.
Braided wire is considered the best for ground applications. Your station ground should be a common point where all grounds come together. You will likely be using a PC and a DC power source so be sure to ground these devices together as well. 


6 - AUDIO
Audio USB connector
USB 2.0 Cable - A-Male to Mini-B must be used to connect HAMlab audio sound card with the PC in order to be able to use Phone, MIC and speaker connector for voice communication.


Speaker connector 
1/8” TRS stereo connector can be used to connect stereo powered computer speakers.

.. note::
	
	Do not use a mono or TS connector that grounds the “ring” portion of the connector. 


7 - CTRL
DB9 connector is used to control external equipment.
PTT OUT relay is connected between pins 6 and 7. 

.. note::

	Other pins are at the moment not in use and should be left unconnected.


8 - DATA
LAN 
This is network connection to the HAMlab. It is an auto-sensing 100 megabit or 1 gigabit Ethernet port that enables you to connect HAMlab to your local network or directly to PC.


USB
This USB port is used to connect WIFI dongle when user would like to connect to HAMlab wirelessly.

.. note::

	Recommended WIFI USB dongle is Edimax EW7811Un. In general all WIFI USB dongles that use RTL8188CUS chipset should work.


SD card 
HAMlab software is running from SD card. 

.. note:: 
	
	HAMlab comes with pre installed SD card HAMlab OS. Upgrade can be done using OS upgrade application from the HAMlab application menu and there is no need to remove the SD card. Therefore user should remove the SD card and reinstall SD card software only if system gets corrupted or stops working due to SD card failure reason. In this case only official HAMlab OS should be installed on the SD card for proper operation.
	
   
