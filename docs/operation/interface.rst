*******************************************
User Interface
*******************************************

.. meta::
   :description: JMRI Engine Driver Throttle
   :keywords: Engine Driver EngineDriver JMRI manual help interface

.. |br| raw:: html

   <br />

.. sidebar:: On this page
  
  .. contents::
     :depth: 3
    
----

Main Screens
-------------

There are four main screens:

* Connection Screen
* Throttle Screen
* Turnouts/Points Screen
* Routes Screen

Connection Screen
^^^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/connect.png
   :align: right

This screen is the first screen you normally see when starting Engine Driver. 

It allows you choose which WiThrottle Server to connect, which you must do to control your trains.

TODO

- Address and Port
- Discovered Servers
- Recent servers

Once you select a server the 'Throttle Screen' will be automatically displayed.

If you only ever connect to one WiThrottle server you can effectively bypass this screen by setting the ``Auto-Connect to WiThrottle Server?`` preference.

Throttle Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/throttle_vertical_outline.png
   :scale: 8 %
   :align: right

This screen allows you to control:

* The speed and direction of your trains
* Initiate special locomotive decoder functions like the light, bell, horn 
* Accessing the Action Bar buttons and Menu features. 
  |br|\ These include:

  * All Stop
  * Track Power
  * Flashlight
  * Throttle Web View
  * Throttle Layout Switching
  * Layout Switching
  * In Phone Loco Sound

      The optionally configured buttons are configured via the Preferences > Throttle Screen Status Row Preferences.

Throttle Area
""""""""""""""""""""""""""""""""""""

The Throttle may configured to be simple buttons that allow you to increase or decrease the locomotive's speed in pre-defined steps.  Alternatively, the Throttle may be configured as a slider.  A slider can be configured as one-directional (0-100) or bi-directional (-100 - 0 - +100).  Bi-directional sliders are useful for when you are switching/shunting. i.e. moving backwards and forwards a lot.

Direction Buttons Area
""""""""""""""""""""""""""""""""""""

TODO

Function Buttons Scroll Area
""""""""""""""""""""""""""""""""""""

TODO

Function Buttons are displayed here.  If there are too many to display in the screen area allocated, then the area becomes scrollable (but without scroll bars) so that they can all be viewed and pressed as needed.

Web View Area
""""""""""""""""""""""""""""""""""""

Your JMRI Layout panel is displayed here if you have configured it to do so in Preferences. TODO

----

Turnouts/Points Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

Accessed from the menu on the any of the main screens as ``Turnouts`` or ``Points`` or by swiping right from the Throttle Screen if enabled in the Left with the ``Swipe through Turnouts?`` or ``Swipe through Points?`` preference.

This screen allows you to display all Turnouts/Points that have been defined in JMRI.

Turnouts/Points can be changed from Closed to Thrown and vice versa be pressing on either the “Closed” or “Thrown” buttons

Routes Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

Accessed from the menu on the any of the main screens as ``Routes`` or by swiping left from the Throttle Screen if enabled in the Left with the ``Swipe through Routes?`` preference.

This screen allows you to display all Routes that have been defined in JMRI or DCC++EX.

Web Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

Accessed from the menu on the any of the main screens as ``Turnouts`` or ``Points`` or by swiping left or right twice from the Throttle Screen if enabled in the Left with the ``Swipe through Web?`` preference.
It can also be accessed, if the ``Screen orientation`` preference is set to ``Auto Web``, by rotating the Android Device/Phone.

This screen displays a web browser interface that lets you view any web page. Normally this will be a web page on your JMRI server. 

From the JMRI web server you can view and interact with additional features of JMRI.  The menu at the top right of the web panel screen allows you to further display:

* Rosters
* Operations
* Trains
* Tables
* Turnouts/Points |br|\ A list of turnouts is displayed in tabular form.  Turnouts can be changed from Closed to Thrown and vice versa by pressing on the “State” column's “closed” or “thrown” words.
* Sensors
* Routes
* Reporters
* Memories
* Blocks
* Layout Blocks
* Lights
* Signal Masts
* Signal Heads
* Locations
* Cars
* Engines
* ID Tags

This can be used for:

* A webThrottle screen
* Your JMRI layout panel(s)
* Any URL in a full screen.  This is in addition to being able to display your JMRI layout panel in a small section of the main Throttle Screen.

Tap on any of the Open Windows to expand its view.  You can then resize the panel by pinching and zooming.  It is sometimes useful to rotate your device to landscape mode, so as to better view your layout.


----

Secondary / Support Screens
-------------------------------

TODO

Intro/Setup Wizard Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO


Loco Select Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

Consist Edit Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

Consist Lights Edit Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO


Power Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Accessed from the menu on the Throttle Screen as ``Power`` or from the Status Bar if enabled with the ``Layout Power button?`` preference.

This screen allows you to toggle the state of track power to your layout.

* When the button is displayed in green, it indicates that track power is “On”.
* When the button is displayed in red, it indicates that track power is “Off”.
* Pressing a green button will cause the button to be changed to red and the track power will be turned “Off”.
* Pressing a red button will cause the button to be changed to green and the track power will be turned “On”.

Preferences Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Accessed from the menu on the any of the main screens as ``Preferences``.

This screen allows you to configure Engine Driver for how you want it to operate for you.

See `Preferences <../configuration/preferences.html>`_ for details on the preferences that can be set.

In Phone Loco Sounds Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

Accessed from the menu on the Throttle Screen as ``Loco Sounds`` or from the Status Bar if enabled with the ``In phone sounds button`` preference.

Function Defaults Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

Accessed from the menu on the Throttle Screen as ``Function Defaults``.

Gamepad Test Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

Accessed from the menu on the Throttle Screen as ``Gamepads`` -> ``Gamepad Test X``. (where 'X' is the number of the gamepad.)

View Log Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO

Accessed from the menu on the any of the main screens as ``View Log``.

This screen allows you to view the internal Engine Driver log of events.
This is sometimes useful for analysing problems.

The option to ``Start recording to file`` creates a user-accessible file that can be sent to the Engine Driver app developers or the Groupio help group to assist you in resolving a problem.
The file will be located on your mobile phone at:
Internal storage .../engine_driver
and will be named something like:
logcat9999999999999.txt

About Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This screen displays 

* Information about Engine Driver, 
* Information about the WiThrottle Server it is currently connected to (if any), and 
* A page of basic information about Engine Driver

TODO 

----

Common Elements
---------------

Action Bar
^^^^^^^^^^

The Action Bar appears at the top of all screen. It will show different information and different buttons depending on a) the particular screen and b) preferences you have set.

The Action Bar can display:

* The app name (“Engine Driver”)
* Optionally configured information:

  * Fast Clock

* Optionally configured buttons:

  * All Stop
  * Emergency Stop
  * Track Power
  * Flashlight
  * Throttle Web View
  * Throttle Layout Switching
  * In Phone Sound

* The Overflow Menu, which is normally three dots (⁞) or three bars (≡).   (Main Screens only)

The optionally configured items are configured via the corresponding preferences in the ``Throttle Screen Action Bar Preferences`` preference group.


Overflow Menu
^^^^^^^^^^^^^

The Overflow Menu (or simply 'Menu') appears in the Action Bar at the top of most of the main screens. It will show different options depending on a) the particular screen, b) preferences you have set and c) the state of certain elements in the app.

The Overflow Menu can display

* Throttle
* Turnouts/Points
* Routes
* Web
* PowerPreferences
* Function Defaults
* Gamepads

  * Gamepad Test 1
  * Gamepad Test ...

* Loco Sounds
* View Log
* Exit
* About