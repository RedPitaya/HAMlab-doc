What is in the box 
##################

The following accessories and materials are included with your HAMlab kit. Carefully remove the HAMlab device and accessories from its shipping package and identify the items listed below. 

	* HAMlab 80-10 10W
	* DC power cord with Anderson Power Pole™ connector
	* Ethernet cable   
	* USB 2.0 Cable - A-Male to Mini-B

.. +---------------------------------+----------------+------------+
.. |       HAMlab 80-10  		  | 	basic	   |	full    |
.. +=================================+================+============+
.. | HAMlab 80-10 10W      	  |      ✓         |     ✓      |
.. +---------------------------------+----------------+------------+
.. | DC power cord with 		  |		   | 		|
.. | Anderson Power Pole™ connectors |    ✓       	   |    ✓       |
.. +---------------------------------+----------------+------------+
.. | Ethernet cable       		  |      ✓   	   |       ✓    |
.. +---------------------------------+----------------+------------+
.. | USB 2.0 Cable - A-Male to Mini-B|  	  ✓        |    ✓       |
.. +---------------------------------+----------------+------------+
.. | Microphone         		  |   	    x      |       ✓    |
.. +---------------------------------+----------------+------------+
.. | Power supply      		  |   	x  	   |     ✓      |
.. +---------------------------------+----------------+------------+
.. | Two oscilloscope probes         |         x      | 	✓	|
.. +---------------------------------+----------------+------------+
.. | Logic analyzer cable and probes |         x      |    ✓     	|
.. +---------------------------------+----------------+------------+
.. _shop: http://redpitaya.com/hamlab/#Products

Other additional requirements
#############################

In addition to the supplied accessories, software and cables supplied with the HAMlab, you will need to provide the following:

	* An **HF-Antenna** or dummy load with BNC or SO-239 connector
	* powered **stereo speakers** (computer type) or stereo headphones
	* **router** with enabled **DHCP** and connection to the internet
	* good RF **ground**	
	* HAMlab compatible Microphone 	available in HAMlab shop_ .
	* A stabilized DC 13.8 VDC, 3A **Power Supply**
	* Oscilloscope and logic analyzer probes available in HAMlab shop_ . 


SDR application requirements:

	* Personal computer (PC) running Windows 7 or later. Either 32 or 64-bit operating systems are supported. 


Instrumentation applications requirements: 

	* All instrumentation applications are WEB based and don’t require the installation of any native software. Users can access them via a browser using their smartphone, tablet or a PC running any popular operating systems (macOS, Linux, Windows, Android or iOS).


Start using HAMlab measurment instruments
#########################################

Connecting the cables
---------------------

Back panel connections
++++++++++++++++++++++

HAMlab should be powered by DC 13.8V Power Supply that can provide at least 3A of constant power. Make sure that is turned off and then use DC power cord with Anderson Power Pole™ connector to connect it with HAMlab. RED wire is positive (+) while BLACK wire is negative (-), double check to not mix the colours or polarity! 
Don’t turn on the power supply yet.

.. image:: hamlab/IMG_20161130_090117.jpg

**Ethernet Connection** - connect the HAMlab to your local network using ethernet cable.

.. image:: hamlab/IMG_20161130_090107.jpg

.. note::
	
	Other connections are at the moment not important, you can read more about them later in the :ref:`back` section.

Front panel connections
+++++++++++++++++++++++

Oscilloscope probes 

.. image:: hamlab/IMG_20161130_090049.jpg

Logic analyzer probes 

.. image:: hamlab/IMG_20161130_090059.jpg


Turning it on and start using mesuring instruments
--------------------------------------------------

	1) Turn on power supply, HAMlab will start automatically. Blue led on power button will turn on. Next time you can momentary press on the power button to turn it on.

.. image:: hamlab/IMG_20161130_132527.jpg
	
	2) Make sure your computer is connected to same local area network as HAMlab.
	3) On your computer start a WEB browser (Chrome recommended).
	
	4) Type in the HAMlab URL.
	
.. image:: hamlab/14-20-22.png

