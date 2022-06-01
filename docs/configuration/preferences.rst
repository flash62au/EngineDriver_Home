*******************************************
Preferences
*******************************************

.. meta::
   :keywords: options preferences

.. include:: ../include.rst

.. sidebar::

  .. contents:: On This Page
    :depth: 3

----

**Show Advanced Preferences?**
  
  By default, only a small number of core preferences are displayed. Check this preference to show the additional preferences.

Device Preferences
------------------

Throttle Name
"""""""""""""

Use this to enter a unique name for your device/phone.  The name will appear in the wiThrottle window in JMRI.
  
Screen orientation
""""""""""""""""""

|todo|

* Portrait
* Landscape
* Auto-Rotate
* Auto-Web

Theme/Style
"""""""""""

|todo|

You can switch between different themes by changing this preference. 

* The original theme 
* The high contrast theme. |br|\ Similar to the original theme, without the textured background with deeper blacks and brighter whites. 
* The high contrast outline theme. |br|\ For people who like white text on a black background.
* The Dark theme. 
* The Colourful theme.


Localisation
""""""""""""

Changing this setting not only changes the language that is used, it also changes the railroad/railway terminology (eg, Selecting 'Use Phone’s global setting' and having this set to 'English (Australia)' then causes the term 'Points' to be displayed rather than 'Turnouts' as is displayed when 'English (US)' is selected). In the Preferences screen and the Throttle Screen Layout selection screen (where 'shunting' is displayed rather than 'switching').  This is not guaranteed to operate on all text on all screens. 

Supported localisations are:

* Use Phone's global setting |br| -  Will use any of the localisations below and your system is set to it
* English (US) |br| - Engine Driver's default
* English (UK) |br| - Activated if you select 'Use Phone's global setting' and your system is set to English (UK)
* English (AUS) |br| - Activated if you select 'Use Phone's global setting' and your system is set to English (AUS)
* English (NZ) |br| - Activated if you select 'Use Phone's global setting' and your system is set to English (NZ)
* Italian
* Portuguese
* German
* Spanish
* Catalan
* French
* Czech

Left/Right Swipe Preferences
""""""""""""""""""""""""""""

|todo|

**Disable full screen Swipe?**

|todo|

If checked, only the toolbar can be swiped to change screens

**Swipe through Web?**

|todo|

Include Web Screen when swiping between screens

**Swipe Through Turnouts/Points?**

|todo|

Include Turnouts/Points Screen when swiping between screens

**Swipe through Routes?**

|todo|

Include Routes screen when swiping between screens

Throttle Screen Appearance Preferences
--------------------------------------

|todo|

