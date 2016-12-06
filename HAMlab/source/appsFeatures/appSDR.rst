.. _sdr:

SDR
###
    
SDR HPSDR
---------

In order to use HAMlab in SDR mode You must run SDR HPSDR web application first. 

.. image :: hpsdr_icon.png
   :alt: icon
   :align: center

While web application is running HAMlab will be in SDR mode and you can connect to it with PowerSDR software to use it as radio.
   
.. image :: webapp.png   


	
Power SDR
---------    
    
Power SDR installation
++++++++++++++++++++++

1. After downloading the PowerSDR Charly 25 / Hamlab Edition software from here_ .

.. _here: http://downloads.redpitaya.com/hamlab/powersdr/Setup_PowerSDR_Charly_25_Hamlab_Edition.exe

Start the installation by double clicking on the Setup_PowerSDR_Charly_25_Hamlab_Edition.exe file.


2. If you are asked for extended user access rights during the installation click Yes!


3. Follow the instructions of the setup routine and accept the license agreements if asked for.


4. At the end of the installation you are asked if you want to run PowerSDR Charly 25 / Hamlab Edition software immediately, feel free to do so.


5. After starting the PowerSDR Charly 25 / Hamlab Edition software the first time you will be led through the PowerSDR Charly 25 / Hamlab Edition specific setup wizard which lets you configure the software to use it with your Hamlab.

So please choose Hamlab as your radio model:

.. image :: powersdrsetup01.jpg

6. Confirm the RedPitaya as HPSDR hardware (currently there is no other type of hardware available for the Hamlab).

.. image :: powersdrsetup02.jpg

7. Select the region where you are using your Hamlab, this is important due to the different frequency ranges your are allowed to transmit in the different countries all over the world:

.. image :: powersdrsetup03.jpg

8. Your initial setup is completed:

.. image :: powersdrsetup04.jpg

9.  After clicking the Finish button PowerSDR Charly 25 / Hamlab Edition will start with the calculation of the FFT wisdom file, which will take a while depending on the CPU power of your computer.
This is only done once, even after updating the software to a new version in the future:

.. image :: powersdrsetup05.jpg

10. When all calculations are done, PowerSDR Charly 25 / Hamlab Edition will come up with the main window:

.. image :: powersdrsetup06.jpg



Power SDR configuration
+++++++++++++++++++++++

Power SDR basic usage
+++++++++++++++++++++    


Credits
+++++++

Original developer of sdr-transceiver-hpsdr web application is Pavel Demin. 
Original developer of PowerSDR is FlexRadio Systems. 

Repositories used for our builds:

	- https://github.com/RedPitaya/PowerSDR_HPSDR_mRX_PS
	- https://github.com/RedPitaya/red-pitaya-notes

   