URL can be found on the back panel of the HAMlab.

.. image:: hamlab/IMG_20161130_132607.jpg

HAMlab application page should appear where measurement applications are listed.
     
.. image:: hamlab/14-19-19.png

Click on application to run it. 




.. note:: 
	
	More details about HAMlab instruments can be found in the Applications & features section.
	
	Instruments applications documentation:

	* :ref:`oscapp`
	* :ref:`laapp`
	* :ref:`saapp`


Start using HAMlab as Radio Station - SDR
#########################################

Connecting the cables
---------------------

Back panel connections
++++++++++++++++++++++


Antenna - Connect an HF antenna with nominal 50 Ohm impedance to the SO-239 connector.

.. image:: hamlab/IMG_20161130_090121.jpg

.. hint::
	If you prefer BNC connector you can remove HAMlab top cover and reconnect it from SO-239 to BNC.
	
Ground - Remove the thumb screw marked GND. Connect your central station ground to the thumb screw and screw it back into the radio.

.. image:: hamlab/IMG_20161130_090117.jpg

Speakers - connect powered stereo speakers to the jack 

.. image:: hamlab/IMG_20161130_090113.jpg

.. note::

	You can instead of speakers connect headphones on the front panel.

USB cable - connect the HAMlab with the PC using USB 2.0 Cable - A-Male to Mini-B

.. image:: hamlab/IMG_20161130_090113.jpg

Ethernet Connection - connect the HAMlab to your local network using ethernet cable

.. image:: hamlab/IMG_20161130_090107.jpg

HAMlab should be powered by DC 13.8V Power Supply that can provide at least 3A of constant power. Make sure that is turned off and then use DC power cord with Anderson Power Pole™ connector to connect it with HAMlab. RED wire is positive (+) while BLACK wire is negative (-), double check to not mix the colours or polarity! 
Don’t turn on the power supply yet.

.. image:: hamlab/IMG_20161130_090117.jpg

.. note::

	Other connections are at the moment not important, you can read more about them later in the :ref:`back` section.


Front panel connections
+++++++++++++++++++++++


.. image:: hamlab/IMG_20161130_132542.jpg

Phones (optional if speakers are not connected)

.. image:: hamlab/IMG_20161130_090056.jpg

Iambic Morse Code Paddle Keyer Plug

.. image:: hamlab/IMG_20161130_090056.jpg

.. note::

	More information about compatibility of microphone, key and headphones and front panel connections in general can be found in the :ref:`front` section.


Turn it on & put HAMlab in SDR mode
-----------------------------------


Turn on power supply, HAMlab will start automatically. Next time you can momentary press on the power button to turn it on/off.
Make sure your computer is connected to same local area network as HAMlab
On your computer start a WEB browser (Chrome recommended)

.. image:: hamlab/14-20-22.png
   :align: center


Type in the HAMlab URL that can be found on the back panel of the HAMlab

.. image:: hamlab/IMG_20161130_132607.jpg

HAMlab application page should appear 
     
.. image:: hamlab/14-19-19.png

Click on the SDR icon in order to put HAMlab into SDR mode. Once in this mode user can connect to HAMlab using Power SDR software.

.. note::

	Exiting this web application will close the connection to Power SDR.

Congratulations, HAMlab is now ready for use, now let’s install Power SDR.


Power SDR installation & configuration (TBD, images)
----------------------------------------------------

:ref:`SDR`

Click here to download Power SDR installation package

Select HAMlab hardware

Audio setup: VAC1 setup -> select USB codec 

Click POWER to connect to HAMlab

START USING POWER SDR SOFTWARE
++++++++++++++++++++++++++++++

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
 
	Power SDR software is described in Power :ref:`sdr` section.

Troubleshooting
###############

In case ob sd card failiure new HAMlab OS memory card will have to be prepaired.
 
 1) power off HAMlab
 2) remove sd card from HAMlab
 3) insert sd cart into computer
 4) folow new :ref:`sdcard` guide to create new sd card with HAMlab OS
 5) insert sd cart into HAMlab and power it on