Throttle Screen Layout
""""""""""""""""""""""

+-----------------------------------+---------+--------------+---------------------+---------------+
|Format/Capability                  |Web View |Function |br| |Throttle Control     |Direction |br| |
|                                   |         |Buttons       |                     |Buttons        |
+===================================+=========+==============+=====================+===============+
|Horizontal (1-3)                   |✓        |✓             |0-100                |✓              |
+-----------------------------------+---------+--------------+---------------------+---------------+
|Vertical (2)                       |    ✓    |    ✓         |0-100                |    ✓          |
+-----------------------------------+---------+--------------+---------------------+---------------+
|Big Buttons - Left (1)             |    🗴    |    ✓         |0-100                |    ✓          |
+-----------------------------------+---------+--------------+---------------------+---------------+
|Big Buttons - Right (1)            |    🗴    |    ✓         |0-100                |    ✓          |
+-----------------------------------+---------+--------------+---------------------+---------------+
|Vertical - Left (1)                |    ✓    |    ✓         |0-100                |    ✓          |
+-----------------------------------+---------+--------------+---------------------+---------------+
|Vertical - Right (1)               |    ✓    |    ✓         |0-100                |    ✓          |
+-----------------------------------+---------+--------------+---------------------+---------------+
|Vertical Shunting (2) |br|         |    ✓    |    ✓         | \-100 - 0 - +100    |    🗴          |
|Vertical Switching (2)             |         |              |                     |               |
+-----------------------------------+---------+--------------+---------------------+---------------+
|Vertical Shunting - Left (1) |br|  |    ✓    |    ✓         | \-100 - 0 - +100    |    🗴          |
|Vertical Switching - Left (1)      |         |              |                     |               |
+-----------------------------------+---------+--------------+---------------------+---------------+
|Vertical Shunting - Right (1) |br| |    ✓    |    ✓         | \-100 - 0 - +100    |    🗴          |
|Vertical Switching - Right (1)     |         |              |                     |               |
+-----------------------------------+---------+--------------+---------------------+---------------+
|Horizontal Shunting (1-3) |br|     |    ✓    |    ✓         | \-100 - 0 - +100    |    🗴          |
|Horizontal Switching  (1-3)        |         |              |                     |               |
+-----------------------------------+---------+--------------+---------------------+---------------+
|Simple (Tablet Recommended) (1-6)  |    🗴    |see note      |0-100                |    ✓          |
+-----------------------------------+---------+--------------+---------------------+---------------+

Notes:

* The number is brackets after the Throttle Screen Layout name is the maximum number of throttles that the layout can support.
* The 'Simple' Throttle Screen Layout is designed to allow for up to 6 throttles simultaneously.  |br|\ It is recommended that this only be used on a tablet device, because of the screen real estate demands that 6 throttles requires. |br|\ When this Throttle Screen Layout is selected, the ``Number of Throttles`` preferences options is activated.  You can then use this to restrict the number of throttles being displayed on the 'Simple' Throttle Screen Layout.  |br|\ Also the ``Functions Area Size`` preferences options is activated.  You can then use this to control how many Function Buttons are displayed with each throttle.  By default, not Function buttons will be shown. |br|\ If you have selected In Phone Loco Sounds, then you will want to set this to 4 (for Mute, Light, Bell and Whistle/Horn).

**Engine Driver** automatically reload the throttle screen after closing the preferences screen. 

Number of throttles 
"""""""""""""""""""

|todo|

How many throttles to display on the Throttle Screen. (Limited by the selected Throttle Screen Layout.)


Speed Slider and Buttons Preferences
""""""""""""""""""""""""""""""""""""

|todo|

**Increase Slider/Speed Height?**

|todo|

Use a taller Slider, or Speed buttons, for throttles

**Throttle Speed Slider Margin**

|todo|

Number of pixels to offset margins of throttle speed sliders

**Display Speed buttons?**

|todo|

Display buttons next to Speed Sliders to change loco speed

**Hide Speed Slider?**

|todo|

Do not show speed slider, use speed buttons instead

**Hide Slider AND Speed Buttons?**

|todo|

Show neither speed slider nor speed buttons

Only really of use on the ESU MCII

**Tick Marks on Speed Sliders?**

|todo|

Show tick marks on the background of the Speed Sliders

**Switching throttle Dead Zone**

|todo|

Set the size of the dead zone on the slider of the Switching/Shunting Throttle Screen


**Stop Button Vertical Margins**
   
|todo|

Number of pixels to offset margins of the stop button from the speed buttons and bottom of screen.

Haptic Feedback (Vibration)
"""""""""""""""""""""""""""

|todo|

**Haptic Feedback (Vibration)**

|todo|

Haptic feedback (vibrate) on speed changes

**Haptic Feedback Duration**

|todo|

Duration of each vibration (in milliseconds).

**Haptic Feedback on Button Presses**
 
|todo|

Haptic feedback (vibrate) on button presses.

Direction Button Preferences
""""""""""""""""""""""""""""

|todo|

**Swap Direction buttons?**

|todo|

Permanently swap the two Direction buttons for all throttles

**Long press Swap Direction buttons?**

|todo|

Temporarily swap the two Direction buttons with a long press of any Direction button

**Direction button Long Press Delay**

|todo|

How many milliseconds constitutes a long press for the direction buttons<

**Left Direction button Label**

|todo|

Labels for all LEFT direction buttons. Enter \'Forward\' or blank for normal behaviour.

**Right Direction button Label**

|todo|

Labels for all RIGHT direction buttons. Enter \'Reverse\' or blank for normal behaviour.

**Short Left Direction button Label**

|todo|

Short Labels for all LEFT direction buttons. Enter \'Fwd\' or blank for normal behaviour.

**Short Right Direction button Label**
 
|todo|

Labels for all Short RIGHT direction buttons. Enter \'Rev\' or blank for normal behaviour.

Decrease Loco No. height?
"""""""""""""""""""""""""

|todo|

Use smaller buttons for the Loco Number, Speed and Direction buttons

Loco Address instead of Name?
"""""""""""""""""""""""""""""

|todo|

Show loco DCC Address(es) instead of the Roster Name(s) on the Throttle screen

Ignores the Roster name for the `Select` button label.  Changes the label only.  Has no other functional effect.

