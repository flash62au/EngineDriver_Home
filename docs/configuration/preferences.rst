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

|ed| is highly configurable.  There are over 100 different items than can be changed to allow you customise your experience with |ED|\ .

Most configuration options are found in the *Preferences* which is accessed via the overflow menu, sometimes called a 'hamburger menu', which is normally three dots (⁞) or three bars (≡).

Advanced Preferences
--------------------------

Show Advanced Preferences?
""""""""""""""""""""""""""

By default, only a small number of core preferences are displayed. 

If you enable this preference |ed| will immedialy show the additional preferences.

Device Preferences
------------------

The following preferences provide options for the 'whole' of |ed|.

Throttle Name
"""""""""""""

Use this to enter a unique name for your device/phone.  The name will appear in the WiThrottle window in JMRI.  While not significant ion a single user layout, having a name on the device can be useful in club or multi user environments, especially when trying to sort out issues.
  
Screen orientation
""""""""""""""""""

There are four options to choose from:

* Portrait
* Landscape
* Auto-Rotate
* Auto-Web

.. list-table::
    :width: 100%
    :widths: 60 40
    :header-rows: 1

    * - Example
      - Theme
    * - .. image:: ../_static/images/screenshots/throttle_horizontal_outline_theme.png  
          :scale: 8%
      - Portrait
    * - .. image:: ../_static/images/screenshots/throttle_horizontal_landscape_outline_theme.png 
          :scale: 8%
      - Landscape
    * - see above 
      - Auto-Rotate |br|\ will switch between |br|\ Portrait and |br|\ landscape when |br|\ you rotate the |br|\ screen
    * - .. image:: ../_static/images/screenshots/auto_web.png
          :scale: 8%
      - Auto-Web |br|\ will show the |br|\ Web Screen when |br|\ you rotate the |br|\ screen

Theme/Style
"""""""""""

Themes provide different colours and textures to the buttons, backgrounds, sliders etc.  You can switch between different themes by changing this preference. 

There are five themes to choose from:

* Original 
* High contrast
* High contrast *outline*
* Dark
* Colourful

.. list-table::
    :width: 100%
    :widths: 50 50
    :header-rows: 1

    * - Example
      - Theme
    * - .. image:: ../_static/images/screenshots/throttle_horizontal_original_theme.png  
          :scale: 8%
      - Original theme
    * - .. image:: ../_static/images/screenshots/throttle_horizontal_high_contrast_theme.png 
          :scale: 8%
      - High contrast theme |br|\ |br|\ Similar to the original |br|\ theme, without the |br|\ textured background |br|\ with deeper blacks |br|\ and brighter whites.
    * - .. image:: ../_static/images/screenshots/throttle_horizontal_outline_theme.png
          :scale: 8%
      - High contrast |br|\ Outline theme |br|\ |br|\ For people who like |br|\ white text on a |br|\ black background.
    * - .. image:: ../_static/images/screenshots/throttle_horizontal_dark_theme.png
          :scale: 8%
      - Dark theme
    * - .. image:: ../_static/images/screenshots/throttle_horizontal_colorful_theme.png
          :scale: 8%
      - Colourful theme

Localisation
""""""""""""

Changing the *Localisation* primarily changes the language used in the menus, buttons and messages throughout |ED|.

For English, it also changes the railroad/railway terminology (eg, Selecting 'Use Phone's global setting' and having this set to 'English (Australia)' or 'English (UK)' results in the term 'Points' to be displayed rather than 'Turnouts' as is displayed when 'English (US)' is selected). In the Preferences screen and the Throttle Screen Layout selection screen (where 'shunting' is displayed rather than 'switching').  This is not guaranteed to operate on all text on all screens. 

Supported localisations are:

* Use Phone's global setting |br| -  Will use any of the localisations below depending on what your system is set to it
* English (US) |br| - Engine Driver's default
* Italian
* Portuguese
* German
* Spanish
* Catalan
* French
* Czech

The following can't be chosen in the preference, but will be activated automatically if you select ``Use the Phone's global setting`` and you have selected one of the following primary languages in you Device's / Phone's global settings:

* English (UK)
* English (AUS)
* English (NZ)

Left/Right Swipe Preferences
""""""""""""""""""""""""""""

