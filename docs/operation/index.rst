*******************************************
Operation
*******************************************

.. meta::
   :keywords: operation

.. include:: ../include.rst

.. sidebar::

  .. contents:: On This Page
    :depth: 3


Quick Start / Getting Started
-----------------------------

* Install **Engine Driver** from the `Google Play Store <https://play.google.com/store/apps/details?id=jmri.enginedriver>`_ or by `direct download <../downloads/index.html>`_. 
* Confirm that your devices meet the `Prerequisites <../prerequisites/index.html>`_
* **Start your WiThrottle server**

  * For JMRI, Start the `WiThrottle <https://www.jmri.org/help/en/package/jmri/jmrit/withrottle/Protocol.shtml>`_ function of JMRI, located in DecoderPro under Tools, Throttles. |br|\ It is also highly recommended that you start the `JMRI Web Server function <https://www.jmri.org/help/en/html/web/index.shtml>`_ (Tools, Start JMRI Web Server). 
  * For other devices, turning them on and waiting a minute or two should be sufficient.

    See the `Prerequisites <../prerequisites/index.html>`_ page for more information.

* **On your Android device/phone** 
  
  * Make sure you are connected to same network as the WiThrottle server's network.

  * Start |ED| 

    * The first time you run |ED| you will need to go through the Setup Wizard to agree to the permissions and select a few key preferences  
   
      See the `Setup Wizard <../configuration/setup_wizard.html>`_ page for more information.

  * Wait for your server's address to show up in 'Discovered Servers'

  * Click on the Discovered server

    * If the server does not show up, check that are on the same network as the WiThrottle server.   
    * If the server *never* appears in the discovered list, type in the IP address and Port of the WiThrottle server (Using the values shown on the JMRI WiThrottle window) and press :guilabel:`Connect`. |br|\ Note: this situation is sometimes possible even if you are on the same network. |br|\ |br|\ See the `WiFi connection <./wifi_issues.html>`_ page for more assistance if you have connection issues. |br|\ |br|\ 

  * If needed, turn the track power on with :menuselection:`Menu --> Power` and confirm the button is 'green'  (This is not required by all DCC Command Stations.)
  
  * On the Throttle screen, click on the :guilabel:`Select` loco button

  * On the next (Loco Select) screen, either:

    * Click on a loco from the Roster or Recent lists |br|\ or
    * Enter the loco address (verify short or long), and press :guilabel:`Acquire`

      You will be returned to the Throttle screen.

      For Consists / multiple units, see the note below.

  * Operate your loco 
  
    * Use the slider, or volume hardware buttons, or optional buttons for speed
    * Use the :guilabel:`Forward` and :guilabel:`Reverse` buttons to control direction

  * Press your phone's Menu button to access screens for Turnout, Route and Power control, as well as adjust settings and set numerous preferences
  * You can also 'swipe/fling' left or right to jump quickly back and forth between the Throttle, Routes, Turnouts and Web pages. (Use Preferences to choose which are in the left / right swipe list) |br|\ |br|\ 

  * To release a single loco (or consist), click :guilabel:`Select` again and click the :guilabel:`Release` button

  * To release all locos, just press the :guilabel:`Back` button and exit the app. |br|\ This will also stop your locos (can be overridden in preferences)

Note:

* To create a consist 'on-the-fly', simply select additional locos for the same throttle, then select which way the new loco if facing. Direction and speed will be sent for all. Release will release all for that throttle

Detailed Instructions 
---------------------

Connecting
^^^^^^^^^^^^^^^^

Connecting has two aspects:

* Connecting to the correct WiFi network, which uses Android's build in capabilities (not |EDs|)
* Connecting |ED| to the WiThrottle server

Connecting to the WiFi network
""""""""""""""""""""""""""""""

.. sidebar:: 
  :class: sidebar-no-background

  .. image:: ../_static/images/parts/network1.png
    :scale: 30 %
    :align: right

  |br|

  .. image:: ../_static/images/parts/network2.png
    :scale: 30 %
    :align: right

* Use Android's Network - Wifi settings to connect to the same network as your WiThrottle server
* With some exceptions, your device's IP Address should be similar to the server's IP address (the first three blocks of numbers will be identical)

  * For your Android device / phone, you can see its address in the |EDs| 'About Screen' (:menuselection:`Menu --> About`), at the top of the screen
  * For a JMRI server, see the WiThrottle screen for its address 
  * For other devices, see the instructions for that device

.. note:: 
  :class: note-ed-hidden-title
  
  Also see the `WiFi issues <./wifi_issues.html>`_ page if you are having difficulties.

