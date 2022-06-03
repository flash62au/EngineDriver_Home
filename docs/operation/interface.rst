*******************************************
User Interface
*******************************************

.. meta::
   :keywords: user interface ui

.. include:: ../include.rst

.. sidebar::

  .. contents:: On This Page
     :local:
     :depth: 3

----

The user interface for |ED| is described and explained in these pages as 'screens'.  There are several 'Main Screens' which you will routinely interact with and and larger number of 'Secondary / Support Screens' that will interact with infrequently. 

There are also some settings that impact all of the screens which described towards the end of this page:

* Theme
* Localisation 


Main Screens
-------------

There are four main screens:

* Connection Screen
* Throttle Screen
* Turnouts/Points Screen
* Routes Screen

----

Connection Screen
^^^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/connect.png
   :align: right

This screen is the first screen you normally see when starting |ED|\ . 

It allows you choose which WiThrottle Server to connect, which you must do to control your trains.

|todo|

* Address and Port
* Discovered Servers
* Recent servers

Once you select a server the 'Throttle Screen' will be automatically displayed.

If you only ever connect to one WiThrottle server you can effectively bypass this screen by setting the ``Auto-Connect to WiThrottle Server?`` preference.

----

Throttle Screen
^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/throttle_vertical_outline.png
   :scale: 8 %
   :align: right

The *Throttle Screen* has two distinct areas:

* The Action Bar
* One or more Throttle Areas

There are also some settings that impact the whole Throttle Screen which described towards the end of this section:

* Background
* Immersive Mode (Full Screen)
* Swipe Up / Down
* Accelerometer (Shake)  
 
The *Throttle Screen* allows you to control:

- Access common functions from the Action Bar and Menu
- Control one or more locos

The *Throttle Screen* contains between 1 and 6 Throttle areas depending on the Throttle layout chosen and the number of throttles for that layout (only some allow this to be changed).  


Throttle Area
""""""""""""""""""""""""""""""""""""

Each Throttle on the Throttle Screen will display different information and buttons depending on the ``Throttle Screen Layout`` chosen: :menuselection:`Menu --> Preferences --> Throttle Screen Appearance Preferences --> Throttle Screen Layout`

Each *Throttle Area* allows you to:

* Select and release locos 
* Control the speed and direction of your trains
* Activate DCC decoder functions like the light, bell, horn 
* Activate Virtual (IPLS) Sounds (bell, horn, short horn) (if enabled)

   **Loco Select Button**

   The loco ``Select`` in the Throttle Area allows to select or release locos for that particular Throttle.  Click on the button and you will be taken to the Select Loco screen.

   Once you have selected a loco, the label on the button change to the DCC Address(s) or the Roster name(s) of the Loco depending on how you select the loco in the Loco Select Screen, and if you have the set the ``Loco Address instead of Name?``: preference :menuselection:`Menu --> Preferences --> Throttle Screen Appearance Preferences --> Loco Address instead of Name?`.

   When the button is displaying DCC Address(s) or the Roster name(s), click on the button again and you will be taken to the Select Loco screen where you can de-select the loco(s), select additional locos to make a consist / multiple unit train, edit the locos in the consist, or edit the lights of the locos in the consist / multiple unit.

   .. note:: 
      :class: note-ed-hidden-title

      See the `Operation <../operation/index.html#selecting-releasing-locos>`_ page for more information.

   **Speed indicator**

   |todo|
   
   * Speed

     * Percent 0 - 100%
     * Auto Speed steps
     * 8 steps
     * 10 steps
     * 14 steps
     * 28 steps
     * 128 steps

   * Direction
   * Volume indicator
   * Gamepad Indicator

   Touch a Speed Indicator to set which Throttle the Hardware Volume buttons control.

   .. note:: 
      :class: note-ed-hidden-title

      See the Throttle Control Preferences section of the `Preferences <../configuration/preferences.html#throttle-control-preferences>`_ page for a detailed explanation of the ``Speed Untits`` options.

   **Speed Slider Area**

   TODO

   The Throttle areas can be configured with a slider.  Dragging you finger along the slider will increase or decrease the speed of the loco(s) selected for the that Throttle. Pressing and holding your finger at one spot on the slider will cause |ED| to slowly increase or decrease the speed of the loco(s) selected for the that Throttle till it gets to that point.
   
   Depending on the ``Throttle Screen Layout`` chosen all sliders on the Throttle Screen will be either:
   
   * one-directional (0% - 100%) |br|\ or 
   * bi-directional (-100% - 0 - +100%) 


   Bi-directional sliders are useful for when you are switching/shunting. i.e. moving backwards and forwards a lot.

   **Speed Buttons**

   |todo|

   The Throttle may configured have simple buttons that allow you to increase or decrease the locomotive's speed in pre-defined steps.  

   **Direction Buttons Area**

   |todo|

   **Function Buttons Scroll Area**

   |todo|

   Function Buttons are displayed here.  If there are too many to display in the screen area allocated, then the area becomes scrollable (but without scroll bars) so that they can all be viewed and pressed as needed.

   **Web View Area**

   Your JMRI Layout panel can be displayed here if you have configured it to do so in Preferences. 
   
   TODO

