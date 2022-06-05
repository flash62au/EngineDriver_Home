*******************************************
Preferences
*******************************************

.. meta::
   :keywords: options preferences

.. include:: ../include.rst

.. sidebar::

  .. contents:: On This Page
    :local:
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

.. list-table::
    :widths: auto
    :header-rows: 1

    * - Layout Name
      - No. |br|\ Throttles
      - Slider |br|\ Orient.
      - Web |br|\ View
      - Function |br|\ Buttons
      - Throttle |br|\ Control
      - Direction |br|\ Buttons
    * -  Horizontal
      - 1 \- 3 
      - H
      - ✓
      - ✓
      - 0-100
      - ✓
    * - Vertical
      - 2
      - V
      - ✓    
      - ✓
      - 0-100    
      - ✓
    * - Big Buttons - Left
      - 1
      - 🗴
      - 🗴
      - ✓
      - 0-100
      - ✓
    * - Big Buttons - Right
      - 1
      - 🗴
      - 🗴
      - ✓
      - 0-100
      - ✓
    * - Vertical - Left
      - 1
      - V
      - ✓
      - ✓
      - 0-100
      - ✓
    * - Vertical - Right
      - 1
      - V
      - ✓
      - ✓
      - 0-100
      - ✓
    * - Vertical Shunting |br| Vertical Switching
      - 2
      - V
      - ✓
      - ✓
      - \-100 - 0 - +100
      - 🗴
    * - Vertical Shunting - Left |br| Vertical Switching - Left
      - 1
      - V
      - ✓
      - ✓
      - \-100 - 0 - +100
      - 🗴
    * - Vertical Shunting - Right |br| Vertical Switching - Right
      - 1
      - V
      - ✓
      - ✓
      - \-100 - 0 - +100
      - 🗴
    * - Horizontal Shunting |br| Horizontal Switching
      - 1 \- 3
      - H
      - ✓
      - ✓
      - \-100 - 0 - +100
      - 🗴
    * - Simple |br| (Tablet Recommended)
      - 1 \- 6
      - V
      - 🗴
      - see note
      - 0-100
      - ✓

Notes:

* The number is brackets after the Throttle Screen Layout name is the number of throttles that the layout can support.
* The 'Simple' Throttle Screen Layout is designed to allow for up to 6 throttles simultaneously.  |br|\ It is recommended that this only be used on a tablet device, because of the screen real estate demands that 6 throttles requires. |br|\ When this Throttle Screen Layout is selected, the ``Number of Throttles`` preferences options is activated.  You can then use this to restrict the number of throttles being displayed on the 'Simple' Throttle Screen Layout.  |br|\ Also the ``Functions Area Size`` preferences options is activated.  You can then use this to control how many Function Buttons are displayed with each throttle.  By default, not Function buttons will be shown. |br|\ If you have selected In Phone Loco Sounds, then you will want to set this to 4 (for Mute, Light, Bell and Whistle/Horn).

**Engine Driver** automatically reload the throttle screen after closing the preferences screen. 

Number of throttles 
"""""""""""""""""""

This preference allow you to set how many throttles to display on the Throttle Screen. (Limited by the selected Throttle Screen Layout.)

Only available for the following Throttle Screen Layouts:

* Horizontal (1-3)
* Horizontal Shunting / Horizontal Switching (1-3)
* Simple (1-6)

All other layouts will automatically change this preference to the fix number for that particular layout.


Speed Slider and Buttons Preferences
""""""""""""""""""""""""""""""""""""

The following preference allow you to adjust aspects of the Throttle Areas on the Throttle Screen.

**Increase Slider/Speed Height?**

When set, this preference will show a taller Slider, or Speed buttons, for throttles.

Only relevant for the following Throttle Screen Layouts:

* Horizontal (1-3)
* Horizontal Shunting / Horizontal Switching (1-3)

**Throttle Speed Slider Margin**

When set, this changes the space between either the edge of the screen and the ends of the Slider, or if the Speed Buttons are enabled, the edge of the Speed Buttons and the ends of the Slider.  Specific in pixels haw far to offset.  This is useful if you find it difficult to get the zero or maximum speeds without accidently touching the Speed Buttons.

Only relevant for the following Throttle Screen Layouts:

* Horizontal (1-3)
* Horizontal Shunting / Horizontal Switching (1-3)