Connecting the WiThrottle server
""""""""""""""""""""""""""""""""""

.. sidebar:: 
  :class: sidebar-no-background

  .. image:: ../_static/images/parts/connecting_ip_address.png
    :scale: 30 %
    :align: right
    :name: IP Address

  |br|

  .. image:: ../_static/images/parts/connecting_discovered_servers.png
    :scale: 30 %
    :align: right
    :name: Discovered Servers

  |br|

  .. image:: ../_static/images/parts/connecting_recent_servers.png
    :scale: 30 %
    :align: right
    :name: Recent Severs

* Start Engine Driver |br|\ You will be presented with the Connection Screen
* On the Connection Screen there are three ways you can select a WiThrottle server to connect to:

  - IP Address and Port
  - Discovered Servers
  - Recent servers

  **Discover Servers**

  This is the most common way to connect. If the server you want to connect to is in the list, simply click on it and you will be taken to the Throttle screen.

  If the server does not appear in the recent list try one of the other two methods.  
  Your server not appearing in the recent list is not necessarily a problem  See `Connection issues <./wifi_issues.html>`_ for more information.

  **Recent Server List**

  If the server you want to connect to is in the list, simply click on it and you will be taken to the Throttle screen.

  A server being in this list *does not* necessarily mean that you will be able to connect it *now*. It just means that you have successfully connected to it in the past.

  There is also a 'demo' server at **jmri.mstevetodd.com**, port **44444** in this list that you can connect to for testing. (If your device/phone has an internet connection.)

  **IP Address and Port**

  Type in the **IP address** and **Port** of the WiThrottle server and press :guilabel:`Connect`.

  To find your server's IP address and Port:

    * For a JMRI server, see the WiThrottle screen for its address 
    * For other devices, see the instructions for that device


  If you only ever connect to one WiThrottle server you can effectively bypass this screen by setting the ``Auto-Connect to WiThrottle Server?`` preference.

.. note:: 
  :class: note-ed-hidden-title
  
  Also see `Connection issues <./wifi_issues.html>`_ if you are having difficulties.


----

Power on the Layout
^^^^^^^^^^^^^^^^^^^

Some DCC Command Stations need to be directed to turn the track power on before you can use them.  This is not required by all Command Stations so you may need to look at the manufacturers instructions.

There are two ways to turn the power on/of:

* Power Screen - accessed from the menu
* Power Action Bar button - needs to be enable in the preferences
 
The Power Screen can be accessed from the :menuselection:`Menu --> Power`.  This will open the Power Screen where there is a simple button that to turn the power on or off. Use Android's ``Back`` button to return to the Throttle Screen.

If the Power Action Bar button is enable, simply click on it to tur track power on or off.

.. note:: 
  :class: note-ed-hidden-title

  See the `Power section of the User Interface page <./interface.html#power-screen>`_ for more information.
  
  See the `Power Button option in the Preferences page <../configuration/preferences.html#throttle-screen-action-bar-preferences>`_ for more information on enabling the Power Button on the Action bar.

----

Selecting & Releasing Locos
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Selecting and releasing locos and Consists/Multiple Units is done from the Throttle Screen, by clicking on the :guilabel:`Select` button of one of the Throttles on the screen.

(The Throttle screen may have from 1 to 6 throttles on it, depending on the `Throttle Screen Layout preferences <../configuration/preferences.html#throttle-screen-appearance-preferences>`_ you have chosen.)

Selecting a Single loco
"""""""""""""""""""""""

There three ways select a loco:

* By entering a DCC Address
* By selecting from the Roster
* By selecting a Recent Loco

  **DCC Address**

  You can enter the loco's DCC address (verify short or long), and press :guilabel:`Acquire` to select the loco.  You will then be taken back to the Throttle screen with that loco selected.

  **Roster**

  If the loco you want to control to is in the list, simply click on it and you will be taken back to the Throttle screen with that loco selected.

  The Loco you want to control needs to be in the roster of the WiThrottle server.  Not all WiThrottle server support rosters.  Refer to the JMRI documentation or you WiThrottle server device's documentation for creating a roster.

  Also see `Locomotive Icons <#locomotive-icons-in-the-roster>`_ below.

  **Recent Locos**

  **Engine Driver** remembers the last 10 locos that you have selected. (That number can be increased or decreased with ``Maximum Recent Locos`` preference.)

  If the loco you want to control to is in the list, simply click on it and you will be taken back to the Throttle screen with that loco selected.

On the fly / In Phone Consists (Multiple Units)
""""""""""""""""""""""""""""""""""""""""""""""""

There four ways create a Consist / Multiple Unit train:

*  **Selecting additional locos, one loco 'at a time' (as above)**

      * DCC Address
      * Roster
      * Recent Locos |br|\ |br|\ or

* By using the **Recent Consists** list |br|\ |br|\ 

  **One at a time**

  Adding additional locos the Consist / Multiple Unit train is identical to the process of selecting a single loco.  Simply click on the :guilabel:`Select` button, which will be showing the name or address of any locos already selected.

  There is no real limit to the number of locos that can be added to a Consist / Multiple Unit.

  After selecting each additional loco, you are presented with a screen that allows you to:

  - Change the facing of each loco (except the front loco)
  - Change the order of the locos in the Consist / Multiple Unit
  - Remove locos in the Consist / Multiple Unit

  **Recent Consists**

  Selecting a Consist / Multiple Unit in the Recent Consists list will automatically add all the remembered locos, including their facing.

  Note:

  * the order of the locos in the consist can be important.  By default, lights and sound functions are only sent to the first loco.  This can be overridden in the preferences.

