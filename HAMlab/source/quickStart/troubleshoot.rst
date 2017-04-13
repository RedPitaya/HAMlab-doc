Troubleshoot
$$$$$$$$$$$$

Damaged or corrupted SD card
----------------------------

HAMlabs equivalent for geting your sistem back into factory setings is preparing new sd card. This should be done in case of sd card failiure. In that situation new HAMlab OS memory card will have to be prepaired.
Please folow this steps to achieve this:

 1) Power off HAMlab
 2) Remove sd card from HAMlab
 3) Insert sd cart into computer
 4) Folow :ref:`sdcard` guide to create new sd card with HAMlab OS
 
In case that written sd card does not behave as expected please use new sd card, size should be at least 4 Gb and it should be specified as class 10.


Power SDR cannot connect to HAMlab
----------------------------------

After clicking Power button the Power SDR application should automatically connect to HAMlab and receiving signal should appear in the panadapter. 
If the following msg. appears on screen after clicking the Power button this means that:

.. image :: HamLab_images/SDRapplicationnotrunningonHAMlaborcnnectionproblems.PNG

HAMlab might not be connected to same network as computer that is running Power SDR application

SDR transceiver application was not started or is not running on HAMlab

When trying to run PowerSDR please run SDR HPSDR web application before starting Power SDR.


Audio board not working
-----------------------

(This  troubleshoot is only for HAMlab 80-10 10W model)

If audio there is no sound coming from your headphones or speaker connected to HAMlab while running Power SDR application please make sure that: 
HAMlab is connected to PC that is running Power SDR with USB cable



Check audio setings on your computer

.. image :: HamLab_images/Volume.PNG

Set correnct Power SDR avdio settings

.. image :: HamLab_images/PowerSDRaudiosetup.PNG

Make sure that HAMlab audio card was recognized by your Windows OS and driver is properly installed. 

Open control panel.

.. image :: HamLab_images/opencontrolpanel.PNG

Click on Hardware and Sound

.. image :: HamLab_images/hardwareandsound.PNG

Check that audio card was recognized

.. image :: HamLab_images/devicemanager.PNG

You can also make a simple test by playing some music with media player.

.. image :: HamLab_images/recording_test.PNG

.. image :: HamLab_images/speaker_test1.PNG

.. image :: HamLab_images/speaker_test2.PNG



HAMlab doesn’t turn ON anymore
++++++++++++++++++++++++++++++

Make sure your power supply is on and properly connected.
Try to remove HAMlab cover and check the main fuse - if broken, try to replace it.

Cannot connect to HAMlab anymore
++++++++++++++++++++++++++++++++

Try to turn your HAMlab off and follow quick start procedure first.
If you hear that the fan doesn’t lower it’s power (revolutions) after 1 min after turning the HAMlab on this might suggest that SD card image (HAMlab software) is corrupted. 
In this case it is recommended to remove SD card and try to reinstall it. 

There is no transmit power from the HAMlab
++++++++++++++++++++++++++++++++++++++++++

If there is no transmit power from the device please check your Power SDR settings first.
In case that settings are not the case, please try to remove the cover of HAMlab and Transceiver module to replace the fuse.