The following preferences provide options for how *left/right swipes* work and which screens are available when you swipe left / right.

Disable full screen Swipe?
'''''''''''''''''''''''''''''''''''

If this preference is enabled, only the Action Bar can be swiped to change screens.  This is useful if you find it difficult to swipe left and right on either of the two Web Views without accidently changing screens.

Swipe through Web?
'''''''''''''''''''''''''''''''''''

If this preference is enabled, the Web Screen is included in the list of screens when swiping left/right between screens.

Swipe Through Turnouts/Points?
'''''''''''''''''''''''''''''''''''

If this preference is enabled, the Turnouts/Points Screen is included in the list of screens when swiping left/right between screens.

Swipe through Routes?
'''''''''''''''''''''''''''''''''''

If this preference is enabled, the Routes Screen is included in the list of screens when swiping left/right between screens.

Throttle Screen Appearance Preferences
--------------------------------------

The following preferences provide options for the appearance of the Throttle Screen.

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

|ed| automatically reload the throttle screen after closing the preferences screen. 

Number of throttles 
"""""""""""""""""""

This preference allows you to set how many throttles to display on the Throttle Screen. (Limited by the selected Throttle Screen Layout.)

Only available for the following Throttle Screen Layouts:

* Horizontal (1-3)
* Horizontal Shunting / Horizontal Switching (1-3)
* Simple (1-6)

All other layouts will automatically change this preference to the fixed number for that particular layout.


Speed Slider and Buttons Preferences
""""""""""""""""""""""""""""""""""""

The following preference allows you to adjust aspects of the Throttle Areas on the Throttle Screen.

Increase Slider/Speed Height?
'''''''''''''''''''''''''''''''''''

When set, this preference will show a taller Slider, or Speed buttons, for throttles.

Only relevant for the following Throttle Screen Layouts:

* Horizontal (1-3)
* Horizontal Shunting / Horizontal Switching (1-3)

Throttle Speed Slider Margin
'''''''''''''''''''''''''''''''''''

When set, this changes the space between either the edge of the screen and the ends of the Slider, or if the Speed Buttons are enabled, the edge of the Speed Buttons and the ends of the Slider.  Specific in pixels haw far to offset.  This is useful if you find it difficult to get the zero or maximum speeds without accidently touching the Speed Buttons.

Only relevant for the following Throttle Screen Layouts:

* Horizontal (1-3)
* Horizontal Shunting / Horizontal Switching (1-3)

Display Speed buttons?
'''''''''''''''''''''''''''''''''''

When this preferences is set, |ED| will display buttons (``++`` and ``--``) next to Speed Sliders to change loco speed.  

Clicking the ``++`` button will increase the speed of the Locos(s) by a preset amount. Clicking the ``--`` button will increase the speed of the Locos(s) by a preset amount.  

The amount the speed changes on each press can be changed with the `Speed Button Change Amount`_ preference.  Note that this is independent of the `Speed Button Change Amount (Volume)`_ preference and the `Speed Button Change Amount (Gamepad)`_ preference.

Holding down a button will increase / decrease the speed continuously by the preset amount, in series of steps.

The time between steps can be changed with the `Speed Button Repeat Delay`_ preference.  Note that this is independent of the `Speed Button Repeat Delay (Gamepad)`_ preference.  But the Volume button repeat Delay is linked to it.


Hide Speed Slider?
'''''''''''''''''''''''''''''''''''

When this preferences is set, |ED| will not show speed slider, use speed buttons instead.

This option is not relevant for the following Throttle Screen Layouts as they cannot have a slider:

* Big Buttons - Left
* Big Buttons - Right

Hide Slider AND Speed Buttons?
'''''''''''''''''''''''''''''''''''

When this preferences is set, |ED| will show neither speed slider nor speed buttons.t

Only really of use on the ESU MCII

This option is not relevant for the following Throttle Screen Layouts as they cannot be without the Speed buttons:

* Big Buttons - Left
* Big Buttons - Right

Tick Marks on Speed Sliders?
'''''''''''''''''''''''''''''''''''

When this preferences is set, |ED| will show tick marks on the background of the Speed Sliders.