----

Running Trains
^^^^^^^^^^^^^^^

Once you have selected a loco or consist / multiple unit for a throttle the names or addresses of the locos will be shown in the :guilabel:`Select` button of the throttle.

From here you can:

- Control the speed and direction of you loco or consist / multiple unit
- Activate the DCC functions for you loco or consist / multiple unit
- Activate the Virtual Sounds 
- Add or release locos.  
  
  .. note:: 
    :class: note-ed-hidden-title

    See `Selecting / Releasing Locos and Consists/Multiple Units <#selecting-releasing-locos-and-consists-multiple-units>`_

Controlling Speed
""""""""""""""""""""""""""""""""""

|todo|

There are eight ways you can control the speed of of your loco or consist /multiple unit train:

- Sliders (if available in the Throttle layout)
- Speed buttons (if enabled)
- Stop button
- Volume keys
- All Stop - Action Bar button (if enabled)
- Pause button (if enabled)
- Limit Speed button (if Enabled)
- Gamepad keys (if connected)

  **Sliders**

  |todo|

  **Speed buttons**

  |todo|

  ``++`` and ``--`` buttons

  **Stop button**

  |todo|

  **Volume Keys**

  |todo|

  Hardware ``Volume Up`` and ``Volume Down`` Android buttons

  **All Stop - Action Bar button**

  |todo|

  **Pause button**

  |todo|

  **Limit Speed button**

  |todo|

  **Gamepad keys**

  |todo|


Controlling Direction
""""""""""""""""""""""""""""""""""

|todo|

There are three ways you can control the direction of your loco or consist /multiple unit train:

- throttle screen layouts with direction buttons
- throttle screen layouts without direction buttons  (Switching/Shunting)
- gamepad keys

  **Direction Buttons**

  ``Forward`` and ``Reverse``

  * These can be re-labeled
  * These can be swapped
  * Not available on the Switching/Shunting Throttle Screen layouts

  **Switching/Shunting Throttle Screen layouts**

  |todo|

  **Gamepad keys**

  |todo|


DCC Functions
""""""""""""""""""""""""""""""""""

|todo|

There are two ways you can activate the DCC Functions of your loco or consist /multiple unit train:

- Function buttons
- Gamepads keys (if connected)

The actions of the DCC functions will be impacted depending on the settings and preferences you have selected:

* Common Functions
* Function Labels
* Functions in consists

  **Function Buttons**

  |todo|

  **Gamepad Keys**

  |todo|

  **Common Functions**

  |todo|

  **Function Labels**

  |todo|

  **Functions in consists**

  |todo|

Virtual Sounds - In Phone Loco Sounds (IPLS)
""""""""""""""""""""""""""""""""""""""""""""

|todo|

How to enable, change, mute.

* steam
* diesel
* custom 
* gamepads

See `In Phone Loco Sounds (IPLS) <../configuration/ipls.html>`_ for more information.

Gamepads  
""""""""""""""""""""""""""""""""""

|todo|

.. note:: 
  :class: note-ed-hidden-title

  See `gamepads <./gamepads.html>`_ for more information.

Action Bar and Menu
^^^^^^^^^^^^^^^^^^^

|todo|

Men=number
* common
* screen specific
  
Action Bar
* common
* screen specific

Track Power
""""""""""""""""""""""""""""""""""

|todo|

* Menu item
* Action Bar button

In Phone Loco Sounds (IPLS)
""""""""""""""""""""""""""""""""""

|todo|

* Preferences
* Action Bar Button

----

Turnouts / Points
^^^^^^^^^^^^^^^^^

|todo|

* Address
* From the WiThrottle server

----

Routes
^^^^^^^^^^^^^^^

|todo|

* From the WiThrottle server

----

Panels and Web Pages
^^^^^^^^^^^^^^^^^^^^^^

|todo|

* Throttle Web View VS Web Screen
* Default page
  * Web View
  * Web Screen


----

Exiting Engine Driver
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

To exit **Engine Driver**, you can:

* Press the Android :guilabel:`Back` button once from the main screens (more than once if you are on one of the secondary screens) |br|\ OR
* :menuselection:`Menu --> Exit`

Exiting **Engine Driver**:

* Disconnects from the WiThrottle server.
* Stops playing all In Phone Loco Sounds (if any were configured).


Odds and Ends
-------------

Pushing Engine Driver to the Background
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

* Disable Alert

----

Disconnections
^^^^^^^^^^^^^^

|todo|

* Disable haptic Alert



.. toctree::
    :hidden:
    :maxdepth: 1

    interface
    wifi_issues
    gamepads
    esu_mcii
    advanced
    faq