Default Function Preferences
""""""""""""""""""""""""""""

|todo|

When and how the default Function Labels are displayed

**Use default function labels?**

|todo|

Display the default Function Labels instead of labels from roster entries

Ignores the Roster for the Function button labels.  Changes the labels only.  Has no other functional effect.

**Number of Default Functions**

|todo|

Limit the Function Labels shown if not available from the Server roster

**Number of Default Functions for Roster**

|todo|

Limit the Function Labels shown for Server Roster Entries with no function Labels

Function Buttons Area size
""""""""""""""""""""""""""

|todo|

Number of Function Buttons (0-4) to show on the 'Simple' Throttle layout ONLY.

Throttle Web View Preferences
"""""""""""""""""""""""""""""

|todo|

Options for Throttle Web View appearance (Web page that will appear at the bottom of the Throttle Screen)

**Throttle Web View?**

|todo|

Include web view on Throttle screen

**Larger Throttle Web View?**

|todo|

Increase Throttle Web View size to 60% for small screens

**Initial throttle Web Page**

|todo|

Initial throttle Web Page (such as \'/panel/\')

Swipe Up-Down Preferences
"""""""""""""""""""""""""

|todo|

Options for swipe up or down on the Throttle screen

**Use Immersive Mode for Throttle view?**

|todo|

Display the Throttle view full screen.  

You can set Swipe up or down options to temporarily disable and reach the menu, though this is not strictly necessary anymore

**Hide Toolbar in Immersive Mode?**

|todo|

Set to also hide the Toolbar in immersive mode

**Swipe down action in the Throttle view?**

|todo|

What should happen when you swipe down on the Throttle screen.

**Swipe up action in the Throttle screen?**

|todo|

What should happen when you swipe up on the Throttle screen.

**Screen Dimming % Value**

|todo|

Brightness setting to use when dimming the screen (0%-99%). Disables Auto or Adaptive Brightness if set.

Accelerometer (Shake) Preferences
"""""""""""""""""""""""""""""""""

|todo|

Options for device motion on the Throttle screen

**Shake Action**

|todo|

Options for when you shake the device

**Shake Threshold**

|todo|

Threshold at which the shake will register. (1.5 - 3.5) Lower value will respond to a gentle action.
Requires restart of engine Driver after changing to take effect.

Background Image Preferences
""""""""""""""""""""""""""""

|todo|

Show a background image on the Throttle screen

**Background Image**

|todo|

Show a background image on the Throttle screen

**Background Image File Name**

|todo|

Enter the name of the background image file.

**Background Image Position**

|todo|

Select how the background image will be positioned on the screen.

Throttle Screen Action Bar Preferences
--------------------------------------

|todo|

Emergency Stop button?
""""""""""""""""""""""

|todo|

Show loco Emergency Stop button in action bar

Layout Power button?
""""""""""""""""""""

|todo|

Show Layout Power button in action bar

Flashlight button?
""""""""""""""""""

|todo|

Show Flashlight button in action bar

Fast Clock Display
""""""""""""""""""

|todo|

Set format for Fast Clock display in action bar

Throttle Web View button?
"""""""""""""""""""""""""

|todo|

Show button in action bar to show/hide Throttle Web View. (requires 'Throttle Web View' preference to be enabled)

Layout Switch Button Preferences
""""""""""""""""""""""""""""""""

|todo|

Show the Throttle Layout Switch button in the Throttle Screen action bar to allow quick changing of Throttle Layouts

**Show Layout Switch button?**

|todo|

Show the Throttle Layout Switch button in the Throttle Screen action bar to allow quick changing of Throttle Layouts

**First Screen Layout**

|todo|

Layout Switch Button will switch between this throttle layout and the next preference

**Second Screen Layout**

|todo|

Layout Switch Button will switch between the throttle layout in the previous preference and this one

In phone sounds button
""""""""""""""""""""""

|todo|

Show an action bar button to change the in phone loco sounds options

Show Server Description
"""""""""""""""""""""""

|todo|

Show the description of the current server on the action bar

Throttle Control Preferences
----------------------------

|todo|

Speed Units
"""""""""""

|todo|

Display speed as percentage, or by a specific number of steps

 * Percent 0 - 100%
 * Auto Speed steps
 * 8 steps
 * 10 steps
 * 14 steps
 * 28 steps
 * 128 steps


Maximum throttle Percentage
"""""""""""""""""""""""""""

|todo|

Maximum Allowed throttle slider value in % in ALL sliders

Maximum throttle Change
"""""""""""""""""""""""

|todo|

Maximum allowed throttle change in %

Speed button Change Amount
""""""""""""""""""""""""""

|todo|

How much Speed buttons jump throttle speed

Speed button Repeat Delay
"""""""""""""""""""""""""

|todo|

How long between repeats on speed buttons.\nSmaller is faster. Excludes gamepad buttons. (See separate gamepad setting.)

Speed step on Decrement?
""""""""""""""""""""""""

|todo|

Force the speed step to be used when long pressing a lower speed on the slider.\nIf not checked, the speed will immediately jump to the touched speed.

Stop on Phone call?
"""""""""""""""""""

|todo|

Stop loco(s) when a phone call is answered or placed

Direction change while moving?
""""""""""""""""""""""""""""""

|todo|

Allow direction changes when moving

Stop on direction change?
"""""""""""""""""""""""""

|todo|

Stop loco if you change direction while moving

'Limit Speed' & 'Pause' button Preferences
""""""""""""""""""""""""""""""""""""""""""

|todo|

**Show 'Limit Speed' button?**

|todo|

Show a button to temporarily restrict the maximum speed on an individual throttle

**'Limit Speed' button**

|todo|

Set the \% of the throttle that the speed will be temporarily limited to

**Show 'Pause' button?**

|todo|

Show a button to slow and stop the locomotive, then return to original speed on next press

**'Pause' button Rate**

|todo|

Number of milliseconds between speed step changes for the Pause action

**'Pause' button Step**

|todo|

Step size changes for the Pause action

Consist Function Follow Preferences
-----------------------------------

|todo|

Options for how functions will behave in a consist.

Consist Functions - Follow Rule Style
"""""""""""""""""""""""""""""""""""""

|todo|

Which style of rules to follow in a consist when function buttons are pressed.

Note: If 'Use Default function labels' is enabled, 'Special...' will also apply to the lead (or only) loco.

Selective Lead Unit Sound?
""""""""""""""""""""""""""

|todo|

Send Horn/Bell functions to only the Lead unit in an EngineDriver consist. 

(Only/any function with a 'label' that includes 'bell', 'horn' or 'whistle' as part of the label.)

Always treat F1 as Sound?
"""""""""""""""""""""""""

|todo|

For the 'Selective Lead Unit Sound' option

Always treat F2 as Sound?
"""""""""""""""""""""""""

|todo|

For the 'Selective Lead Unit Sound' option

If All matches Fail Action
""""""""""""""""""""""""""

|todo|

Which locos in the consist should react to the function buttons if none of the rules below are meet.

Headlight specific String 1
"""""""""""""""""""""""""""

|todo|

Comma separated string(s) to look for in the function labels of the locos in the consist to recognise the \'Headlight\' function (normally F0).

Headlight specific Action 1
"""""""""""""""""""""""""""

|todo|

Which locos in the consist should react to the found headlight functions.

String 2, 3, 4, 5
"""""""""""""""""

|todo|

Action for String 2, 3, 4, 5
""""""""""""""""""""""""""""

|todo|


Additional Throttle Control Source Preferences
----------------------------------------------

|todo|

Volume Button Preferences
"""""""""""""""""""""""""

|todo|

**Speed button Change Amount**

|todo|

**Disable Volume keys?**

|todo|

**Volume keys follow touch?**

|todo|

Gamepad Preferences
"""""""""""""""""""

|todo|

**Gamepad type**

|todo|

**Test Gamepad settings now!**

|todo|

**Speed button Change Amount**

|todo|

**Gamepad Button Click Volume %**

|todo|

**Speed button Repeat Delay**

|todo|

**Gamepad button action <!-- X -->**

|todo|

**Gamepad button action <!-- Y -->**

|todo|

**Gamepad button action <!-- A -->**

|todo|

**Gamepad button action <!-- B -->**

|todo|

**Gamepad button action <!-- Start(Lower) -->**

|todo|

**Gamepad button action <!-- Return(Upper) -->**

|todo|

**Gamepad DPAD Up action**

|todo|

**Gamepad DPAD Right action**

|todo|

**Gamepad DPAD Down action**

|todo|

**Gamepad DPAD Left action**

|todo|

**Swap Direction buttons with Screen buttons?**

|todo|

**Enforce Gamepad Testing?**

|todo|

**Use Simple Test?**

|todo|

ESU MobileControl II Options
""""""""""""""""""""""""""""

|todo|

Device Stop button options
""""""""""""""""""""""""""

|todo|

**Stop Button long-press delay**

|todo|

**Enable Short Press**

|todo|

Device side button options
""""""""""""""""""""""""""

|todo|

**Top-left button action**

|todo|

**Bottom-left button action**

|todo|

**Top-right button action**

|todo|

**Bottom-right button action**

|todo|

**Button repeat delay**

|todo|

Control Knob options
"""""""""""""""""""""""""

|todo|

**Control Knob Zero Trim**

|todo|

**Direction Change at end-stop**

|todo|

**Show disable Knob button**

|todo|

Additional selected loco Indicator
""""""""""""""""""""""""""""""""""

|todo|


Voice Response Preferences
""""""""""""""""""""""""""

|todo|

**Voice Response**

|todo|

**On Gamepad Throttle change**

|todo|

**On Gamepad Speeds**

|todo|

**On Gamepad Test start**

|todo|

**On Gamepad Test complete**

|todo|

**On Gamepad Test key press**

|todo|


Select Loco Preferences
-----------------------

|todo|

Stop on Release?
"""""""""""""""""""""""""

|todo|

Drop Loco before acquire?
"""""""""""""""""""""""""

|todo|

Allow loco select while moving?
"""""""""""""""""""""""""""""""

|todo|

Default Address Length
"""""""""""""""""""""""""

|todo|

Roster in Recent Locos?
"""""""""""""""""""""""""

|todo|

Roster Names in Recent Locos?
"""""""""""""""""""""""""""""

|todo|

Maximum Recent Locos
"""""""""""""""""""""""""

|todo|

Control consist Lights on long click
""""""""""""""""""""""""""""""""""""

|todo|

Filter Roster
"""""""""""""""""""""""""


|todo|

In Phone Loco Sounds
--------------------

|todo|

Throttle 1 Loco Sounds
"""""""""""""""""""""""""

|todo|

Throttle 2 Loco Sounds
"""""""""""""""""""""""""

|todo|

Additional Preferences
"""""""""""""""""""""""""

|todo|

**In Phone Momentum**

|todo|

**Don't clip loco step sounds**

|todo|

**In Phone Loco Sounds Volume**

|todo|

**In Phone Bell Sounds Volume**

|todo|

**In Phone Horn/Whistle Sounds Volume**

|todo|

**Bell button Latching/Momentary**

|todo|

**F1 and F2 activate Bell and Horn?**

|todo|


Connect Preferences
-------------------

|todo|

Maximum Recent Connections
""""""""""""""""""""""""""

|todo|

Auto-Connect to WiThrottle Server?
""""""""""""""""""""""""""""""""""

|todo|

Hide Demo Server
"""""""""""""""""""""""""

|todo|

Initial Connection Timeout
""""""""""""""""""""""""""

|todo|

Socket Timeout
"""""""""""""""""""""""""

|todo|

Mobile Data connection?
"""""""""""""""""""""""""

|todo|

Feedback on Disconnect
"""""""""""""""""""""""""

|todo|

Background Alert
"""""""""""""""""""""""""

TODO


Web Screen Preferences
----------------------

|todo|

Web Screen Orientation
"""""""""""""""""""""""""

|todo|

Initial Web Screen Page
"""""""""""""""""""""""""

|todo|

Turnouts and Routes Preferences
-------------------------------

|todo|

Hide Sys Route Names?
"""""""""""""""""""""""""

|todo|

Location Delimiter
"""""""""""""""""""""""""

|todo|

Hide if no user name?
"""""""""""""""""""""""""

|todo|

Children's (Timer) Preferences
------------------------------

|todo|

Time limited running
"""""""""""""""""""""""""

|todo|

Restart Password
"""""""""""""""""""""""""

|todo|

Reset/Disable Password
"""""""""""""""""""""""""

|todo|

Allow Reverse?
"""""""""""""""""""""""""

|todo|

Show Timer button?
"""""""""""""""""""""""""

|todo|

Default time for Button
"""""""""""""""""""""""""

|todo|

Notes for the Timer:
"""""""""""""""""""""""""

|todo|

Import/Export/Reset & Log Preferences
-------------------------------------

Import, Export or Reset
"""""""""""""""""""""""""

|todo|

Import from current Server (manually)
"""""""""""""""""""""""""""""""""""""

|todo|

Auto import from all Servers?
"""""""""""""""""""""""""""""

|todo|

Include recent loco list?
"""""""""""""""""""""""""

|todo|

Auto host specific import/export?
"""""""""""""""""""""""""""""""""

|todo|

Manual host specific import/export
""""""""""""""""""""""""""""""""""

|todo|

Show Timestamps on Log?
"""""""""""""""""""""""""

|todo|
