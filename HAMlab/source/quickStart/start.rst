
IMPORTANT NOTICE - READ BEFORE OPERATING THIS UNIT WARNING!
###########################################################

.. caution::

    This radio has been configured to operate in your country according to your nation's regulations when required. It may operate on frequencies which are not allowed for public use.
    You are required to have a valid amateur radio license of an appropriate class from your government to have the privileges to operate on amateur radio frequencies.
    Except those actions which have been described in this HAMlab, no other manipulations to the radio are allowed. The unit must only be opened and/or serviced by a qualified technician.
    These documents contain important information for safe operation, please study it!

    Radio frequency energy (RF) from transmitters can interact with some electronic devices, such as cardiac pacemakers and defibrillators. Please refer to the implanted pacemaker or defibrillator manufacturer's instructions with respect to precautions to be taken in the vicinity of an amateur radio transmitter. If any interaction or interference with a pacemaker or implanted defibrillator is suspected, STOP transmitting immediately!


What is in the box and other additional requirements
####################################################

The following accessories and materials are included with your HAMlab kit. Carefully remove the HAMlab device and accessories from its shipping package and identify the items listed below. 

+---------------------------------+----------------+------------+
|       HAMlab 80-10  		  | 	basic	   |	full    |
+=================================+================+============+
| HAMlab 80-10 10W      	  |      ✓         |     ✓      |
+---------------------------------+----------------+------------+
| DC power cord with 		  |		   | 		|
| Anderson Power Pole™ connectors |    ✓       	   |    ✓       |
+---------------------------------+----------------+------------+
| Ethernet cable       		  |      ✓   	   |       ✓    |
+---------------------------------+----------------+------------+
| USB 2.0 Cable - A-Male to Mini-B|  	  ✓        |    ✓       |
+---------------------------------+----------------+------------+
| Microphone         		  |   	    x      |       ✓    |
+---------------------------------+----------------+------------+
| Power supply      		  |   	x  	   |     ✓      |
+---------------------------------+----------------+------------+
| Two oscilloscope probes         |         x      | 	✓	|
+---------------------------------+----------------+------------+
| Logic analyzer cable and probes |         x      |    ✓     	|
+---------------------------------+----------------+------------+

In addition to the supplied accessories, software and cables supplied with the HAMlab, you will need to provide the following:

	* An **HF-Antenna** or dummy load with BNC or SO-239 connector
	* powered **stereo speakers** (computer type) or stereo headphones
	* **router** with enabled DHCP and connection to the internet
	* good RF **ground**
	* Items that might be already included in the kit:
	
		- HAMlab compatible Microphone
		- A stabilized DC 13.8 VDC, 3A power supply
		- Oscilloscope and logic analyzer probes


SDR application requirements:

	* Personal computer (PC) running Windows Vista Service Pack 2 or later. Either 32 or 64-bit operating systems are supported.

Instrumentation applications requirements: 

	* All instrumentation applications are WEB based and don’t require the installation of any native software. Users can access them via a browser using their smartphone, tablet or a PC running any popular operating systems (macOS, Linux, Windows, Android or iOS).


Start using HAMlab measurment instruments
#########################################

Connecting the cables
---------------------

Back panel connections
++++++++++++++++++++++

Power Supply - if you are using power supply that was not included in the kit, please make double check that it is a DC 13.8V power supply that can provide at least 3A of constant power. After that make sure it is turned off and connect DC power cord with Anderson Power Pole™ connectors to it. RED wire is positive (+) while BLACK wire is negative (-), make sure that you don’t mix the colours or polarity! After that gently connect power pole connector to HAMlab. Don’t turn on the power supply yet.

!!!!!!!!!!!!inset image!!!!!!!!!!!

Ethernet Connection - connect the HAMlab to your local network using ethernet cable

!!!!!!!!!!!!inset image!!!!!!!!!!!


.. note::
	
	Other connections are at the moment not important, you can read more about them later in the BACK PANEL CONTROLS AND CONNECTIONS section.


Front panel connections
+++++++++++++++++++++++

Oscilloscope probes 

!!!!!!!!!!!!inset image!!!!!!!!!!!

Logic analyzer probes 
      
!!!!!!!!!!!!inset image!!!!!!!!!!!


Turning it on and start using mesuring instruments
--------------------------------------------------

Turn on power supply, HAMlab will start automatically. Next time you can momentary press on the power button to turn it on/off.
Make sure your computer is connected to same local area network as HAMlab
On your computer start a WEB browser (Chrome recommended)