**Display Speed buttons?**

|todo|

When this preferences is set, |ED| will 

Display buttons next to Speed Sliders to change loco speed

**Hide Speed Slider?**

|todo|

When this preferences is set, |ED| will 

Do not show speed slider, use speed buttons instead

**Hide Slider AND Speed Buttons?**

|todo|

When this preferences is set, |ED| will 

Show neither speed slider nor speed buttons

Only really of use on the ESU MCII

**Tick Marks on Speed Sliders?**

When this preferences is set, |ED| will show tick marks on the background of the Speed Sliders.

**Switching throttle Dead Zone**

|todo|

When this preferences is set, |ED| will 

Set the size of the dead zone on the slider of the Switching/Shunting Throttle Screen


**Stop Button Vertical Margins**
   
|todo|

When this preferences is set, |ED| will 

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


You can now arrange the labels on ED any way you want, and as long as the equivalent function has a similar name it doesn't matter what function number it is, it will activate it correctly.

I have added two new options to the menu " Special Exact" and "Special Partial"
These options override the Original and Complex options completely and ignore the string matching preferences (it disables them)

Their behaviour is:

* for every loco in the consist
  
  * for every function in the locos roster entries

    * if the string of the function label exactly matches (or partially matches) the label of the function the ED is currently showing for the pressed function button

      * the function will be activated on that loco
  
Note

* There is no lead trail checking.  any matching function will be activated in any loco
* If no matching function on a particular loco (including the lead) nothing will happen for that loco
* It will use the ED default function labels if you have set them
* OR whatever labels have been loaded for the lead loco.
* Partial patching is a bit so-so.  I have a couple of sound decoders that allow me to change the bell and whistle tones in the function buttons.  Those functions also get activated when I just press 'Bell' or 'Whistle' as that text was also in the labels for the functions..  




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

Use Volume buttons to control speed

**Speed button Change Amount**

|todo|

How much Volume buttons jump throttle speed

**Disable Volume keys?**

|todo|

Disables the hardware Volume keys on the phone/tablet that would otherwise control speed

**Volume keys follow touch?**

|todo|

The Volume keys speed control will follow the last touched throttle

Gamepad Preferences
"""""""""""""""""""

|todo|

**Gamepad type**

|todo|

Choose the option that best supports your gamepad

**Test Gamepad settings now!**

|todo|

Allows you to confirm that the chosen setting works correctly.\nTest screen will launch IMMEDIATELY on selection.

**Speed button Change Amount**

|todo|

How much each press of the Gamepad buttons changes the throttle speed

**Gamepad Button Click Volume %**

|todo|

Set the volume percent for gamepad button clicks

**Speed button Repeat Delay**

|todo|

How long between repeats on Gamepad speed buttons.  Smaller is faster.

**Gamepad button action <!-- X -->**

|todo|

Choose the action when you press the button

**Gamepad button action <!-- Y -->**

|todo|

Choose the action when you press the button

**Gamepad button action <!-- A -->**

|todo|

Choose the action when you press the button

**Gamepad button action <!-- B -->**

|todo|

Choose the action when you press the button

**Gamepad button action <!-- Start(Lower) -->**

|todo|

Choose the action when you press the button

**Gamepad button action <!-- Return(Upper) -->**

|todo|

Choose the action when you press the button

**Gamepad DPAD Up action**

|todo|

Choose the action when you press the button

**Gamepad DPAD Right action**

|todo|

Choose the action when you press the button

**Gamepad DPAD Down action**

|todo|

Choose the action when you press the button

**Gamepad DPAD Left action**

|todo|

Choose the action when you press the button

**Swap Direction buttons with Screen buttons?**

|todo|

Temporarily swap the two Gamepad Direction buttons if the Screen Direction buttons are swapped

**Enforce Gamepad Testing?**

|todo|

Test each gamepad every time they are connected

**Use Simple Test?**

|todo|

Only test that you can reduce speed

