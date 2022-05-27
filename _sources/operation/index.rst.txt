*******************************************
Operation
*******************************************

.. meta::
   :description: JMRI Engine Driver Throttle
   :keywords: Engine Driver EngineDriver JMRI manual help operation

.. |br| raw:: html

   <br />

.. sidebar:: On this page

  .. contents::
    :depth: 3

----

Quick Start / Getting Started
-----------------------------


* Confirm that your devices meet the `Prerequisites <../prerequisites/index.html>`_
* **Start your WiThrottle server**

  * For JMRI, Start the `WiThrottle <https://www.jmri.org/help/en/package/jmri/jmrit/withrottle/Protocol.shtml>`_ function of JMRI, located in DecoderPro under Tools, Throttles. It is also highly recommended that you start the `JMRI Web Server function <https://www.jmri.org/help/en/html/web/index.shtml>`_ (Tools, Start JMRI Web Server). 
  * For other devices, turning them on a waiting a minute or two should be sufficient.

    See the `Prerequisites <../prerequisites/index.html>`_ page for more information.

* **On your Android device/phone** 
  
  * Make sure you are connected to same network as the WiThrottle server's network.

  * Start Engine Driver 

    * The first time you run Engine Driver you will need to go through the Setup Wizard to agree to the permissions and select a few key preferences  
   
      See the `Setup Wizard <../configuration/setup_wizard.html>`_ page for more information.

  * Wait for your server's address to show up in 'Discovered Servers'

  * Click on the discovered address

    * If the server does not show up, check that are on the same network as the WiThrottle server.   
    * If the server *never* appears in the discovered list, type in the IP address and Port of the WiThrottle server (Using the values shown on the JMRI WiThrottle window) and press :guilabel:`Connect`. |br|\ Note: this situation is sometimes possible even if you are on the same network. |br|\ |br|\ NOTE: see the `WiFi connection page <./wifi_issues.html>`_ for more assistance on connection issues. |br|\ There is also a "demo" server at **jmri.mstevetodd.com**, port **44444** that you can connect to for testing. |br|\ |br|\ 

  * On the throttle screen, click on the :guilabel:`Select` loco button

  * On the next (Loco Select) screen, either:

    * click on a loco from the Roster or Recent lists
    * or enter the loco address (verify short or long), and press :guilabel:`Acquire`

      You will be returned to the Throttle screen.

      For Consists / multiple units, see the note below.

  * Operate your loco 
  
    * Use the slider, or volume hardware buttons, or optional buttons for speed
    * Use the :guilabel:`Forward` and :guilabel:`Reverse` buttons to control direction

  * Press your phone's Menu button to access screens for Turnout, Route and Power control, as well as adjust settings and set numerous preferences
  * You can also "fling" left or right to jump quickly back and forth between the Throttle, Routes, Turnouts and Web pages (use Preferences to choose) |br|\ |br|\ 

  * To release a single loco (or consist), click :guilabel:`Select` again and click the :guilabel:`Release` button

  * To release all locos, just press the :guilabel:`Back` button and exit the app. |br|\ This will also stop your locos (can be overridden in preferences)

Note:

* To create a consist "on-the-fly", simply select additional locos for the same throttle, then select which way the new loco if facing. Direction and speed will be sent for all. Release will release all for that throttle

----

Detailed Information 
--------------------

Connecting
^^^^^^^^^^^^^^^^

Connecting to the network
""""""""""""""""""""""""""

.. sidebar:: 
  :class: sidebar_no_background

  .. image:: ../_static/images/parts/network1.png
    :scale: 30 %
    :align: right

  |br|

  .. image:: ../_static/images/parts/network2.png
    :scale: 30 %
    :align: right

TBA

* Use Android's Network/Wifi settings to connect to the same network as your WiThrottle server
* With some exceptions, your device's IP Address should be similar to the server's IP address (the first three blocks of numbers will be identical)

  * For your Android device / phone, you can see its address in the Engine Driver menu option ``About``, at the top of the screen
  * For a JMRI server, see the WiThrottle window for its address 
  * For other devices, see the instructions for that device

Also see `WiFi issues <./wifi_issues.html>`_ if you are having difficulties.

|br|

Connecting the WiThrottle server
""""""""""""""""""""""""""""""""""

.. sidebar:: 
  :class: sidebar_no_background

  .. image:: ../_static/images/parts/connecting_ip_address.png
    :scale: 30 %
    :align: right

  |br|

  .. image:: ../_static/images/parts/connecting_discovered_servers.png
    :scale: 30 %
    :align: right

  |br|

  .. image:: ../_static/images/parts/connecting_recent_servers.png
    :scale: 30 %
    :align: right

TBA

* Start Engine Driver |br|\ You will be presented with the Connection Screen
* There are three ways you can select a server to connect to

  - Address and Port
  - Discovered Servers
  - Recent servers


If you only ever connect to one WiThrottle server you can effectively bypass this screen by setting the ``Auto-Connect to WiThrottle Server?`` preference.

Also see `Connection issues <./wifi_issues.html>`_ if you are having difficulties.


----

Selecting / Releasing Locos and Consists/Multiple Units
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TBA

Single loco
""""""""""""""""""""""""""""""""""

TBA

* DCC Address
* Roster
* Recent Locos
* Recent Consists

Also see `Locomotive Icons <#locomotive-icons-in-the-roster>`_ below.

On the fly / In Phone Consists (Multiple Units)
""""""""""""""""""""""""""""""""""""""""""""""""

- direction
- changing order
- removing

----

Running Trains
^^^^^^^^^^^^^^^

TBA

Controlling Speed
""""""""""""""""""""""""""""""""""

TBA

- sliders
- speed buttons
- volume keys
- gamepads

Controlling Direction
""""""""""""""""""""""""""""""""""

TBA

- throttle screen layouts with direction buttons
- throttle screen layouts without direction buttons  (Switching/Shunting)
- gamepads

DCC Functions
""""""""""""""""""""""""""""""""""

TBA

- Common Functions
- Function Labels
- Functions in consists
- gamepads

Virtual Sounds - In Phone Loco Sounds (IPLS)
""""""""""""""""""""""""""""""""""""""""""""

TBA

- steam
- diesel
- custom 
- gamepads

Gamepads  
""""""""""""""""""""""""""""""""""

TBA

See `gamepads <./gamepads.html>`_

Action Bar and Menu
^^^^^^^^^^^^^^^^^^^

TBA

Track Power
""""""""""""""""""""""""""""""""""

TBA

In Phone Loco Sounds (IPLS)
""""""""""""""""""""""""""""""""""

TBA

Power
""""""""""""""""""""""""""""""""""

TBA

Flashlight 
""""""""""""""""""""""""""""""""""

TBA

----

Turnouts / Points
^^^^^^^^^^^^^^^^^

TBA

----

Routes
^^^^^^^^^^^^^^^

TBA

----

Panels and Web Pages
^^^^^^^^^^^^^^^^^^^^^^

TBA

----

Pushing Engine Driver to the Background
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TBA

----

Exiting Engine Driver
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

To exit Engine Driver, you can:

* Press the Android :guilabel:`Back` button once from the main screens (more than once if you are on one of the secondary screens) |br|\ OR
* Menu > Exit

Exiting Engine Driver:

* Disconnects from the WiThrottle server.
* Stops playing all In Phone Loco Sounds (if any were configured).


----

.. toctree::
    :hidden:
    :maxdepth: 1

    interface
    wifi_issues
    gamepads
    esu_mcii
    faq
