*******************************************
Operation
*******************************************

.. meta::
   :description: JMRI Engine Driver Throttle
   :keywords: Engine Driver EngineDriver JMRI manual help operation

.. |br| raw:: html

   <br />

.. contents::

----

-------------------------------
Quick Start / Basic Information
-------------------------------

* Start your wiThrottle server

  * For JMRI, Start the `WiThrottle <https://www.jmri.org/help/en/package/jmri/jmrit/withrottle/Protocol.shtml>`_ function of JMRI, located in DecoderPro under Tools, Throttles. It is also highly recommended that you start the `JMRI Web Server function <https://www.jmri.org/help/en/html/web/index.shtml>`_ (Tools, Start JMRI Web Server). 
  * For other devices, turning them on a waiting a minute or two should be sufficient.

    See the `Prerequisites <../prerequisites/index.html>`_ page for more information.

* On your Android device, make sure you are connected to same network as the WiThrottle server's network.
* Start the Engine Driver app 

  * The first time you run Engine Driver you will need to go through the Setup Wizard to enable the permissions and select a few significant preferences.  
   
    See the `Setup Wizard <../configuration/setup_wizard.html>`_ page for more information.

* Wait for your server's address to show up in "Discovered Servers".
* Click on the discovered address, 

  * If the server does not show up, check that are on the same network as the WiThrottle server.   
  * If the server *never* appears in the discovered list, type in the IP address and Port of the WiThrottle server (Using the values shown on the JMRI WiThrottle window) and press ``Connect``. |br|\ Note: this situation is sometimes possible even if you are on the same network. |br|\ |br|\ NOTE: see the `WiFi connection page <./wifi_issues.html>`_ for more assistance on connection issues. |br|\ There is also a "demo" server at **jmri.mstevetodd.com**, port **44444** that you can connect to for testing. |br|\ |br|\ 

* On the throttle screen, click on the ``Select`` loco button.
* On the next (Loco Select) screen, either:

  * click on a loco from the Roster or Recent lists, 
  * or enter the loco address (verify short or long), and press ``Acquire``. 

    You will be returned to the Throttle screen.

    For Consists / multiple units, see the note below

* Operate your loco 
  
  * Use the slider, or volume hardware buttons, or optional buttons for speed, 
  * Use the ``Forward`` and ``Reverse`` buttons to control direction.

* Press your phone's Menu button to access screens for Turnout, Route and Power control, as well as adjust settings and set numerous preferences.
* You can also "fling" left or right to jump quickly back and forth between the Throttle, Routes, Turnouts and Web pages (use Preferences to choose) |br|\ |br|\ 
* To release a single loco (or consist), click ``Select`` again and click the ``Release`` button.
* To release all locos, just press the ``Back`` button and exit the app. |br|\ This will also stop your locos (can be overridden in preferences). 

Note:

* To create a consist "on-the-fly", simply select additional locos for the same throttle, then select which way the new loco if facing. Direction and speed will be sent for all. Release will release all for that throttle.

----

--------------------
Detailed Information 
--------------------

^^^^^^^^^^^^^^^^
Connecting
^^^^^^^^^^^^^^^^

TBA

Connecting to the network

Connecting the wiThrottle server

Auto connecting

`Connection issues <./wifi_issues.html>`_

^^^^^^^^^^^^^^^^^^^^^^^^^^^
Selecting / Releasing Locos
^^^^^^^^^^^^^^^^^^^^^^^^^^^

TBA

Single loco

On the fly / In Phone Consists (Multiple Units)

- direction
- changing order
- removing

Also see `Locomotive Icons <#locomotive-icons-in-the-roster>`_ below.

^^^^^^^^^^^^^^^
Running Trains
^^^^^^^^^^^^^^^

TBA

Sliders

Direction

Functions

- Common Functions
- Function Labels
- Functions in consists

Volume Keys

IPLS

Gamepads  See `gamepads <./gamepads.html>`_


^^^^^^^^^^^^^^^^^
Turnouts / Points
^^^^^^^^^^^^^^^^^

TBA

^^^^^^^^^^^^^^^
Routes
^^^^^^^^^^^^^^^

TBA

^^^^^^^^^^^^^^^^^^^^^^
Panels and Web Pages
^^^^^^^^^^^^^^^^^^^^^^

TBA

^^^^^^^^^^^^^^^
Other stuff TBA
^^^^^^^^^^^^^^^

TBA

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Locomotive Icons in the Roster
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The **Roster List**, and **Recent Locos List** on the Select Loco screen will automatically show icons for your locos only if:

* The **Web Server** (not just the wiThrottle server) is running on the JMRI server
* The loco itself has an icon added for it in the JMRI roster |br|\ OR
* A locally cached or manually chosen image is avilable for the loco (see below)
* For the **Recent Locos list**, the loco was originally selected from a roster. (i.e. Not entered as a DCC Address)


**For wiThrottle servers that do support a roster but don't support Locomotive Icons**

There are three ways to load & store your Locomotive Icon Image in Engine Driver 2.32.142 and above.

1. **Automatically from your existing JMRI Roster & Media**
  
  * Start JMRI and capture and load your images into JMRI Roster & Media panel as normal
  * Start the WiThrottle server.
  * Start the Web Server.
  * Connect Engine Driver to JMRI WiThrottle Server Discovered Server 'My JMRI Railroad' or type in the IP address : Port# 
  * Click ``Select`` and load your Locos then ``Release`` and repeat until you've loaded all the locomotives you require with Icons into a throttle. 
 
  These Loco Icons will automatically be saved/cached on the Android device/phone in a new '/Android/data/jmri.enginedriver/files/recent_engine_list/**recent_engine_list**' folder for you.

  Requirements for this to work:

    * Have identical names (from JMRI Roster ID to DCC++EX EXRAIL Roster ID)  example ID;    "PE 1225"
    * Have image icons displayed for the locomotives

2. **Manually entered directly into your Android Engine Driver folder**
  
  * Capture then rename the image exactly like the Roster ID name in JMRI & EXRAIL and save as a .PNG file
  * Then place the engine Image into your Android device/phone in the |br|\ '/Android/data/jmri.enginedriver/files/recent_engine_list' folder |br|\ example image name;  PE 1225.png

  Note: certain characters are not allowed in file names so need to be substituted with "_" (underscore) if you have used them in your roster name. They are:

  * / (forward slash) 
  * " (double quote)
  * \\ (backslash)
  * \* (asterix)
  * ? (question mark)
  * < (less than)
  * > (greater than)

3. **Select an image on the phone/device (which can be taken on the phone's camera)**

 * In the **Roster List** on the Select Loco screen

   * Long press on the loco
   * press the ``New Image`` button, which will lauch the Android system's default app for choosing images 
   * find and select an image
   * click ``Save`` |br|\ |br|\ You can replace an image with the ``New Image`` button or remove it with the ``Remove`` button

**General Notes on the Local Loco Icons:**

* If the loco already has an image in the JMRI Roster (of the currently connected wiThrottle server), you won't be able to choose a local image.
* If you later add an image in the JMRI Roster for the loco (or later connect to a wiThrottle server that has an image), it will automatically overwrite the local image with the one on the server.
* In the Recent Locos list you *can not* add images to locos entered by a DCC address. (i.e. not from the roster)  

----

---------------------
Additional Infomation
---------------------


.. toctree::
    :maxdepth: 1

    wifi_issues
    gamepads
    faq