ESU MobileControl II Options
""""""""""""""""""""""""""""

|todo|

Device Stop button options
""""""""""""""""""""""""""

|todo|

**Stop Button long-press delay**

|todo|

How long for a \'long-press\' of the Stop button.\nA \'long-press\' stops all active throttles; a \'short-press\' pauses the current throttle.\nSmaller is faster.

**Enable Short Press**

|todo|

A \'short-press\' pauses the currently controlled locomotive/consist.\nWill revert to original speed when operations resume.

Device side button options
""""""""""""""""""""""""""

|todo|

**Top-left button action**

|todo|

Choose the action when you press the button

**Bottom-left button action**

|todo|

Choose the action when you press the button

**Top-right button action**

|todo|

Choose the action when you press the button

**Bottom-right button action**

|todo|

Choose the action when you press the button

**Button repeat delay**

|todo|

How long between repeats on device side buttons. Smaller is faster.

Control Knob options
"""""""""""""""""""""""""

|todo|

**Control Knob Zero Trim**

|todo|

Set the Control Knob zero trim setting. Smaller is closer to counter-clockwise end-stop position.  Permitted range 0-255.

**Direction Change at end-stop**

|todo|

Allow Loco direction to change when control knob at counter-clockwise end-stop position

**Show disable Knob button**

|todo|

Allow the control knob to be disabled by an action button on the throttle screen

Additional selected loco Indicator
""""""""""""""""""""""""""""""""""

|todo|

Additional highlight of the Loco Select button based on the selection method

Voice Response Preferences
""""""""""""""""""""""""""

|todo|

**Voice Response**

|todo|

When to speak key events and actions using Text to Speech (TTS)

**On Gamepad Throttle change**

|todo|

When you select a different throttle on the gamepad

**On Gamepad Speeds**

|todo|

When the speed hits certain speeds when using a gamepad

**On Gamepad Test start**

|todo|

When the gamepad test screen is launched

**On Gamepad Test complete**

|todo|

When the gamepad test screen is finished 

**On Gamepad Test key press**

|todo|

When each buttons is pressed in the gamepad test screen


Select Loco Preferences
-----------------------

|todo|

Stop on Release?
"""""""""""""""""""""""""

|todo|

Stop loco(s) when releasing from throttle

Drop Loco before acquire?
"""""""""""""""""""""""""

|todo|

Drop current loco before acquiring new loco

Allow loco select while moving?
"""""""""""""""""""""""""""""""

|todo|

Enables Loco Select button when moving

Default Address Length
"""""""""""""""""""""""""

|todo|