!!!!!!!!!!!!inset image!!!!!!!!!!!

Type in the HAMlab URL that can be found on the back panel of the HAMlab

!!!!!!!!!!!!inset image!!!!!!!!!!!

HAMlab application page should appear where measurement applications are listed 
     
!!!!!!!!!!!!inset image!!!!!!!!!!!

Click on application to run it. 

.. note:: 
	
	More details about HAMlab instruments can be found in the Applications & features section.

Start using HAMlab as SDR
#########################

Connecting the cables
---------------------

Back panel connections
++++++++++++++++++++++

Remove the top cover and connect the antenna SMA cable to your preferable connector type (ANT1 - SO239 or ANT2 - BNC ) Once this cable is connected place top cover back to it’s place and screw it.
Antenna - Connect an HF antenna with nominal 50 Ohm impedance to the the same connector that you connected antenna SMA cable

!!!!!!!!!!!!inset image!!!!!!!!!!!

Ground - Remove the thumb screw marked GND. Connect your central station ground to the thumb screw and screw it back into the radio.

!!!!!!!!!!!!inset image!!!!!!!!!!!

Speakers - connect powered stereo speakers to the jack (Notice that you can instead of speakers connect headphones on the front panel)

!!!!!!!!!!!!inset image!!!!!!!!!!!

Power Supply - if you are using power supply that was not inclueded in the kit, please make double check that it is a DC 13.8V power supply that can provide at least 3A of constant power. After that make sure it is turned off and connect DC power cord with Anderson Power Pole™ connectors to it. RED wire is positive (+) while BLAC wire is negative (-), make sure that you don’t mix the colours or polarity! After that gently connect power pole connector to HAMlab. Don’t turn on the power supply yet.

!!!!!!!!!!!!inset image!!!!!!!!!!!

USB cable - connect the HAMlab with the PC using USB 2.0 Cable - A-Male to Mini-B

!!!!!!!!!!!!inset image!!!!!!!!!!!

Ethernet Connection - connect the HAMlab to your local network using ethernet cable

!!!!!!!!!!!!inset image!!!!!!!!!!!

.. note::

	Other connections are at the moment not important, you can read more about them later in the BACK PANEL CONTROLS AND CONNECTIONS section.


Front panel connections
+++++++++++++++++++++++

Microphone

!!!!!!!!!!!!inset image!!!!!!!!!!!

Phones (optional if speakers are not connected)

!!!!!!!!!!!!inset image!!!!!!!!!!!

Key

!!!!!!!!!!!!inset image!!!!!!!!!!!


.. note::

	More information about compatibility of microphone, key and headphones and front panel connections in general can be found in the FRONT PANEL CONTROLS AND CONNECTIONS section.


Turn it on & put HAMlab in SDR mode
-----------------------------------


Turn on power supply, HAMlab will start automatically. Next time you can momentary press on the power button to turn it on/off.
Make sure your computer is connected to same local area network as HAMlab
On your computer start a WEB browser (Chrome recommended)

!!!!!!!!!!!!inset image!!!!!!!!!!!

Type in the HAMlab URL that can be found on the back panel of the HAMlab

!!!!!!!!!!!!inset image!!!!!!!!!!!

HAMlab application page should appear 
     
!!!!!!!!!!!!inset image!!!!!!!!!!!

Click on the SDR icon in order to put HAMlab into SDR mode. Once in this mode user can connect to HAMlab using Power SDR software.

.. note::
	Exiting this application will close the connection to Power SDR.


Congratulations, HAMlab is now ready for use, now let’s install Power SDR.
Power SDR installation & configuration (TBD, images)
----------------------------------------------------
Click here to download Power SDR installation package
…
Select HAMlab hardware
Audio setup: VAC1 setup -> select USB codec 
Click POWER to connect to HAMlab
START USING POWER SDR SOFTWARE


Setting the operating frequency or changing the band
Setting Rx attenuators and amplifiers
Transmitting
Applications & features

In order to use HAMlab as SDR user has to:
Run the SDR radio application on HAMlab - this will put HAMlab in SDR mode. 


Run the Power SDR program on the computer and connect to HAMlab


.. note:: 

	Exiting this SDR WEB application will close the connection to Power SDR.

.. note::
 
	Power SDR software is described in Power SDR section.


Power SDR
---------

Power SDR installation & configuration
++++++++++++++++++++++++++++++++++++++

Power SDR basic usage
+++++++++++++++++++++

Pre-distortions / pure signal

Network manager
