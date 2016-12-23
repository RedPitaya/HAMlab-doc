.. _sdr:

Power SDR
######### 

Power SDR Instalation
+++++++++++++++++++++

Power SDR installation and SDR configuration
--------------------------------------------

.. _here: http://downloads.redpitaya.com/hamlab/powersdr/Setup_PowerSDR_Charly_25_HAMlab_Edition.exe
Click here_ to download Power SDR installation package.


1. Start the installation by double clicking on the Setup_PowerSDR_Charly_25_HAMlab_Edition.exe file.

	.. image :: HamLab_images/PowerSDRinstallation1.PNG


2. If you are asked for extended user access rights during the installation click Yes! Running installer with administration rights will work as well. 
	
	.. image :: HamLab_images/PowerSDRinstallation2.PNG
	
On Windows 10 you might get warning of Unknown Publisher you can procede with installation by clicking on "more info" and then "Run anyway".
 
	.. image :: HamLab_images/PowerSDRinstallation3.PNG
	.. image :: HamLab_images/PowerSDRinstallation4.PNG

3. Follow the instructions of the setup routine and accept the license agreements if asked for.


4. At the end of the installation you are asked if you want to run PowerSDR Charly 25 / Hamlab Edition software immediately, feel free to do so.


5. After starting the PowerSDR Charly 25 / Hamlab Edition software the first time you will be led through the PowerSDR Charly 25 / Hamlab Edition specific setup wizard which lets you configure the software to use it with your Hamlab.

So please choose Hamlab as your radio model:

.. image :: ../appsFeatures/powersdrsetup01.jpg

6. Confirm the RedPitaya as HPSDR hardware (currently there is no other type of hardware available for the Hamlab).

.. image :: ../appsFeatures/powersdrsetup02.jpg

7. Select the region where you are using your Hamlab, this is important due to the different frequency ranges your are allowed to transmit in the different countries all over the world:

.. image :: ../appsFeatures/powersdrsetup03.jpg

8. Your initial setup is completed:

.. image :: ../appsFeatures/powersdrsetup04.jpg

9.  After clicking the Finish button PowerSDR Charly 25 / HAMlab Edition will start with the calculation of the FFT wisdom file, **which will take a while** depending on the CPU power of your computer.
This is only done once, even after updating the software to a new version in the future:

.. image :: ../appsFeatures/powersdrsetup05.jpg

10. When all calculations are done, PowerSDR Charly 25 / HAMlab Edition will come up with the main window:

.. image :: ../appsFeatures/powersdrsetup06.jpg

11. Click Power to connect Power SDR with HAMlab. On the screen the input singnal should appear.

.. image :: ../quickStart/HamLab_images/SDRconnectepower.PNG



Power SDR configuration
+++++++++++++++++++++++
Audio configuration
HAMlab configuration
    
    
Power SDR basic usage
+++++++++++++++++++++   
 
Putting HAMlab into SDR mode
Connecting Power SDR with HAMlab
Receiving 
Transmitting

Credits
+++++++

Original developer of sdr-transceiver-hpsdr web application is Pavel Demin. 
Original developer of PowerSDR is FlexRadio Systems. 

Repositories used for our builds:

	- https://github.com/RedPitaya/PowerSDR_HPSDR_mRX_PS
	- https://github.com/RedPitaya/red-pitaya-notes

   