Action Bar (Throttle Screen)
""""""""""""""""""""""""""""

While common across all the screens, the Action bar and menus has some options that are only available from the Throttle Screen. |br|\ These include:

  * Flashlight (if enabled)
  * Throttle Web View (if enabled)
  * Throttle Layout Switching (if enabled)
  * In Phone Loco Sound (if enabled)

Common options include:

  * Emergency Stop (if enabled)
  * Track Power (if enabled)

      The optional buttons are enabled via the :menuselection:`Menu --> Preferences --> Throttle Screen Status Row Preferences`.


|todo|

Background
""""""""""

|todo|

Immersive Mode (Full Screen)
""""""""""""""""""""""""""""

|todo|

Swipe Up / Down
"""""""""""""""

Accelerometer (Shake)  
"""""""""""""""""""""

|todo|

----

Turnouts/Points Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

Accessed from any of the main screens by the :menuselection:`Menu --> Turnouts`` or :menuselection:`Menu --> Points` or by swiping right from the Throttle Screen if enabled in the Left with the ``Swipe through Turnouts?`` or ``Swipe through Points?`` preference: :menuselection:`Menu --> Preferences --> Left/Right Swipe Preferences --> Swipe through Turnouts/Points`

This screen allows you to display all Turnouts/Points that have been defined in JMRI.

Turnouts/Points can be changed from Closed to Thrown and vice versa be pressing on either the “Closed” or “Thrown” buttons

----

Routes Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

Accessed from any of the main screens by the menu :menuselection:`Menu --> Routes` or by swiping left from the Throttle Screen if enabled in the Left with the ``Swipe through Routes?`` preference: :menuselection:`Menu --> Preferences --> Left/Right Swipe Preferences --> Swipe through Routes`

This screen allows you to display all Routes that have been defined in JMRI or DCC++EX.

----

Web Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

Accessed from any of the main screens by the menu :menuselection:`Menu --> Web` or by swiping left or right twice from the Throttle Screen if enabled in the Left with the ``Swipe through Web?`` preference: :menuselection:`Menu --> Preferences --> Left/Right Swipe Preferences --> Swipe through Web`
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

Secondary / Support Screens
-------------------------------

|todo|

----

Intro/Setup Wizard Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

----

Loco Select Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

----

Consist Edit Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

----

Consist Lights Edit Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

----

Power Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Accessed from any of the main screen via : :menuselection:`Menu --> Preferences --> Left/Right Swipe Preferences --> Power` or from the Action Bar if enabled with the ``Layout Power button?`` preference: :menuselection:`Menu --> Preferences --> Throttle Screen Action Bar Preferences --> Layout Power button?`.

This screen allows you to toggle the state of track power to your layout.

* When the button is **Green**, it indicates that track power is 'On'.
* When the button is **Red**, it indicates that track power is 'Off'.
* Pressing a **Green** button will cause the button to be changed to **Red** and the track power will be turned 'Off'.
* Pressing a **Red** button will cause the button to be changed to **Green** and the track power will be turned 'On'.

----

Preferences Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Accessed from any of the main screens via :menuselection:`Menu --> Preferences`.

This screen allows you to personalise  **Engine Driver** for how you want it to use it.

.. note:: 
   :class: note-ed-hidden-title

   See the `Preferences page <../configuration/preferences.html>`_ for details on the preferences that can be set.

----

In Phone Loco Sounds Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

Accessed from Throttle Screen by the :menuselection:`Menu --> Loco Sounds` or from the Status Bar if enabled with the ``In phone sounds button`` preference.

----

Function Defaults Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

Accessed from the menu on the Throttle Screen as ``Function Defaults``.

----

Gamepad Test Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

Accessed from the Throttle Screen via the :menuselection:`Menu --> Gamepads -> Gamepad Test X`. (where 'X' is the number of the gamepad.)

----

View Log Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

Accessed from any of the main screens via :menuselection:`Menu --> View Log`.

This screen allows you to view the internal Engine Driver log of events.
This is sometimes useful for analysing problems.

The option to ``Start recording to file`` creates a user-accessible file that can be sent to the **Engine Driver** app developers or the `Groups.io <https://groups.io/g/jmriusers/topics>`_` help group to assist you in resolving a problem.
The file will be located on your mobile phone at:
Internal storage ``/Android/data/jmri.enginedriver/files`` |br|\ and will be named something like: ``logcat9999999999999.txt``

----

About Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This screen displays 

* Information about **Engine Driver** 
* Information about the WiThrottle Server it is currently connected to (if any)
* A page of basic information about **Engine Driver**

|todo| 


Reconnecting Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This screen displays 

|todo| 


Common Elements and Features
----------------------------

|todo|

----

Theme
^^^^^

|todo|

* Default
* High Contrast
* Outline
* Dark
* Colourful

Localisation
^^^^^^^^^^^^

|todo|

* Use Phone's global setting
* English (US)  - Engine Driver's default
* English (UK)
* English (AUS)
* English (NZ)
* Italian
* Portuguese
* German
* Spanish
* Catalan
* French
* Czech

.. note:: 
   :class: note-ed-hidden-title

   See `Localisation on the Preferences page <../configuration/preferences.html#Localisation>`_ for more information.

Action Bar
^^^^^^^^^^

.. image:: ../_static/images/parts/action_bar.png
   :align: right
   :scale: 50%

The Action Bar appears at the top of all screen. It will show different information and different buttons depending on a) the particular screen and b) preferences you have set.

The Action Bar can display:

* The app name (**Engine Driver**)
* Optionally configured information:

  * Fast Clock
  * Children's Timer Status and Countdown
  * Full Screen or Action Bar Only left/right swipe
  * WiThrottle Server Name

* Optionally configured buttons:

  * Emergency Stop  (EStop)
  * Track Power
  * Flashlight
  * Throttle Web View
  * Throttle Layout Switching
  * In Phone Loco Sound
  * Children's Timer

* The Overflow Menu, which is normally three dots (⁞) or three bars (≡).   (Main Screens only)

The optionally configured items are configured via the corresponding preferences in the ``Throttle Screen Action Bar Preferences`` preference group.

Emergency Stop
""""""""""""""

|todo|

.. image:: ../_static/images/parts/estop.png
   :align: right
   :scale: 50%

The *Emergency Stop* Action Bar button is enable with the ...

*Emergency Stop*, when pressed ...

Track Power
"""""""""""

