Connect to your Red Pitaya
###########################

.. TODO preveri slovnico

Network connectivity user guide
*******************************

For electronic equipment used today and tomorrow a network connectivity is and will be an industry standard. Red
Pitaya STEMLab boards are network attachable devices focused on simple connectivity and quick accessibility. Having a 
graphical user interface for your Oscilloscope, Signal Generator, LCR meter and other Red Pitaya applications, 
directly on your PC without any limitations such are limited commands or controls or any installation of additional 
software will provide you with a unique working experience. 
  
Red Pitaya STEMLab boards can be connected over:

    1. Local Area Network (LAN) – Requires DHCP settings on your local network rout  
    4. Direct Ethernet cable connection – Requires additional setting on users PC and STEMLab board
    2. Wireless Network – Requires an additional WiFi dongle available at Red Pitaya store
    3. Access Point Mode – STEMLab board creates its own WiFi network
    
.. image:: connect-1.png

Wired
*****

Local Area Network (LAN)  
========================

This is the most common and recommended way of connecting and using your Red Pitaya STEMLab boards. Your LAN network 
needs to have DHCP settings enabled which is the case in majority of the local networks,  whit this,  simple “plug and
play”  approach is enabled. Having STEMLab board connected the local network will enable quick access to all Red 
Pitaya applications using only your web browser. Simply follow this 3 simple steps:

    
    1. Connect power supply to the Red Pitaya STEMlab board
    2. Connect STEMlab board to the router or direc to the PC ethernet socket
    3. Open your web browser and in the URL filed type:   ``rp-xxxxxx.local/``
       
.. note::

    ``xxxxxx`` are the last 6 characters from MAC address of your STEMlab board. MAC address is written on the Ethernet 
    connector.
    
.. figure:: connect-2.png
    
    Figure 1: Connecting your STEMlab board to the LAN network.

After the **third step** you will get a Red Pitaya STEMlab main page as shown below.

.. figure:: connect-3.png

    Figure 2: STEMlab main page user interface.
    
Direct Ethernet cable connection
================================

If there are some restrictions for the user to have STEMlab boards on the DHCP LAN network **permanently** there is a 
possibility to directly connect to your STEMLab board. This type of connection requires additional settings on your PC
and STEMLab board. 

.. note::

    This connection is also arranged via Network manager application so users should first
    have access to the LAN  (DHCP) network in order to arrange static IP on the STEMlab board. 
    
How to set direct Ethernet connection is described bellow.

.. image:: connect-10.png

First step in connecting STEMlab board directly to LAN network and setting a static IP on it. 
    1. Use recommended connection described in **Local Area Network (LAN)** section. Once you are successfully 
       connected to your STEMlab board, open Network Manager and  chose “Static” option. Input the static IP, default
       getaway and DNS. Click “Apply”. **Fields Gateway and DNS can be left empty.**

    .. image:: connect-11.png


    2. Second step is to set a network setting on the PC
       Here we give an example on the Ubuntu 14.04 but it is very similar on the other OS also.
       To set a direct connection with your PC  follow next steps:
        
        1. Open network manager on your PC
        2. Add new Ethernet connection
           **(There is no need to create new network since you can set static IP settings on the existing network and**
           **skip all steps up to step 5. )**

    .. image:: connect-12.png
    
    3. Select “Ethernet” connection and press “Create” button

    .. image:: connect-13.png
    
    4. Select the name of the new Ethernet connections
    
    .. image:: connect-14.png

    5. Select “Method – Manual”, Press “Add” button and insert:

        - static IP address of your PC (must be different from the IP address of  the STEMlab board),  
        - Netmask (input: 255.255.255.0)
        - Getaway (can be left empty)
        - DNS servers  (can be left empty) and click  “Save” button.
    
    .. image:: connect-15.png 

    .. note::
    
        Once you have this settings arranged, connect Ethernet cable between your STEMlab board and  PC, open web
        browser, in the web browser URL field input chosen STEMlab board static IP (in our example it is 192.168.0.15) 
        and press enter.

    .. image:: connect-16.png 

