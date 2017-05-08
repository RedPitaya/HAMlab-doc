.. _update:
Update HAMlab software
######################

Instead of writing the whole SD card image,
it is possible to update only the ecosystem.

********************
Web interface update
********************

At boot HAMlab checks for software updates,
and alerts the user if a new release is available.
Users can also check for updates manually.

#. Open HAMlab desktop using your WEB browser.

#. Click on the system icon.

	.. image:: system.png
   
#. Then click onto update icon.
	
	.. image:: update.png

#. Select ecosystem version and start OS updater

#. Follow the steps in the OS updater app in order to install new OS.
   
.. note::
   
   OS update might cause your HAMlab desktop to freeze for a few minutes.

**************
Manual upgrade
**************

A manual upgrade allows you to fix a corrupted SD card image
(if only the FAT partition is corrupted) or to install
older, newer or custom ecosystem zip files.

#. Download a zip file from our `download server <http://downloads.redpitaya.com/downloads/hamlab_0.97/>`_.

#. Insert SD card into card reader.

#. Delete all files from the FAT partition.
   Use ``Shift + Delete`` to avoid placing files
   into a trash bin on the same partition.

#. Extract the ecosystem zip file contents onto the now empty partition.

If you wish too keep wireless settings skip deleting the next files:

* ``wpa_supplicant.conf``
* ``hostapd.conf``