Default Loco Address Length, (Auto will set based on # of digits)

Roster in Recent Locos?
"""""""""""""""""""""""""

|todo|

Include roster selections in Recent list?

Roster Names in Recent Locos?
"""""""""""""""""""""""""""""

|todo|

Include Loco names from the roster in Recent list if a matching address is found

Maximum Recent Locos
"""""""""""""""""""""""""

|todo|

Maximum Recent Locos to show in list

Control consist Lights on long click
""""""""""""""""""""""""""""""""""""

|todo|

Change the Lights of the individual locos in a Consist with a long click on the Loco Select button.

Filter Roster
"""""""""""""""""""""""""

|todo|

Only show roster entries containing…

In Phone Loco Sounds
--------------------

|todo|

Throttle 1 Loco Sounds
"""""""""""""""""""""""""

|todo|

Play basic loco sounds in the phone for Throttle 1

Throttle 2 Loco Sounds
"""""""""""""""""""""""""

|todo|

Play basic loco sounds in the phone for Throttle 2

Additional Preferences
"""""""""""""""""""""""""

|todo|

Additional In Phone Loco Sounds preferences

**In Phone Momentum**

|todo|

Delay (momentum) per step change in milliseconds (0-2000)

**Don't clip loco step sounds**

|todo|

Loco step sounds will play till their end when changing step.  Momentum amount (above) becomes a minimum time only.


**In Phone Loco Sounds Volume**

|todo|

Volume for Loco engine sounds in the phone (1-100)

**In Phone Bell Sounds Volume**

|todo|

Volume for bell sounds in the phone (1-100)

**In Phone Horn/Whistle Sounds Volume**

|todo|

Volume for Horn/Whistle sounds in the phone (1-100)

**Bell button Latching/Momentary**

|todo|

Bell button is momentary (not latching)?

**F1 and F2 activate Bell and Horn?**

|todo|

F1 and F2 also activate IPLS Bell and Horn


Connect Preferences
-------------------

|todo|

Maximum Recent Connections
""""""""""""""""""""""""""

|todo|

Maximum Recent Connections to show in list

Auto-Connect to WiThrottle Server?
""""""""""""""""""""""""""""""""""

|todo|

Connect automatically to \'first\' WiThrottle Server discovered


Hide Demo Server
"""""""""""""""""""""""""

|todo|

Hide the Demo Server \'jmri.mstevetodd.com\' in the connection list

Initial Connection Timeout
""""""""""""""""""""""""""

|todo|

Set initial connection timeout in milliseconds

Socket Timeout
"""""""""""""""""""""""""

|todo|

Set socket read timeout in milliseconds

Mobile Data connection?
"""""""""""""""""""""""""

|todo|

Allow your device to connect to JMRI over Mobile Data

Feedback on Disconnect
"""""""""""""""""""""""""

|todo|

Play sound and vibrate on unexpected disconnect

Background Alert
"""""""""""""""""""""""""

TODO

Audible alert when the app is sent to the background

Web Screen Preferences
----------------------

|todo|

Web Screen Orientation
"""""""""""""""""""""""""

|todo|

Select the Web Screen orientation

Initial Web Screen Page
"""""""""""""""""""""""""

|todo|

Enter the initial Web Page (such as '/panel') for the Web Screen

Different to the 'Throttle Web View' initial Web Page.

Turnouts/Points and Routes Preferences
--------------------------------------

|todo|

Hide Sys Route Names?
"""""""""""""""""""""""""

|todo|

Hide system names for Routes, used to save space on Route list

Location Delimiter
"""""""""""""""""""""""""

|todo|

Set the character that marks the end of the Location portion of Turnout/Point and Route names

Hide if no user name?
"""""""""""""""""""""""""

|todo|

Omit Turnout/Point/Route from list if the user name is empty

Children's (Timer) Preferences
------------------------------

|todo|

Options for young children. Time controlled running.

- select the loco first.
- Timer will start with the first increase in speed.
- You must come back to this preference to reset the time (or clear it) after the timeout.
 
Recommendations:

- Enable the Action Bar button
- Disable the volume keys
- Disable 'Swipe Through Turnouts' 
- Disable 'Swipe Through Routes'
- Disable EStop


Time limited running
"""""""""""""""""""""""""

|todo|

Restrict the time that the loco will run. e.g. Each child (operator) will get an equal amount of time.

Restart Password
"""""""""""""""""""""""""

|todo|

Password to restart the timer with the current settings

Reset/Disable Password
"""""""""""""""""""""""""

|todo|

Password to reset/disable the timer settings

Allow Reverse?
"""""""""""""""""""""""""

|todo|

Enable the reverse button

Show Timer button?
"""""""""""""""""""""""""

|todo|

Display the Timer Button to activate the timer

Default time for Button
"""""""""""""""""""""""""

|todo|

Default time if using the Action Bar Button to activate the timer


Import/Export/Reset & Log Preferences
-------------------------------------

Import, Export or Reset
"""""""""""""""""""""""""

|todo|

'Import' or 'Export' preferences to the '\\Android\\data\\jmri.enginedriver\\files\\' folder, or 'Reset' them.
Will occur IMMEDIATELY on selecting the option.
WARNING! With 'Reset' and 'Import', Engine Driver will restart!
(You can transfer the preferences to a different phone by copying the file.)

Auto import from all Servers?
"""""""""""""""""""""""""""""

|todo|

Automatically import the preferences from servers on connection.
(If the file \'\\Android\\data\\jmri.enginedriver\\files\\auto_preferences.ed\' is on the server and if it is more recent that the last time checked.)

Include recent loco list?
"""""""""""""""""""""""""

|todo|

Include the locos in the recent loco list in \'Imports\' and \'Exports\'

Auto host specific import/export?
"""""""""""""""""""""""""""""""""

|todo|

On every connection to a host, AUTOMATICALLY 'Import' preferences for that host, and optionally 'Export' them on disconnect. 
(To constantly reset back to a known state, set to 'Auto import on connect only' after the first time, or after a manual save (below).)

Manual host specific import/export
""""""""""""""""""""""""""""""""""

|todo|

'Import' or 'Export' your preferences for a specific host to the '\\Android\\data\\jmri.enginedriver\\files\\' folder. The host must be in your recent connection list.
Will occur IMMEDIATELY on selecting the option.
(Only available when not currently connected.)

Show Timestamps on Log?
"""""""""""""""""""""""""

|todo|

Show Date Time for each entry on the log screen