Switching throttle Dead Zone
'''''''''''''''''''''''''''''''''''

When this preferences is set, |ED| will set the size of the dead zone, or detent, on the slider of the Switching/Shunting Throttle Screen.  The larger the size, the easier it is to find Zero on the slider.

* Vertical Shunting |br| Vertical Switching
* Vertical Shunting - Left |br| Vertical Switching - Left
* Vertical Shunting - Right |br| Vertical Switching - Right
* Horizontal Shunting |br| Horizontal Switching
* Horizontal Shunting - Left |br| Horizontal Switching - Left
* Horizontal Shunting - Right |br| Horizontal Switching - Right


Stop Button Vertical Margins
'''''''''''''''''''''''''''''''''''
   
When this preferences is set, |ED| will add the entered number of pixels to offset margins of the stop button from the speed buttons and bottom of screen.  This is useful if you find it difficult to get the zero speeds on the vertical sliders without accidently touching the Stop Button.

Only relevant to the following Throttle Screen layouts:

* Vertical
* Vertical Shunting |br| Vertical Switching
* Vertical Shunting - Left |br| Vertical Switching - Left
* Vertical Shunting - Right |br| Vertical Switching - Right

Haptic Feedback (Vibration) Preferences
"""""""""""""""""""""""""""""""""""""""

The following preferences provide options for how and when the Device / Phone will *vibrate* on certain actions.

Haptic Feedback (Vibration)
'''''''''''''''''''''''''''''''''''

When this preferences is set, |ED| will the device / phone will provide Haptic feedback (vibrate) on speed changes.

Options:

* None
* Slider - Every Step
* Slider - Skip some at 29, 100, 128 Steps

Haptic Feedback Duration
'''''''''''''''''''''''''''''''''''

Use with preference to change the duration of each vibration (in milliseconds).

Haptic Feedback on Button Presses
'''''''''''''''''''''''''''''''''''
 
When this preferences is set, |ED| will provide haptic feedback (vibrate) on button presses.

Direction Button Preferences
""""""""""""""""""""""""""""

The following preferences provide options for Direction Buttons.

Swap Direction buttons?
'''''''''''''''''''''''''''''''''''

When this preferences is set, |ED| will permanently swap the two Direction buttons for all throttles.

Long press Swap Direction buttons?
'''''''''''''''''''''''''''''''''''

When this preferences is set, |ED| will temporarily swap the two Direction buttons when you long press of either of the Direction buttons.

Direction button Long Press Delay
'''''''''''''''''''''''''''''''''''

|todo|

How many milliseconds constitutes a long press for the direction buttons

Left Direction button Label
'''''''''''''''''''''''''''''''''''

You can use this preference to change the labels for all LEFT direction buttons. 

Enter \'Forward\' or blank for normal behaviour.

Right Direction button Label
'''''''''''''''''''''''''''''''''''

You can use this preference to change the labels for all RIGHT direction buttons.

Enter \'Reverse\' or blank for normal behaviour.

Short Left Direction button Label
'''''''''''''''''''''''''''''''''''

You can use this preference to change the short labels for all LEFT direction buttons.

Enter \'Fwd\' or blank for normal behaviour.

Short Right Direction button Label
'''''''''''''''''''''''''''''''''''
 
You can use this preference to change the short labels for all RIGHT direction buttons.

Enter \'Rev\' or blank for normal behaviour.

Decrease Loco No. height?
"""""""""""""""""""""""""

You can use this preference to have |ed| use smaller buttons for the Loco Number, Speed and Direction buttons

Loco Address instead of Name?
"""""""""""""""""""""""""""""

You can use this preference to have |ed| to show loco DCC Address(es) instead of the Roster Name(s) on the Throttle screen.  It will ignore the Roster name for the `Select` button label.  This changes the label only.  It has no other functional effect.

Default Function Preferences
""""""""""""""""""""""""""""

The following preferences provide options for when and how the default Function Labels are displayed.

Use default function labels?
'''''''''''''''''''''''''''''''''''

You can use this preference to have |ed| *always* display the default Function Labels (configured inside |ed|\ ) instead of labels from roster entries. It will ignore the Roster for the Function button labels.  It changes the labels only.  It has no other functional effect.