|todo|

.. image:: ../_static/images/parts/power_green.png
   :align: right
   :scale: 50%

The *Track Power* Action Bar button is enable with the ...

*Track Power*, when pressed ...

Flashlight
""""""""""

|todo|

.. image:: ../_static/images/parts/flashlight_on.png
   :align: right
   :scale: 50%

The *Flashlight* Action Bar button is enable with the ...

*Flashlight*, when pressed ...

Throttle Web View
"""""""""""""""""

|todo|

.. image:: ../_static/images/parts/web_view.png
   :align: right
   :scale: 50%

The *Throttle Web View* Action Bar button is enable with the ...

*Throttle Web View*, when pressed ...

In Phone Loco Sound
"""""""""""""""""""

|todo|

.. image:: ../_static/images/parts/in_device_sounds_outline.png
   :align: right
   :scale: 50%

The *In Phone Loco Sounds* Action Bar button is enable with the ...

*In Phone Loco Sounds*, when pressed ...

Children's Timer Button
"""""""""""""""""""""""

.. image:: ../_static/images/parts/timer.png
   :align: right
   :scale: 50%

The *Children's Timer Button* Action Bar button is enable with the ...

*Children's Timer Button*, when pressed ...

Fast Clock
""""""""""

|todo|

.. image:: ../_static/images/parts/fast_clock.png
   :align: right
   :scale: 50%

The *Fast Clock* Action Bar button is enable with the ...

*Fast Clock*, when pressed ...

Children's Timer Status and Countdown
"""""""""""""""""""""""""""""""""""""

|todo|

Full Screen or Action Bar Only left/right swipe
"""""""""""""""""""""""""""""""""""""""""""""""

|todo|

WiThrottle Server Name
""""""""""""""""""""""

|todo|



----

Overflow Menu
^^^^^^^^^^^^^

The Overflow Menu (or simply 'Menu') appears in the Action Bar at the top of most of the main screens. It will show different options depending on a) the particular screen, b) preferences you have set and c) the state of certain elements in the app.

The Overflow Menu can display

* Throttle
* Turnouts/Points
* Routes
* Web
* Power
* Function Defaults
* Gamepads

  * Gamepad Test 1
  * Gamepad Test ...

* Loco Sounds
* View Log
* Exit
* About

