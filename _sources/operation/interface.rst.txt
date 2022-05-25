*******************************************
Interface
*******************************************

.. meta::
   :description: JMRI Engine Driver Throttle
   :keywords: Engine Driver EngineDriver JMRI manual help interface

.. |br| raw:: html

   <br />

.. contents::
    
----

-------------
Main Screens
-------------

TBA

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Connection Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This screen allows you to 

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Throttle Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This screen allows you to control:
The direction of your trains
The speed of your trains
Initiating special locomotive decoder functions like:
Turning the light on or off
Ringing the bell
Tooting the whistle/horn
Toolbar/Status Row/Action Area
TODO Resolve what this area is called and standardise in Help AND the Engine Driver app TODO
The Toolbar Area displays:
The app name (“Engine Driver”)
Various optionally configured buttons:
Emergency Stop
Track Power
Flashlight
Fast Clock
Throttle Web View
Layout Switching
In Phone Sound
Hamburger Menu
The “optionally configured buttons” are configured via the Preferences > Throttle Screen Status Row Preferences.
Throttle Area
The Throttle may configured to be simple buttons that allow you to increase or decrease the locomotive’s speed in pre-defined steps.  Alternatively, the Throttle may be configured as a slider.  A slider can be configured as one-directional or bi-directional.  Bi-directional sliders are useful for when you are shunting backwards and forwards a lot.
Direction Buttons Area

Function Buttons Scroll Area
Function Buttons are displayed here.  If there are too many to display in the screen area allocated, then the area becomes scrollable (but without scroll bars) so that they can all be viewed and pressed as needed.
Web View Area
Your JMRI Layout panel is displayed here if you have configured it to do so in Preferences. TODO

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Turnouts/Points Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This screen allows you to display all Points that have been defined in JMRI.
Points can be changed from Closed to Thrown and vice versa be pressing on either the “Closed” or “Thrown” buttons

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Routes Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This screen allows you to display all Routes that have been defined in JMRI.

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Web Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This screen displays a separate Engine Driver screen that displays a web brower interface that lets you view any web page. Normally this will be a web page on your JMRI server. 

From the JMRI web serer you can view an interact with.  The hamburger menu at the top right of the web panel screen allows you to further display:

* Rosters
* Operations
* Trains
* Tables
* Turnouts / Points |br|\ A list of turnouts is displayed in tabular form.  Turnouts can be changed from Closed to Thrown and vice versa by pressing on the “State” column's “closed” or “thrown” words.
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

-------------------------------
Secondary / Support Screens
-------------------------------

TBA

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Intro/Setup Wizard Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This screen allows you to 



^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Power Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This screen allows you to toggle the state of track power to your layout.

* When the button is displayed in green, it indicates that track power is “On”.
* When the button is displayed in red, it indicates that track power is “Off”.
* Pressing a green button will cause the button to be changed to red and the track power will be turned “Off”.
* Pressing a red button will cause the button to be changed to green and the track power will be turned “On”.

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Preferences Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This screen allows you to configure the Engine Driver app for how you want it to operate for you.

+-----------------------------------+---------+---------+---------------------------+
|Format/Capability                  |Web View |Function |Throttle Control           |
|                                   |         |Buttons  |                           |
+===================================+=========+=========+===========================+
|Horizontal (1-3)                   |    ✓    |    ✓    |0-100 + Direction Buttons  |
+-----------------------------------+---------+---------+---------------------------+
|Vertical (2)                       |    ✓    |    ✓    |0-100 + Direction Buttons  |
+-----------------------------------+---------+---------+---------------------------+
|Big Buttons - Left (1)             |    🗴    |    ✓    |0-100 + Direction Buttons  |
+-----------------------------------+---------+---------+---------------------------+
|Big Buttons - Right (1)            |    🗴    |    ✓    |0-100 + Direction Buttons  |
+-----------------------------------+---------+---------+---------------------------+
|Vertical - Left (1)                |    ✓    |    ✓    |0-100 + Direction Buttons  |
+-----------------------------------+---------+---------+---------------------------+
|Vertical - Right (1)               |    ✓    |    ✓    |0-100 + Direction Buttons  |
+-----------------------------------+---------+---------+---------------------------+
|Vertical Shunting (2) |br|         |    ✓    |    ✓    | \-100 - 0 - +100          |
|Vertical Switching (2)             |         |         |                           |
+-----------------------------------+---------+---------+---------------------------+
|Vertical Shunting - Left (1) |br|  |    ✓    |    ✓    | \-100 - 0 - +100          |
|Vertical Switching - Left (1)      |         |         |                           |
+-----------------------------------+---------+---------+---------------------------+
|Vertical Shunting - Right (1) |br| |    ✓    |    ✓    | \-100 - 0 - +100          |
|Vertical Switching - Right (1)     |         |         |                           |
+-----------------------------------+---------+---------+---------------------------+
|Horizontal Shunting (1-3) |br|     |    ✓    |    ✓    | \-100 - 0 - +100          |
|Horizontal Switching  (1-3)        |         |         |                           |
+-----------------------------------+---------+---------+---------------------------+
|Simple (Tablet Recommended) (1-6)  |    🗴    |see note |0-100 + Direction Buttons  |
+-----------------------------------+---------+---------+---------------------------+

Notes:

* The number is brackets after the Throttle Screen Layout name is the maximum number of throttles that the layout can support.
* The 'Simple' Throttle Screen Layout is designed to allow for up to 6 throttles simultaneously.  |br|\ It is recommended that this only be used on a tablet device, because of the screen real estate demands that 6 throttles requires. |br|\ When this Throttle Screen Layout is selected, the 'Number of Throttles' preferences options is activated.  You can then use this to restrict the number of throttles being displayed on the 'Simple' Throttle Screen Layout.  |br|\ Also the “Functions Area Size” preferences options is activated.  You can then use this to control how many Function Buttons are displayed with each throttle.  By defult, not Functionbuttons will be shown. |br|\ If you have selected In Phone Loco Sounds, then you will want to set this to 4 (for Mute, Light, Bell and Whistle/Horn).

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
In Phone Loco Sounds Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Function Defaults Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Gamepad Test Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
View Log Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This screen allows you to view the internal Engine Driver app log of events.
This is sometimes useful for analysing problems.

The option to ``Start recording to file`` creates a user-accessible file that can be sent to the Engine Driver app developers or the Groupio help group to assist you in resolving a problem.
The file will be located on your mobile phone at:
Internal storage .../engine_driver
and will be named something like:
logcat9999999999999.txt

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
About Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This screen displays TODO 