Number of Default Functions
'''''''''''''''''''''''''''''''''''

You can use this preference to limit the Function to limit the Function Labels shown for selected locos that are not from the Server Roster, or where you have set the `Use default function labels?`_ preference. 

Number of Default Functions for Roster
''''''''''''''''''''''''''''''''''''''

You can use this preference to limit the Function Labels shown for Server Roster Entries that don't have any function Labels configured.

Function Buttons Area size
""""""""""""""""""""""""""

You can use this preference to instruct |ed| to show some, or no, Function Buttons (0-4) below the Speed Slider the 'Simple' Throttle layout ONLY.

Only relevant to the following Throttle Screen layouts:

* Simple

Throttle Web View Preferences
"""""""""""""""""""""""""""""

The following preferences provide options for options for *Throttle Web View* appearance.

The *Throttle Web View* is a smaller (approximately half page) Web browser window that will appear at the bottom of the Throttle Screen, and is difference to the main Web View Screen.  The two are configured independently.

Throttle Web View?
'''''''''''''''''''''''''''''''''''

You can use this preference to have |ed| to show a *Web View* area on the Throttle screen which is essentially a Web Browser.

Larger Throttle Web View?
'''''''''''''''''''''''''''''''''''

You can use this preference to instruct |ed| to increase the Throttle Web View size to 60% for small screens

Initial throttle Web Page
'''''''''''''''''''''''''''''''''''

