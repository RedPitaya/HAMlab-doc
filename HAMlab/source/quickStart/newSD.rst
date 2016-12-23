.. _sdcard:

Prepare SD card
################

1. Download latest HAMlab OS Image File 
    
    .. image:: microSDcard-RP.png
       :width: 10%
    
    `Download <http://downloads.redpitaya.com/hamlab/hamlab_ubuntu_11-34-26_14-dec-2016.img.zip>`_
    
2. Unzip

3. Select your operating system and follow the instructions:  

Windows
*******


    1. Insert SD card into your PC or SD card reader.
    
    .. image:: 1.jpg
    
    2. Download Win32 Disk Imager to your Desktop and unzip it.
    
    .. image:: 2.png
    
    3. Open unzipped folder, right-click on the WinDisk32Imager, and select 'Run as Administrator'.
    
    .. image:: 3.png
    
    4. Under image file box select unzipped HAMlab OS image file.
    
    .. image:: 4.png
    
    5. Under device box select the drive letter of the SD card.
    
    .. image:: 5.png
    
    .. note::
    
        Be careful to select the correct drive; if you choose the wrong one you risk erasing data from the 
        computer's hard disk! You can easily see the drive letter (for example E:) by looking in the left column 
        of Windows Explorer.
    
    .. image:: 5_2.png
    
    6. Click Write and wait for the write to complete.
    
    .. image:: 6.png
    
    7.  Exit the Imager.
    
    .. image:: 7.png
    
Linux
*****

    1. Insert SD card into your PC or SD card reader.
    
    .. image:: 1.jpg 
    
    2. Run Disks application to format the SD card.
    
    .. image:: ubuntu_disk_format.jpg
    
    3. Open the Terminal and check the available disks with "df -h". Our SD card is 4GB and mounted to /dev/sdb

    .. image:: ubuntu_sdprepare1.png
    
    4. Unmount the SD card with "umount /dev/sdbN" (make sure you replace N with the right number).
    
    .. image:: ubuntu_sdprepare3.png
    
    5. Write the image to the SD card with the following command : dd if=image_file of=/dev/sdb bs=1M
    
    .. note::
    
        Replace the red_pitaya_image_file with the name of the unzipped Red Pitaya SD Card Image and
        /dev/device_name is replaced with the path to the SD Card, usually it will be /dev/sdb.
    
    .. image:: 51.png
    
    
    6. Wait until the process has finished.
    
    .. image:: 61.png

MacOS
*****
    
    1. Insert SD card into your PC or SD card reader.
    
    .. image:: 1.jpg
    
    2. Download Apple Pi Baker and unzip it.
    
    .. image:: 21.png


    3. Press "crtl" key and click on ApplePi-Baker icon, then click Open in order to run it.
    
    .. image:: 3-1.png


    4. Enter your admin password and click OK.
    
    .. image:: 41.png


    5. Select SD card drive. This can be recognized by the size of the card that is 4GB.
    
    .. image:: 52.png


    6. Select HAMlab OS image file.
    
    .. image:: 62.png

    7. Click "Restore Backup" button in order to write image to SD card.
    
    .. image:: 71.png


    8. It's coffee time, application will show you Estimated Time for Accomplishment.

    .. image:: 8.png

    9. When operation is completed click "OK" and quit ApplePi-Baker.

    .. image:: 9.png
    
    FAQ: `How to install HAMlab OS on MAC not using ApplePiBaker? <http://blog.redpitaya.com/faq-page/#QuickStart|23547>`_

4.  Now you have a brand new Micro SD card with latest HAMlab OS. Insert it into HAMlab with contacts facing up.

    .. image:: HamLab_images/sd_card.png
    
5.  Power on Power Supply

6.  Turn HAMlab ON by shortly pressing Power Button
 

.. note ::

	You can also use cross platform `Etcher <https://etcher.io/>`_ for burning your SD Card.