.. TODO
.. USB Console connectivity
.. *************************
.. 
.. This type of connection is used for direct USB serial console connectivity. Here user access STEMLab board via 
.. console/terminal. This is useful for the developers and more demanding users. Connecting to the STEMLab board via USB 
.. will open Linux Terminal where user can control STEMLab board completely using command line tools. Notice: For STEMLab
.. 125-14 you need additional USB to microUSB cable, for STEMLab 125-10 additional serial to USB adapter.
.. 
.. .. image:: connect-17.png
.. 
.. 1. Connect your Red Pitaya and PC with micro USB B to USB A cable and follow the instructions for your OS.
.. 
.. .. image:: pitaya-USB-connection-300x164.png
.. 
.. Serial console connection is independent from the Ethernet connection. Use a Micro USB cable to connect your computer
.. with Red Pitaya. Connection instructions will be given for Windows, Linux and OS X users separately.
.. 
.. Serial port configuration:
.. 
.. .. image:: Selection_002.png
.. 
.. **User name and password to login are “root”.**
.. 
.. Windows users
.. =============
.. 
.. Download and install the `FTD driver <http://www.ftdichip.com/Drivers/VCP.htm>`_ to your PC. After installation, a new
.. COM port will appear in the Device Manager you can use in Hyperterminal or another terminal utility to connect to Red 
.. Pitaya.
.. 
.. `FAQ <http://redpitaya.com/faq/>`_    
    
Wireless
********
    
Wireless Network Connection
===========================

This type of the connection will enable wireless connection to the Red Pitaya STEMLab board via your local WiFi 
network. In order to connect your STEMLab board to the same WiFi network on which you have connected your PC/Laptop 
first you need to use LAN connection.  Access your STEMLab board via web browser and start Network Manager
application. Trough this application all network settings of the STEMLab board are manageable. Simply select the
desired WiFi network, input password and select connect. Once you have arranged WiFi network you don't need LAN
connection anymore and after the restart of the STEMLab board it will connect to the preset WiFi network
automatically.  Notice: Connecting the STEMLab via WiFi network the additional WiFi dongle is needed. WiFi dongle is
available here [Link to RS or similar].    

.. image:: connect-4.png

.. TODO link na Local Area Network (LAN)

Steps on how to connect your STEMlab board over WiFi network are described bellow:
 
    1. Start your STEMlab web user interface (Use connection described **Local Area Network (LAN) connection )**
    2. Open Network Manager application
    3. Insert WiFi dongle in the USB plug on the STEMlab board. Supported WiFi dongles are described here [ `FAQ <http://redpitaya.com/faq/>`_ ]
    


    .. image:: connect-5.png

    4. When the USB WiFi dongle is plugged in, the system will recognize it and enabled additional settings.
    5. Select Client Mode, Desired WiFi network,  Insert password and click Connect.
    
    .. image:: connect-6.png
    
    6. When your STEMlab board is connected  the IP address will be shown on the user interface. This IP address is 
       only for WiFi connection. You can check the connection by inputing a WiFi IP address in the web browser URL 
       field (press enter after inputing). 
       
    .. image:: connect-7.png   

    Now you have WiFi connection established. If you restart STEMlab board it will connect to selected network 
    automatically (if selected network is available). Also you can disconnect LAN connection and your board will be 
    still available over the WiFi network i.e WiFi IP address.
    
    .. note::
    
        WiFi networks are generally not robust and the full performances of the Red Pitaya application can be 
        affected. 
        
Access Point mode
=================

This type of the connection is ideal if there is no LAN or WiFi network. STEMLab board will simply create its own WiFi
network on which users PC/Laptop or Tablet can be connected. Access Point mode is arranged via Network Manager 
application where you give the name to your STEMLab network and  enable it. Since Access Point mode is enabled via 
Network Manager application  this means that first you need to use LAN network, access your STEMLab board and arrange
the Access Point mode. After this there is no need for LAN network and after restarting the STEMLab the settings are
saved.  Notice: Connecting the STEMLab via Access Point mode the additional WiFi dongle is needed. WiFi dongle is 
available [Link to RS or similar].

.. image:: connect-8.png

How to create Access Point network and connect to it is describe below.
    1. Start your STEMlab web user interface (Use connection described **Local Area Network (LAN) connection )**
    2. Open Network Manager application
    3. Input the name and password of the Access Point network to be created
       (Password name should be at least 8 characters long. Do not use special signs.)
    4.  Connect your PC/Laptop/Tablet/Phone to the network created by STEMlab board
    5. Input Access Point network IP address to the web browser URL field and press enter.
    
    .. note::
    
        IP address in Access Point mode is always the same: 192.168.128.1

.. image:: connect-9.png