You can use this preference to set the initial throttle Web Page (such as \'/panel/\') for when the *Throttle Web View* first opens.

Enter the initial Web Page (such as '/panel') for the Web Screen

Note that this is different to the 'Web Screen' initial Web Page which is set with the `Initial Web Screen Page`_ preference.

Swipe Up-Down Preferences
"""""""""""""""""""""""""

The following preferences provide options for options for swipe up or down on the Throttle screen

Use Immersive Mode for Throttle view?
'''''''''''''''''''''''''''''''''''''

Setting this preference will display the Throttle view full screen.  The Navigation bar and the Status Bar will be hidden, Swiping down from off the screen will temporarily show them again.

Hide Toolbar in Immersive Mode?
'''''''''''''''''''''''''''''''''''

Setting this preference, along with `Use Immersive Mode for Throttle view?`_ preference will display the Throttle view in and extended full screen.  The Action Bar, along with the Navigation bar and the Status Bar will be hidden, Swiping down from off the screen will temporarily show the the Navigation bar and Status bar again, but not the Action Bar.

It is essential, that you can set `Swipe down action in the Throttle view?`_ or `Swipe up action in the Throttle screen?`_ preferences to temporarily disable this and allow you to reach the menu.

Swipe down action in the Throttle view?
'''''''''''''''''''''''''''''''''''''''

|todo|

What should happen when you swipe down on the Throttle screen.

Options:

* None
* Hide Web View |br| (requires `Throttle Web View?`_ preference to be set)
* Lock and Dim Screen
* Dim Screen
* Immersive Mode temporarily enable-disable
* Switch Throttle Screen Layouts



Swipe up action in the Throttle screen?
'''''''''''''''''''''''''''''''''''''''

|todo|

What should happen when you swipe up on the Throttle screen.

Options:

* None
* Hide Web View |br| (requires `Throttle Web View?`_ preference to be set)
* Lock and Dim Screen
* Dim Screen
* Immersive Mode temporarily enable-disable
* Switch Throttle Screen Layouts


Screen Dimming % Value
'''''''''''''''''''''''''''''''''''

|todo|

Brightness setting to use when dimming the screen (0%-99%). Disables Auto or Adaptive Brightness if set.

Requires that one of the following is set to ``Lock and Dim Screen`` or ``Dim Screen``

* `Swipe down action in the Throttle view?`_
* `Swipe up action in the Throttle screen?`_
* `Accelerometer (Shake) Preferences`_

Accelerometer (Shake) Preferences
"""""""""""""""""""""""""""""""""

The following preferences provide options for options for what happens when you shake your device / phone while on the Throttle screen.

Shake Action
'''''''''''''''''''''''''''''''''''

|todo|

Options for when you shake the device

Options:

* None
* Hide Web View |br| (requires `Throttle Web View?`_ preference to be set)
* Lock and Dim Screen
* Dim Screen
* Immersive Mode temporarily enable-disable
* Switch Throttle Screen Layouts

Shake Threshold
'''''''''''''''''''''''''''''''''''

|todo|

Threshold at which the shake will register. (1.5 - 3.5) Lower value will respond to a gentle action.
Requires restart of engine Driver after changing to take effect.

Background Image Preferences
""""""""""""""""""""""""""""

.. image:: ../_static/images/screenshots/background_fill.png
  :align: right
  :scale: 12%

The following preferences provide options for showing a background image on the Throttle screen.

Background Image
'''''''''''''''''''''''''''''''''''

Enabling this preference will cause |ed| to show a background image on the Throttle screen, as long as one is selected in the `Background Image File Name`_ preference.

Background Image File Name
'''''''''''''''''''''''''''''''''''

|todo|
 
This preference allows you to select a image file that will be used as the background o the Throttle Screen.  This has no effect unless the `Background Image`_ preference is enabled.

Clicking on this preference launches your image chooser app.  As this can be different on different devices / manufacturers, it is impossible to describe the required steps here.  In general, use the apps navigation features to find the image you want and select it.

Note: You can install additional apps to do the same job for the Play Store.

Background Image Position
'''''''''''''''''''''''''''''''''''

This preference lets you select how the background image will be positioned and/or resized on the screen.

Options include:

* Fit - Shrink/expand
* Fill - Crop one edge pair
* Center - No scaling
* Fit - Shrink only
* Fill - Distort if needed

  **Fit - Shrink/expand**

  Using this option will cause the image to be:
  
  * proportionally reduced in size in too big to fit the screen, such that the image fills the screen in at least one dimension
  * proportionally increased in size in too small to fill the screen, such that the image fills the screen in at least one dimension

  **Fill - Crop one edge pair**

  Using this option will cause the image to be:
  
  * proportionally reduced in size in too big to fit the screen, such that the image will be cropped on either the top/bottom or the sides, so that the image fills the screen 
  * proportionally increased in size in too small to fill the screen, such that the image will be cropped on either the top/bottom or the sides, so that the image fills the screen

  **Center - No scaling**

  Using this option will cause the image to be centered on the screen.  It will not be either shrunk or expanded.

  **Fit - Shrink only**

  Using this option will cause the image to be proportionally reduced in size in too big to fit the screen, such that the image fills the screen in at least one dimension.  If it to smaller than the screen in both dimensions it will not be resized.

  **Fill - Distort if needed**

  Using this option will cause the image to be forcibly:

  * reduced in size in too big to fit the screen, distorting the image if needed to fill the entire screen in both dimensions
  * increased in size in too small to fill the screen, distorting the image if needed to fill the entire screen in both dimensions

Throttle Screen Action Bar Preferences
--------------------------------------


.. image:: ../_static/images/parts/action_bar.png
   :align: right
   :scale: 40%

The following preferences provide options for showing additional buttons on the Action Bar, primarily at the top of the Throttle Screen though some will show on many screens.

Emergency Stop button?
""""""""""""""""""""""

.. image:: ../_static/images/parts/estop.png
   :align: right
   :scale: 50%

Setting this preference will display an Emergency Stop button in Action Bar of most of the Main Screens.

Clicking this button will attempt to quickly stop all locos controlled by the device / phone.  Locos controlled by other people/devices are not stopped.

Layout Power button?
""""""""""""""""""""

.. image:: ../_static/images/parts/power_green.png
   :align: right
   :scale: 50%

Setting this preference will display a *Layout Power button* in Action Bar of most of the Main Screens.

Clicking this button will turn on/off the power to the track. The colour of the button will change colour:

* 'Amber' = unknown state
* 'Red' = Power is Off
* 'Green' = Power is On

Flashlight button?
""""""""""""""""""

.. image:: ../_static/images/parts/flashlight_on.png
   :align: right
   :scale: 50%


Setting this preference will display a *Flashlight* button in action bar of the Throttle Screen.

Clicking this button will turn on/off the Device's camera light.

This preference will be disabled (unable to be set) if the device does not have a camera.

Fast Clock Display
""""""""""""""""""

.. image:: ../_static/images/parts/fast_clock.png
   :align: right
   :scale: 50%

Use this preference to set the format for *Fast Clock display* in action bar:

* none
* 12 Hour format
* 24 Hour format

Throttle Web View button?
"""""""""""""""""""""""""

.. image:: ../_static/images/parts/web_view.png
   :align: right
   :scale: 50%

Setting this preference will display a button in action bar of the Throttle Screen to show/hide *Throttle Web View*. Requires `Throttle Web View?`_ preference to be enabled.

Clicking this button will show / hide the *Throttle Web View* on the Throttle Screen.

Note: If the `Throttle Web View?`_ preference is not enabled the button will do nothing.

Layout Switch Button Preferences
""""""""""""""""""""""""""""""""

The following preferences provide options for an optional button on the Action Bar to switch Throttle Screen layouts.

Show Layout Switch button?
'''''''''''''''''''''''''''''''''''

.. image:: ../_static/images/parts/throttle_switch_button.png
   :align: right
   :scale: 50%

|todo|

Show the Throttle Layout Switch button in the Throttle Screen action bar to allow quick changing between to preset Throttle Layouts.

First Screen Layout
'''''''''''''''''''''''''''''''''''

|todo|

Layout Switch Button will switch between this throttle layout and the next preference

Second Screen Layout
'''''''''''''''''''''''''''''''''''

|todo|

Layout Switch Button will switch between the throttle layout in the previous preference and this one

In phone sounds button
""""""""""""""""""""""

.. image:: ../_static/images/parts/in_device_sounds_outline.png
   :align: right
   :scale: 50%

|todo|

Show an action bar button to change the in phone loco sounds options

Show Server Description
"""""""""""""""""""""""

.. image:: ../_static/images/parts/server_description.png
   :align: right
   :scale: 50%

Setting this preference will display the description of the current server on the Action Bar.

Throttle Control Preferences
----------------------------

The following preferences provide options for how the throttle on the Throttle Screen will behave.

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

Show 'Limit Speed' button?
'''''''''''''''''''''''''''''''''''

|todo|

Show a button to temporarily restrict the maximum speed on an individual throttle

'Limit Speed' button
'''''''''''''''''''''''''''''''''''

|todo|

Set the \% of the throttle that the speed will be temporarily limited to

Show 'Pause' button?
'''''''''''''''''''''''''''''''''''

|todo|

Show a button to slow and stop the locomotive, then return to original speed on next press

'Pause' button Rate
'''''''''''''''''''''''''''''''''''

|todo|

Number of milliseconds between speed step changes for the Pause action

'Pause' button Step
'''''''''''''''''''''''''''''''''''

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

Speed button Change Amount (Volume)
'''''''''''''''''''''''''''''''''''

|todo|

How much Volume buttons jump throttle speed

Disable Volume keys?
'''''''''''''''''''''''''''''''''''

|todo|

Disables the hardware Volume keys on the phone/tablet that would otherwise control speed

Volume keys follow touch?
'''''''''''''''''''''''''''''''''''

|todo|

The Volume keys speed control will follow the last touched throttle

Gamepad Preferences
"""""""""""""""""""

|todo|

Gamepad type
'''''''''''''''''''''''''''''''''''

|todo|

Choose the option that best supports your gamepad

See the `Gamepads page <../configuration/gamepads.html>`_ for more information about selecting and using a gamepad.

Test Gamepad settings now!
'''''''''''''''''''''''''''''''''''

|todo|

Allows you to confirm that the chosen setting are working correctly.  The Gamepad Test screen will launch IMMEDIATELY on selection.

Speed button Change Amount (Gamepad)
''''''''''''''''''''''''''''''''''''

|todo|

How much each press of the Gamepad buttons changes the throttle speed

Gamepad Button Click Volume %
'''''''''''''''''''''''''''''''''''

|todo|

Set the volume percent for gamepad button clicks

Speed button Repeat Delay (gamepad)
'''''''''''''''''''''''''''''''''''

|todo|

How long between repeats on Gamepad speed buttons.  Smaller is faster.

Gamepad button action <!-- X -->
'''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Gamepad button action <!-- Y -->
'''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Gamepad button action <!-- A -->
'''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Gamepad button action <!-- B -->
'''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Gamepad button action <!-- Start(Lower) -->
'''''''''''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Gamepad button action <!-- Return(Upper) -->
''''''''''''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Gamepad DPAD Up action
'''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Gamepad DPAD Right action
'''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Gamepad DPAD Down action
'''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Gamepad DPAD Left action
'''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Swap Direction buttons with Screen buttons?
'''''''''''''''''''''''''''''''''''''''''''

|todo|

Temporarily swap the two Gamepad Direction buttons if the Screen Direction buttons are swapped

Enforce Gamepad Testing?
'''''''''''''''''''''''''''''''''''

|todo|

Test each gamepad every time they are connected

Use Simple Test?
'''''''''''''''''''''''''''''''''''

|todo|

Only test that you can reduce speed

ESU MobileControl II Options
""""""""""""""""""""""""""""

|todo|

Device Stop button options
""""""""""""""""""""""""""

|todo|

Stop Button long-press delay
'''''''''''''''''''''''''''''''''''

|todo|

How long for a \'long-press\' of the Stop button.\nA \'long-press\' stops all active throttles; a \'short-press\' pauses the current throttle.\nSmaller is faster.

Enable Short Press
'''''''''''''''''''''''''''''''''''

|todo|

A \'short-press\' pauses the currently controlled locomotive/consist.\nWill revert to original speed when operations resume.

Device side button options
""""""""""""""""""""""""""

|todo|

Top-left button action
'''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Bottom-left button action
'''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Top-right button action
'''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Bottom-right button action
'''''''''''''''''''''''''''''''''''

|todo|

Choose the action when you press the button

Button repeat delay
'''''''''''''''''''''''''''''''''''

|todo|

How long between repeats on device side buttons. Smaller is faster.

Control Knob options
"""""""""""""""""""""""""

|todo|

Control Knob Zero Trim
'''''''''''''''''''''''''''''''''''

|todo|

Set the Control Knob zero trim setting. Smaller is closer to counter-clockwise end-stop position.  Permitted range 0-255.

Direction Change at end-stop
'''''''''''''''''''''''''''''''''''

|todo|

Allow Loco direction to change when control knob at counter-clockwise end-stop position

Show disable Knob button
'''''''''''''''''''''''''''''''''''

|todo|

Allow the control knob to be disabled by an action button on the throttle screen

Additional selected loco Indicator
""""""""""""""""""""""""""""""""""

|todo|

Additional highlight of the Loco Select button based on the selection method

Voice Response Preferences
""""""""""""""""""""""""""

|todo|

Voice Response
'''''''''''''''''''''''''''''''''''

|todo|

When to speak key events and actions using Text to Speech (TTS)

On Gamepad Throttle change
'''''''''''''''''''''''''''''''''''

|todo|

When you select a different throttle on the gamepad

On Gamepad Speeds
'''''''''''''''''''''''''''''''''''

|todo|

When the speed hits certain speeds when using a gamepad

On Gamepad Test start
'''''''''''''''''''''''''''''''''''

|todo|

When the gamepad test screen is launched

On Gamepad Test complete
'''''''''''''''''''''''''''''''''''

|todo|

When the gamepad test screen is finished 

On Gamepad Test key press
'''''''''''''''''''''''''''''''''''

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

In Phone Momentum
'''''''''''''''''''''''''''''''''''

|todo|

Delay (momentum) per step change in milliseconds (0-2000)

Don't clip loco step sounds
'''''''''''''''''''''''''''''''''''

|todo|

Loco step sounds will play till their end when changing step.  Momentum amount (above) becomes a minimum time only.


In Phone Loco Sounds Volume
'''''''''''''''''''''''''''''''''''

|todo|

Volume for Loco engine sounds in the phone (1-100)

In Phone Bell Sounds Volume
'''''''''''''''''''''''''''''''''''

|todo|

Volume for bell sounds in the phone (1-100)

In Phone Horn/Whistle Sounds Volume
'''''''''''''''''''''''''''''''''''

|todo|

Volume for Horn/Whistle sounds in the phone (1-100)

Bell button Latching/Momentary
'''''''''''''''''''''''''''''''''''

|todo|

Bell button is momentary (not latching)?

F1 and F2 activate Bell and Horn?
'''''''''''''''''''''''''''''''''''

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

.. image:: ../_static/images/parts/timer.png
   :align: right
   :scale: 50%


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
