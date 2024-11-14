*******************************************
User Interface
*******************************************

.. meta::
   :keywords: user interface UI

.. include:: ../include.rst

.. sidebar::

  .. contents:: On This Page
     :local:
     :depth: 4

----

The user interface for |ED| is described and explained in these pages as 'screens'.  There are several '`Main Screens`_' which you will routinely interact with and and larger number of '`Secondary / Support Screens`_' that will interact with infrequently. 

There are also some settings that impact all of the screens which described towards the end of this page:

* Theme
* Localisation 


Main Screens
-------------

There are four main screens:

* `Connection Screen`_
* `Throttle Screen`_
* `Turnouts/Points Screen`_
* `Routes Screen`_

----

Connection Screen
^^^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/connect.png
   :align: right

This screen is the first screen you normally see when starting |ED|. 

It allows you choose which |WTS| to connect to, which you must do to control your trains.

There are three ways you can select a |WTS| to connect to:

* IP Address and Port
* Discovered Servers
* Recent servers

Once you select a server the |T-S| will be automatically displayed.

If you only ever connect to one |WTS| you can effectively bypass this screen by enabling the `Auto-Connect to WiThrottle Server? <../configuration/preferences.html#auto-connect-to-withrottle-server>`_ preference.

.. note:: 
  :class: note-ed-hidden-title

  See :doc:`wifi_issues` for more assistance with connection difficulties.

Connection Method Options
"""""""""""""""""""""""""

IP Address and Port
'''''''''''''''''''

  Enter the IP address or URI of the server in the first field, and the port in the second field, then click :guilabel:`Connect`. |ed| will attempt to connect to it, and the |T-S| will be displayed.

Discovered Servers
''''''''''''''''''

  This is the most common way to connect.

  Your |WTS| will attempt to broadcast its details so that apps like |ED| can automatically find it.  If |ED| does find it, it will be listed here.

  To connect to any |WTS| in this list, simply click on the row.  |ed| will attempt to connect to it, and the |T-S| will be displayed.

Recent servers
''''''''''''''

  To connect to any |WTS| in this list, simply click on the row.  |ed| will attempt to connect to it.  If successful the |T-S| will be displayed.

  Note that, just because it is in this list, it does not mean that you can connect to it now. It only means that you have successfully connected to it in the past.

Action Bar (Connection Screen)
""""""""""""""""""""""""""""""

The Action Bar appears at the top of all screens. It will show different information and different buttons depending on a\) the particular screen and b\) preferences you have set.

In the |C-S| the Action Bar only displays:

* The app name (|ed|)

See the `Action Bar`_ section of this page for more information.

Overflow Menu (Connection Screen)
"""""""""""""""""""""""""""""""""

The *Overflow Menu* (or simply '*Menu*') appears in the Action Bar at the top of most of the `main screens <../operation/interface.html#main-screens>`_ is normally three dots (⁞) or three bars (≡).
It will show different options depending on a) the particular screen, b) preferences you have set and c) the state of certain elements in the app.

Specific to the |C-S|, the Overflow Menu can display:

* `Preferences <../configuration/preferences.html>`_
* `View Log <../operation/interface.html#view-log-screen>`_
* `Exit <../operation/operation.html#exiting-engine-driver>`_
* `About <../operation/interface.html#about-screen>`_

.. note:: 
   :class: note-ed-hidden-title

   See the `Overflow Menu`_  section for more information.

----

Throttle Screen
^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/throttle_vertical_outline.png
   :scale: 8 %
   :align: right

The |T-S| has two distinct areas:

* The Action Bar
* One or more Throttle Areas

There are also some settings that impact the whole |T-S| which described towards the end of this section:

* Background
* Immersive Mode (Full Screen)
* Swipe Up / Down
* Accelerometer (Shake)  
 
The |T-S| allows you to control:

- Access common functions from the Action Bar and Menu
- Control one or more locos

The |T-S| contains between 1 and 6 Throttle areas depending on the Throttle layout chosen and the number of throttles for that layout (only some allow this to be changed).  


Throttle Area
""""""""""""""""""""""""""""""""""""

Each Throttle on the |T-S| will display different information and buttons depending on the ``Throttle Screen Layout`` in the  `Throttle Screen Layout <../configuration/preferences.html#throttle-screen-layout>`_ preference.

Each *Throttle Area* allows you to:

* Select and release locos 
* Control the speed and direction of your trains
* Activate DCC decoder functions like the light, bell, horn 
* Activate Virtual (IPLS) Sounds (bell, horn, short horn) (if enabled)

Loco Select Button
''''''''''''''''''''''''''''''''

   The loco :guilabel:`Select` button in the Throttle Area allows to select or release locos for that particular Throttle.  Click on the button and you will be taken to the Select Loco screen.

   Once you have selected a loco, the label on the button change to the DCC Address(s) or the Roster name(s) of the Loco depending on how you select the loco in the |LS-S|, and if you have the enabled the `Loco Address instead of Name? <../preferences.html#loco-address-instead-of-name>`_ preference.

   When the button is displaying DCC Address(s) or the Roster name(s), click on the button again and you will be taken to the Select Loco screen where you can de-select the loco(s), select additional locos to make a consist / multiple unit train, edit the locos in the consist, or edit the lights of the locos in the consist / multiple unit.

   .. note:: 
      :class: note-ed-hidden-title

      See the `Operation <../operation/index.html#selecting-releasing-locos>`_ page for more information.

Speed indicator
''''''''''''''''''''''''''''''''

   The *Speed Indicator* or *Speed* area of each throttle of the |T-S| indicates the throttle amount/setting (rather than the actual speed of the locos controlled by the the throttle).
   
   Depending on the `Speed Units Preference <../configuration/preferences.html#speed-units>`_ the upper value show will be different: 

   .. list-table::
    :width: 100%
    :widths: 60 20 20
    :header-rows: 1

    * - Speed Unit Setting
      - Low value
      - High Value
    * - Percent 0 - 100% 
      - 0
      - 100
    * - Auto Speed steps 
      - ?
      - ?
    * - 8 steps 
      - 0
      - 8
    * - 10 steps 
      - 0
      - 10
    * - 14 steps 
      - 0
      - 14
    * - 28 steps 
      - 0
      - 28
    * - 128 steps
      - 0
      - 128

   Also, if one of the Shunting/Switching layouts is selected, the high number will be negative ('-') when reversed (e.g. -100 - 0 - 100)

   The *Speed Indicator* area also can show:

   * Volume indicator
   * Gamepad Indicator
   * Direction indicator (Shunting/Switching Layouts only)

   *Volume Indicator*

   A 'V' will be shown in the *Speed Indicator* area to indicate which throttle is being controlled by the hardware volume buttons.
   Touch another *Speed Indicator* to change which Throttle the Hardware Volume buttons control.

   *Gamepad Indicator*
   
   A number ('1','2', etc.) will be shown in the *Speed Indicator* area to indicate which throttle is being controlled by the each connected gamepad.  Set one of the gamepad to allow you to switch throttle it controls.

   *Direction Indicator*

   If one of the Shunting/Switching layouts is selected, a triangle symbol will be shown to indicate direction (pointing Up for forward, and down for reverse).

   .. note:: 
      :class: note-ed-hidden-title

      See the Throttle Control Preferences section of the `Speed Units preference <../configuration/preferences.html#speed-units>`_ for a information on changing the ``Speed Units`` options.

Speed Slider Area
'''''''''''''''''
   .. image:: ../_static/images/parts/slider_horizontal.png
      :scale: 100 %

   The Throttle areas can be configured with a *Speed Slider*.  (All Throttle Screen layouts except the 'Big Button' layouts include sliders by default.) Dragging you finger along the slider will increase or decrease the speed of the loco(s) selected for the that Throttle. Pressing and holding your finger at one spot on the slider will cause |ED| to slowly increase or decrease the speed of the loco(s) selected for that Throttle till it gets to that point.
   
   Depending on the ``Throttle Screen Layout`` chosen in the  `Throttle Screen Layout <../configuration/preferences.html#throttle-screen-layout>`_ preference, all sliders on the |T-S| will be either:
   
   * one-directional (0% - 100%) [#PCT]_  |br|\ or 
   * bi-directional (-100% - 0 - +100%) |br| |br|

   Bi-directional sliders are useful for when you are switching/shunting. i.e. moving your locos backwards and forwards a lot.

   Several preferences can change the appearance or actions of the *Speed Slider*\:

   * `Increase Slider/Speed Height? <../configuration/preferences.html#increase-slider-speed-height>`_ |br| When set, this preference will show a taller Slider, or Speed buttons, for throttles
   * `Throttle Speed Slider Margin <../configuration/preferences.html#throttle-speed-slider-margin>`_ |br| When set, this changes the space between either the edge of the screen and the ends of the Slider, or if the Speed Buttons are enabled, the edge of the Speed Buttons and the ends of the Slider. Specific in pixels haw far to offset
   * `Hide Speed Slider? <../configuration/preferences.html#hide-speed-slider>`_ |br| When this preferences is set, |ed| will not show speed slider, use speed buttons instead
   * `Tick Marks on Speed Sliders? <../configuration/preferences.html#tick-marks-on-speed-sliders>`_ |br| When this preferences is set, Engine Driver will show tick marks on the background of the Speed Sliders
   * `Switching throttle Dead Zone <../configuration/preferences.html#switching-throttle-dead-zone>`_ |br| When this preferences is set, Engine Driver will set the size of the dead zone, or detent, on the slider of the Switching/Shunting |T-S|
   * `Stop Button Vertical Margins <../configuration/preferences.html#stop-button-vertical-margins>`_ |br| When this preferences is set, Engine Driver will add the entered number of pixels to offset margins of the stop button from the speed buttons and bottom of screen

    .. [#PCT] The actual amounts shown in the *Speed Indicator* will depend on the ``Speed Units`` chosen in the  `Speed Units preference <../configuration/preferences.html#speed-units>`_.

Stop Button
''''''''''''''''''''''''''''''''

   .. image:: ../_static/images/parts/stop_button_horizontal.png
      :scale: 80 %

  Clicking the ``Stop`` button of a throttle will the loco or consists / multiple unit controlled by that throttle.  If the locos have momentum configured in the decoded it/they will slow then stop. 

   .. note:: 
      :class: note-ed-hidden-title

      See the `Emergeny Stop Action Bar button <emergency stop button>`_ for information on stopping locos immediately, overriding the momentum setting.

Speed Buttons
''''''''''''''''''''''''''''''''

   .. image:: ../_static/images/parts/speed_buttons_horizontal.png
      :scale: 100 %

   The Throttles may optionally be configured have simple buttons that allow you to increase or decrease the loco's speed in pre-defined steps. The buttons are displayed at either end of the *speed sliders*.
   
   When enabled:
   
   * the :guilabel:`++` will **increase** the throttle speed by the `Speed Button Change Amount <../configuration/preferences.html#speed-button-change-amount>`_.
   * the :guilabel:`--` will **decrease** the throttle speed by the `Speed Button Change Amount <../configuration/preferences.html#speed-button-change-amount>`_.

   For the Horizontal Sliders only, The position of these buttons in relation to the speed sliders (the space between), can be altered with the :ref:`Speed Slider Margin <configuration/preferences:throttle speed slider margin>` preference.

   .. note:: 
     :class: note-ed-hidden-title

     See the :ref:`Display Speed Buttons? <configuration/preferences:display speed buttons?>` preference for more information on enabling these buttons.

     See the :ref:`Speed Button Change Amount <configuration/preferences:speed button change amount>` preference for information on the abount that 

Direction Buttons Area
'''''''''''''''''''''''

   .. image:: ../_static/images/parts/direction_buttons.png
      :scale: 80 %

   Each Throttle on the |T-S| will display :guilabel:`Forward` and :guilabel:`Reverse` direction buttons, depending on the ``Throttle Screen Layout`` in the  :ref:`Throttle Screen Layout <configuration/preferences:throttle screen layout>` preference.  'Shunting/Switching' layouts do not show the direction buttons.

   Change direction while moving preference.

   .. note:: 
     :class: note-ed-hidden-title

     See the :ref:`Direction change while moving? <configuration/preferences:direction change while moving?>`  and :ref:`Stop on Direction change? <configuration/preferences:stop on direction change?>` preferences for information on preferences which alter when the buttons are available and the way the they work.


Function Buttons Scroll Area
''''''''''''''''''''''''''''

   The *Function Buttons Scroll Area* will show form 0 (zero) to 26 function buttons depending on a number of factors. Each button will show either:

   * Labels provided from the roster, which can be individually specified for each loco in the roster
   * The default labels for |ed|  (which can be changed)

   The *Function Button area* can also show:

   * IPLS buttons  (In Phone Loco Sounds)
   * Pause
   * Limit Speed

   The *Function Buttons Scroll Area* is shown by default on all Throttle Screen layouts except ``Simple``.  It can be enable fot the ``Simple`` layout

   .. note:: 
     :class: note-ed-hidden-title

     See the :ref:`Function Button Area Size <configuration/preferences:function buttons area size>` preference for information on how to show the *Function Button Scroll Area* on the simple layout.

DCC Function buttons
''''''''''''''''''''

.. todo:: DCC Function buttons

   DCC Function Buttons are displayed here.  If there are too many to display in the screen area allocated, then the area becomes scrollable (without scroll bars) so that they can all be viewed and pressed as needed.  
   
   All throttle layouts other than the 'Simple' layout show a *Function Buttons Scroll Area* by default.  For the 'Simple' layout it must be enable in the preferences if required.

   Will show from 0 (zero) to 26 DCC function buttons, depending on a number of factors. Each button will show either:

   * Labels provided from the roster, which can be individually specified for each loco in the roster
   * The default labels for |ed|  (which can be changed)

   
   If the loco (or first loco of a consist/multiple unit) was selected from the |WTS| roster, then (by default) the number of functions and labels on the buttons will be whatever is configured for that loco in the |WTS|.  This is also trun if the loco is selected from the Recent Locos list or the Recent Consist/Multiple Units list.
   
   If the loco (or first loco of a consist/multiple unit) was added by entering its DCC Address, then the number of functions and labels on the buttons will be whatever is configured in |ED| in the Default Functions.

   The behaviour of the Function Buttons for locos selected from the |WTS| roster can be overridden with the :ref:`Use default function labels? <configuration/preferences:use default function labels?>` preference.  If this is enabled, the locos selected from the |WTS| roster will also show the Default Functions labels.

   Clicking on any button will instruct the loco to activate that DCC Function in the loco.  By default this is only sent to the Lead loco, however this can be overridden in a number of differnt ways.

   .. note:: 
     :class: note-ed-hidden-title

     See the `Function Defaults Screen <Function Defaults Screen>`_ section for more information on configuring the labels and number of *default function* buttons.

     See the :doc:`Function Buttons <../configuration/functions>` page for more information on the DCC Function buttons.

     For labels from Roster Entries you need to edit the Function buttons in the |WTS|, or configure |ed| to use the default labels.

Pause and Limit Speed buttons
'''''''''''''''''''''''''''''

.. todo:: Pause and Limit Speed buttons

   The *Function Button area* can also show:
   * Pause
   * Limit Speed

  These are optional buttons 


   .. note:: 
     :class: note-ed-hidden-title

     See the :ref:`'Limit Speed' & 'Pause' button Preferences <configuration/preferences:'Limit Speed' & 'Pause' button Preferences>` section on the Preferences page for more information on these buttons.


In Phone Loco Sounds buttons 
''''''''''''''''''''''''''''

.. todo:: In Phone Loco Sounds buttons 

   The *Function Button area* can also show the IPLS buttons  (In Phone Loco Sounds)

  These are optional buttons

   .. note:: 
     :class: note-ed-hidden-title

     See the `In Phone Loco Sounds (IPLS) <../configuration/ipls.html>`_ page for more information on the IPLS buttons


Web View Area (Throttle Web View)
"""""""""""""""""""""""""""""""""
   
.. todo:: Web View Area (Throttle Web View)

Shows a web browser in the lower half of the |T-S|.

Your JMRI Layout panels can be displayed here if you have configured them in JMRI. 

Anything that can be shown in the `Web View Screen <./operation/interface.html#web-view-screen>`_ can equally be shown here, just in a smaller space.

.. note:: 
     :class: note-ed-hidden-title

     see preference

     see initial page preference

     different to the main `Web View Screen <./operation/interface.html#web-view-screen>`_ including a different preference to set the initial page.

     see increase size

Action Bar (Throttle Screen)
""""""""""""""""""""""""""""

.. image:: ../_static/images/parts/action_bar.png
  :align: right
  :scale: 33%

The Action Bar appears at the top of all screens. It will show different information and different buttons depending on a\) the particular screen and b\) preferences you have set.

In the |T-S| the Action Bar can display:

* The app name (|ed|)
* Optionally configured information:

  * Fast Clock
  * Children's Timer Status and Countdown
  * Full Screen or Action Bar Only left/right swipe
  * |WTS| Name

* Optionally configured buttons:

  * Emergency Stop  (EStop)
  * Track Power
  * Flashlight
  * Throttle Web View
  * Throttle Layout Switching
  * In Phone Loco Sound
  * Children's Timer

.. note:: 
   :class: note-ed-hidden-title

   The optional buttons are enabled via the :menuselection:`Menu --> Preferences --> Throttle Screen Status Row Preferences`.  
    
   See the `Action Bar`_ section of this page for more information.


Overflow Menu (Throttle Screen)
"""""""""""""""""""""""""""""""

.. image:: ../_static/images/parts/menu_throttle.png
  :align: right
  :scale: 33%

The *Overflow Menu* (or simply '*Menu*') appears in the Action Bar at the top of most of the `main screens <../operation/interface.html#main-screens>`_ is normally three dots (⁞) or three bars (≡).
It will show different options depending on a) the particular screen, b) preferences you have set and c) the state of certain elements in the app.

Specific to the |T-S|, the Overflow Menu can display:

* `Turnouts/Points <../operation/interface.html#turnouts-points-screen>`_ (All except the *Turnout/Points Screen* only)
* `Routes <../operation/interface.html#routes-screen>`_ (All except the |R-S| only)
* `Power <../operation/operation.html#turn-track-power-on>`_
* `Preferences <../configuration/preferences.html>`_
* `Function Defaults <../operation/interface.html#function-defaults-screen>`_ (|T-S| only)
* Gamepads (|T-S| only)

  * `Gamepad Test 1 <../operation/interface.html#gamepad-test-screen>`_
  * `Gamepad Test ... <../operation/interface.html#gamepad-test-screen>`_

* `Loco Sounds <../operation/interface.html#in-phone-loco-sounds-screen>`_ (|T-S| only)
* `View Log <../operation/interface.html#view-log-screen>`_
* `Exit <../operation/operation.html#exiting-engine-driver>`_
* `About <../operation/interface.html#about-screen>`_

.. note:: 
   :class: note-ed-hidden-title

   See the `Overflow Menu`_  section for more information.

.. image:: ../_static/images/screenshots/background_fill.png
  :align: right
  :scale: 12%

Background
""""""""""

|ed| can show a background image of your choosing on the |T-S|.  Any image/photo on your device/phone can be used.

.. note:: 
   :class: note-ed-hidden-title

   See the  `Background Images section <../configuration/preferences.html#background-image-preferences>`_  of the preferences for more information on how to select a background image.


Immersive Mode (Full Screen)
""""""""""""""""""""""""""""

.. todo:: Immersive Mode (Full Screen)

Swipe Left / Right (From Throttle)
""""""""""""""""""""""""""""""""""

Swiping Left from the |T-S| will take you to the `Routes Screen`_, unless it has been disabled in the preferences

Swiping Right from the |T-S| will take you to the `Turnouts/Points Screen`_, unless it has been disabled in the preferences

By default, you can Left/Right Swipe from any part of the screen, but this can be changed to just the Action Bar in the preferences. This can be useful if Left/Right swipes in the |WV-S| and *Throttle Web view* causes problems. 

.. note:: 
   :class: note-ed-hidden-title

   See the `Left right swipe preferences <./configuration/preferences.html#left-right-swipe-preferences>`_ for information on how to enable and disable which screens are in the Left / Right swipe sequence.

   See the `Disable Full Screen Swipe prefernce <configuration/preferences.html#disable-full-screen-swipe>`_ to enable or disable the Swipe Action Bar only option.

Swipe Up / Down
"""""""""""""""

.. todo:: Swipe Up / Down

Accelerometer (Shake)  
"""""""""""""""""""""

.. todo:: Accelerometer (Shake)  

----

Turnouts/Points Screen
^^^^^^^^^^^^^^^^^^^^^^

.. todo:: Turnouts/Points Screen

Accessed from any of the main screens by the :menuselection:`Menu --> Turnouts`` or :menuselection:`Menu --> Points` or by swiping right from the Throttle Screen if enabled in the Left with the ``Swipe through Turnouts?`` or ``Swipe through Points?`` preference: :menuselection:`Menu --> Preferences --> Left/Right Swipe Preferences --> Swipe through Turnouts/Points`

This screen allows you to display all Turnouts/Points that have been defined in JMRI.

Turnouts/Points can be changed from Closed to Thrown and vice versa be pressing on either the ``Closed`` or ``Thrown`` buttons

**List from WiThrottle**

* Throw
* CLose

**Entry**

.. todo:: Turnouts/Points Screen - Entry

**Filter by location**

The 'Turnout/Points List' can be filtered.  The filtering relies on the idea that the first part of every Turnout/Point name is a 'Location', followed by a common separator, then the actual name for the Turnout/Point name.  The 'filter' then allows you to select one of those locations and |ed| can just show the Turnout/Points at the 'Location'.

The `Location Delimiter <../configuration/preferences.html#location-delimiter>`_ preference allows you to set the character that marks the end of the Location portion of Turnout/Point and Route names.  By default it is a colon (":") but any character can be used.

**Hide if no user name? preference**


Action Bar (Turnouts/Points Screen)
"""""""""""""""""""""""""""""""""""

.. image:: ../_static/images/parts/action_bar.png
  :align: right
  :scale: 33%

The Action Bar appears at the top of all screens. It will show different information and different buttons depending on a\) the particular screen and b\) preferences you have set.

In the |TP-S| the Action Bar can display:

* The app name (|ed|)
* Optionally configured information:

  * Fast Clock
  * Full Screen or Action Bar Only left/right swipe
  * |WTS| Name

* Optionally configured buttons:

  * Emergency Stop  (EStop)
  * Track Power
  * Flashlight

.. note:: 
   :class: note-ed-hidden-title

   The optional buttons are enabled via the :menuselection:`Menu --> Preferences --> Throttle Screen Status Row Preferences`.  
    
   See the `Action Bar`_ section of this page for more information.

Overflow Menu (Turnouts/Points Screen)
""""""""""""""""""""""""""""""""""""""

The *Overflow Menu* (or simply '*Menu*') appears in the Action Bar at the top of most of the `main screens <../operation/interface.html#main-screens>`_ is normally three dots (⁞) or three bars (≡).
It will show different options depending on a) the particular screen, b) preferences you have set and c) the state of certain elements in the app.

Specific to the *Turnouts/Points  Screen*, the Overflow Menu can display:

* `Throttle <../operation/interface.html#throttle-screen>`_ (All except the |T-S| only)
* `Routes <../operation/interface.html#routes-screen>`_ (All except the |R-S| only)
* `Power <../operation/operation.html#turn-track-power-on>`_
* `Preferences <../configuration/preferences.html>`_
* `View Log <../operation/interface.html#view-log-screen>`_
* `Exit <../operation/operation.html#exiting-engine-driver>`_
* `About <../operation/interface.html#about-screen>`_

.. note:: 
   :class: note-ed-hidden-title

   See the `Overflow Menu`_  section for more information.

Swipe Left / Right (From Turnouts/Points)
"""""""""""""""""""""""""""""""""""""""""

Swiping Left from the |TP-S| will take you to the `Throttle Screen`_, unless it has been disabled in the preferences

Swiping Right from the |T-S| will take you to the `Web View Screen`_, unless it has been disabled in the preferences

By default, you can Left/Right Swipe from any part of the screen, but this can be changed to just the Action Bar in the preferences. This can be useful if Left/Right swipes in the |WV-S| and *Throttle Web view* causes problems. 

.. note:: 
   :class: note-ed-hidden-title

   See the `Left right swipe preferences <./configuration/preferences.html#left-right-swipe-preferences>`_ for information on how to enable and disable which screens are in the Left / Right swipe sequence.

   See the `Disable Full Screen Swipe prefernce <configuration/preferences.html#disable-full-screen-swipe>`_ to enable or disable the Swipe Action Bar only option.

----

Routes Screen
^^^^^^^^^^^^^

.. todo:: Routes Screen

Accessed from any of the main screens by the menu :menuselection:`Menu --> Routes` or by swiping left from the Throttle Screen if enabled in the Left with the ``Swipe through Routes?`` preference: :menuselection:`Menu --> Preferences --> Left/Right Swipe Preferences --> Swipe through Routes`

This screen allows you to display all Routes that have been defined in JMRI or DCC-EX EX-CommandStation.

**Enter**

.. todo:: Routes Screen - Enter

**List**

.. todo:: Routes Screen - List

**Filter by location**

The 'Routes List' can be filtered.  The filtering relies on the idea that the first part of every Route name is a 'Location', followed by a common separator, then the actual name for the Route name.  The 'filter' then allows you to select one of those locations and |ed| can just show the Routes at the 'Location'.

The `Location Delimiter <../configuration/preferences.html#location-delimiter>`_ preference allows you to set the character that marks the end of the Location portion of Turnout/Point and Route names.  By default it is a colon (":") but any character can be used.

Hide Sys Route Names? preference 

Hide if no user name? preference

.. todo:: Routes Screen - Filter

Action Bar (Routes Screen)
""""""""""""""""""""""""""

.. image:: ../_static/images/parts/action_bar.png
  :align: right
  :scale: 33%

The Action Bar appears at the top of all screens. It will show different information and different buttons depending on a\) the particular screen and b\) preferences you have set.

In the |R-S| the Action Bar can display:

* The app name (|ed|)
* Optionally configured information:

  * Fast Clock
  * Full Screen or Action Bar Only left/right swipe
  * |WTS| Name

* Optionally configured buttons:

  * Emergency Stop  (EStop)
  * Track Power

.. note:: 
   :class: note-ed-hidden-title

   The optional buttons are enabled via the :menuselection:`Menu --> Preferences --> Throttle Screen Status Row Preferences`.  
    
   See `Action Bar`_ section of this page for more information.

Overflow Menu (Routes Screen)
"""""""""""""""""""""""""""""

The *Overflow Menu* (or simply '*Menu*') appears in the Action Bar at the top of most of the `main screens <../operation/interface.html#main-screens>`_ is normally three dots (⁞) or three bars (≡).
It will show different options depending on a) the particular screen, b) preferences you have set and c) the state of certain elements in the app.

Specific to the |R-S|, the Overflow Menu can display:

* `Throttle <../operation/interface.html#throttle-screen>`_ (All except the |T-S| only)
* `Turnouts/Points <../operation/interface.html#turnouts-points-screen>`_ (All except the *Turnout/Points Screen* only)
* `Power <../operation/operation.html#turn-track-power-on>`_
* `Preferences <../configuration/preferences.html>`_
* `View Log <../operation/interface.html#view-log-screen>`_
* `Exit <../operation/operation.html#exiting-engine-driver>`_
* `About <../operation/interface.html#about-screen>`_

.. note:: 
   :class: note-ed-hidden-title

   See the `Overflow Menu`_  section for more information.


Swipe Left / Right (From Routes)
""""""""""""""""""""""""""""""""

Swiping Left from the |R-S| will take you to the `Web View Screen`_, unless it has been disabled in the preferences

Swiping Right from the |R-S| will take you to the `Throttle Screen`_, unless it has been disabled in the preferences

By default, you can Left/Right Swipe from any part of the screen, but this can be changed to just the Action Bar in the preferences. This can be useful if Left/Right swipes in the |WV-S| and *Throttle Web view* causes problems. 

.. note:: 
   :class: note-ed-hidden-title

   See the `Left right swipe preferences <./configuration/preferences.html#left-right-swipe-preferences>`_ for information on how to enable and disable which screens are in the Left / Right swipe sequence.

   See the `Disable Full Screen Swipe prefernce <configuration/preferences.html#disable-full-screen-swipe>`_ to enable or disable the Swipe Action Bar only option.

----

Web View Screen
^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/web_view_screen.png
  :align: right
  :scale: 12%

.. image:: ../_static/images/screenshots/web_view_screen2.png
  :align: right
  :scale: 12%

.. todo:: Web View Screen

Accessed from any of the main screens by the menu :menuselection:`Menu --> Web` or by swiping left or right twice from the |T-S| if enabled in the Left with the ``Swipe through Web?`` preference: :menuselection:`Menu --> Preferences --> Left/Right Swipe Preferences --> Swipe through Web`
It can also be accessed, if the ``Screen orientation`` preference is set to ``Auto Web``, by rotating the Android Device/Phone.

This screen displays a web browser interface that lets you view any web page. Normally this will be a web page on your JMRI server. 

From the JMRI web server you can view and interact with additional features of JMRI.  The menu at the top right of the web panel screen allows you to further display:

* Rosters
* Operations
* Trains
* Tables
* Turnouts/Points
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
* Any URL in a full screen.  This is in addition to being able to display your JMRI layout panel in a small section of the main |T-S|.

Tap on any of the Open Windows to expand its view.  You can then resize the panel by pinching and zooming.  It is sometimes useful to rotate your device to landscape mode, so as to better view your layout.

Action Bar (Web View Screen)
""""""""""""""""""""""""""""

.. image:: ../_static/images/parts/action_bar.png
  :align: right
  :scale: 33%

The Action Bar appears at the top of all screens. It will show different information and different buttons depending on a\) the particular screen and b\) preferences you have set.

In the |WV-S| the Action Bar can display:

* The app name (|ed|)
* Optionally configured information:

  * Fast Clock
  * Full Screen or Action Bar Only left/right swipe
  * |WTS| Name

* Optionally configured buttons:

  * Emergency Stop  (EStop)
  * Track Power

.. note:: 
   :class: note-ed-hidden-title

   The optional buttons are enabled via the :menuselection:`Menu --> Preferences --> Throttle Screen Status Row Preferences`.  
    
   See `Action Bar`_ section of this page for more information.

Overflow Menu (Web View Screen)
"""""""""""""""""""""""""""""""

The *Overflow Menu* (or simply '*Menu*') appears in the Action Bar at the top of most of the `main screens <../operation/interface.html#main-screens>`_ is normally three dots (⁞) or three bars (≡).
It will show different options depending on a) the particular screen, b) preferences you have set and c) the state of certain elements in the app.

Specific to the |WV-S|, the Overflow Menu can display:

* `Throttle <../operation/interface.html#throttle-screen>`_ (All except the |T-S| only)
* `Turnouts/Points <../operation/interface.html#turnouts-points-screen>`_ (All except the *Turnout/Points Screen* only)
* `Routes <../operation/interface.html#routes-screen>`_ (All except the |R-S| only)
* `Power <../operation/operation.html#turn-track-power-on>`_
* `Preferences <../configuration/preferences.html>`_
* `View Log <../operation/interface.html#view-log-screen>`_
* `Exit <../operation/operation.html#exiting-engine-driver>`_
* `About <../operation/interface.html#about-screen>`_

.. note:: 
   :class: note-ed-hidden-title

   See the `Overflow Menu`_  section for more information.

Swipe Left / Right (Web View Screen)
""""""""""""""""""""""""""""""""""""

.. todo:: Swipe Left / Right (Web View Screen)


Secondary / Support Screens
-------------------------------

The follow additional screens will be shown at different times and for various reasons: 

* `Intro/Setup Wizard Screen`_
* `Loco Select Screen`_
* `Consist Edit Screen`_
* `Consist Lights Edit Screen`_
* `Power Screen`_
* `Preferences Screen`_
* `In Phone Loco Sounds Screen`_
* `Function Defaults Screen`_
* `Gamepad Test Screen`_
* `View Log Screen`_
* `About Screen`_
* `Reconnecting Screen`_

----

Intro/Setup Wizard Screen
^^^^^^^^^^^^^^^^^^^^^^^^^

The *Setup Wizard* will start automatically the first time you run |ed| after you install it.  It sets some basic preferences and asks for the necessary permissions.  These preferences can be subsequently be changed use the : :menuselection:`Menu --> Preferences`, or by re-running the wizard, which can only be done from the menu on the |C-S|.

.. note:: 
   :class: note-ed-hidden-title

   See the  `Setup wizard page <../operation/setup_wizard.html>`_  for more information.

----

Loco Select Screen
^^^^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/select_roster_existing_consist.png
  :align: right
  :scale: 12%

The |LS-S| allows you add locos to a (one of) throttle on the |T-S|.  It also provides access to the additional screens for 'Editing the Consist', 'Editing Lights' and editing the 'In Phone Locos Sounds'.

The |LS-S| is only shown when you click a :guilabel:`Select` button on the |T-S|.

Not that the :guilabel:`Select` button will should the Address(es) or the Name(s) of a Loco or Consist/Multiple Unit Train only the first loco is selected.  Click on the button will (while it is in this state) will again take to this screen to allow to you add additional Locos to the Consist/Multiple Unit Train, or make other changes to the  Consist/Multiple Unit Train.

Selection Method
""""""""""""""""

There are four ways you can choose a loco for the Throttle.  Select one of the radio buttons depending on how you want to the choose the loco:

* DCC Address
* Server Roster
* Recent Locos
* Recent Consists

Select by DCC Address 
"""""""""""""""""""""

.. todo:: Select by DCC Address

Shown if you select ``DCC Address`` in the `Selection Method`_.

You can enter the loco's DCC address (verify short or long), and press :guilabel:`Acquire` to select the loco.  You will then be taken back to the |T-S| with that loco selected.

Select from Sever Roster
""""""""""""""""""""""""

.. todo:: Select from Sever Roster

Shown if you select ``Server Roster`` in the `Selection Method`_.

If the loco you want to control is in the list, simply click on it and you will be taken back to the |T-S| with that loco selected.

For this to be possible, the Loco you want to control needs to be in the roster of the |WTS|.  Not all |WTS| support rosters.  Refer to the JMRI documentation or your |WTS| device's documentation for creating a roster.

  Filter

  Icons

  Icons - adding a local image

  Long Press to see details... (and add icon)

Select from Recent Locos List
"""""""""""""""""""""""""""""

.. todo:: Select from Recent Locos List

Shown if you select ``Recent Locos`` in the `Selection Method`_.

|ed| remembers the last 10 locos that you have selected. (That number can be increased or decreased with `Maximum Recent Locos <../configuration/preferences.html#maximum-recent-locos>`_ preference.)

If the loco you want to control to is in the list, simply click on it and you will be taken back to the |T-S| with that loco selected.

  Icons - From Roster

  Long Press to see details...

  Swipe to remove entry...

Select from Recent Consists List
""""""""""""""""""""""""""""""""

.. todo:: Select from Recent Consists List

Shown if you select ``Recent Consists`` in the `Selection Method`_.

Selecting a Consist / Multiple Unit in the Recent Consists list will automatically add all the remembered locos, including their facing.

  Swipe to remove entry...

Select Loco On Screen Buttons
"""""""""""""""""""""""""""""

Acquire
'''''''

  Shown if you select ``DCC Address`` in the `Selection Method`_.

  After you enter a loco's DCC address you press :guilabel:`Acquire` to select the loco.  You will then be taken back to the |T-S| with that loco selected.

Release
'''''''

  Shown if you have one or locos already selected (acquired) for that throttle.

  Clicking this button will release all the locos currently controlled by the throttle.

Edit Order & Facing
'''''''''''''''''''

  Shown if you have one or locos already selected (acquired) for that throttle.

  Clicking this button will show the `<Consist Edit Screen>`_.

Edit Lights
'''''''''''

  Shown if you have one or locos already selected (acquired) for that throttle.

  Clicking this button will show the `<Consist Lights Edit Screen>`_.

Loco Sounds
''''''''''''

  Shown if you have one or locos already selected (acquired) for that throttle.

  Clicking this button will show `<In Phone Loco Sounds Screen>`_.

----

Consist Edit Screen
^^^^^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/consist_edit2.png
  :align: right
  :scale: 12%


.. todo:: Consist Edit Screen

Shown if you add a second, or subsequent, loco to a throttle via the :guilabel:`Select` button, or if you click on the :guilabel:`Edit Order & Facing` button on the *Select Loco Screen* (which will only be available if you have already acquired more than one loco on the throttle.)

|br|

|br|

Lead Loco
"""""""""

.. todo:: Lead Loco

Trailing Loco
"""""""""""""

.. todo:: Trailing Loco

Consist Top
"""""""""""

.. todo:: Consist Top

* Change Facing


----

Consist Lights Edit Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/consist_lights_edit2.png
  :align: right
  :scale: 12%

.. todo:: Consist Lights Edit Screen

* Unknown
* Follow Fn Btn
* Off

|br|

|br|

|br|

----

Power Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/power.png
  :align: right
  :scale: 12%

Accessed from any of the main screen via : :menuselection:`Menu --> Preferences --> Left/Right Swipe Preferences --> Power` or from the Action Bar if enabled with the `Layout Power button? preference <./configuration/preferences.html#layout-power-button>`_ : :menuselection:`Menu --> Preferences --> Throttle Screen Action Bar Preferences --> Layout Power button?`.

This screen allows you to toggle the state of track power to your layout.

* When the button is **Green**, it indicates that track power is 'On'.
* When the button is **Red**, it indicates that track power is 'Off'.
* When the button is **Amber**, it indicates that track power state is unknown.
* Pressing a **Green** button will cause the button to be changed to **Red** and the track power will be turned 'Off'.
* Pressing a **Red** button or **Amber** button will cause the button to be changed to **Green** and the track power will be turned 'On'.

----

Preferences Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Accessed from any of the main screens via :menuselection:`Menu --> Preferences`.

This screen allows you to personalise  |ed| for how you want it to use it.

.. note:: 
   :class: note-ed-hidden-title

   See the `Preferences page <../configuration/preferences.html>`_ for details on the preferences that can be set.

|br|

|br|

|br|

----

In Phone Loco Sounds Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/ipls_screen.png
  :align: right
  :scale: 12%

.. todo:: In Phone Loco Sounds Screen

Accessed from |T-S| by the :menuselection:`Menu --> Loco Sounds` or from the Status Bar if enabled with the `In phone sounds button <./configuration/preferences.html#in-phone-sounds-button>`_ preference.

|br|

|br|

|br|


----

Function Defaults Screen
^^^^^^^^^^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/function_defaults.png
  :align: right
  :scale: 12%

.. todo:: Function Defaults Screen

Accessed from the menu on the |T-S| as :menuselection:`Menu --> Function Defaults`.

|br|


|br|


----

DCC-EX Function Settings Screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. todo:: DCC-EX Function Settings Screen

Accessed from the menu on the |T-S| as :menuselection:`Menu --> DCC-EX Function Settings`.

----

DCC-EX Screen
^^^^^^^^^^^^^

.. todo:: DCC-EX Screen

Accessed from the menu on the |T-S| as :menuselection:`Menu --> DCC-EX`.

----

Gamepad Test Screen
^^^^^^^^^^^^^^^^^^^

.. todo:: Gamepad Test Screen

Accessed from the |T-S| via the :menuselection:`Menu --> Gamepads -> Gamepad Test X`. (where 'X' is the number of the gamepad.)

|br|

|br|


----

View Log Screen
^^^^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/log_view.png
  :align: right
  :scale: 12%

.. todo:: View Log Screen

Accessed from any of the main screens via :menuselection:`Menu --> View Log`.

This screen allows you to view the internal Engine Driver log of events.
This is sometimes useful for analysing problems.

The option to `Start recording to file` creates a user-accessible file that can be sent to the |ed| app developers or the `Groups.io <https://groups.io/g/jmriusers/topics>`_ help group to assist you in resolving a problem.
The file will be located on your mobile phone at:
Internal storage ``/Android/data/jmri.enginedriver/files`` |br|\ and will be named something like: ``logcat9999999999999.txt``

Enable the ??? preference to include the timestamp on each line of the log.

----

About Screen
^^^^^^^^^^^^

.. image:: ../_static/images/screenshots/about.png
  :align: right
  :scale: 12%

.. todo:: About Screen

This screen displays 

* Information about |ed| 
* Information about the |WTS| it is currently connected to (if any)
* A page of basic information about |ed|


----

Reconnecting Screen
^^^^^^^^^^^^^^^^^^^

This screen displays if |ed| has not been able to communicate with the |WTS| within a specified time.

.. todo:: Reconnecting Screen

Common Elements and Features
----------------------------

This section describes some of the elements and features that appear throughout or affect the entire |ed| app.

* `Theme / Styles`_
* `Localisation`_
* `Action Bar`_
* `Overflow Menu`_ (the Menu)

----

Theme / Styles
^^^^^^^^^^^^^^

Themes provide different colours and textures to the buttons, backgrounds, sliders etc. for all the screens in |ed|.  i.e. It changes the appearance of the entire app.

There are five themes to choose from:

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
      - High contrast theme 
    * - .. image:: ../_static/images/screenshots/throttle_horizontal_outline_theme.png
          :scale: 8%
      - High contrast
    * - .. image:: ../_static/images/screenshots/throttle_horizontal_dark_theme.png
          :scale: 8%
      - Dark theme
    * - .. image:: ../_static/images/screenshots/throttle_horizontal_colorful_theme.png
          :scale: 8%
      - Colourful theme

.. note:: 
   :class: note-ed-hidden-title

   See the `Theme / Style preference <../configuration/preferences.html#theme-style>`_ on the preferences page for more information.

----

Localisation
^^^^^^^^^^^^

Changing the *Localisation* primarily changes the language used in the menus, buttons and messages throughout |ED|.

Supported localisations are:

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

   See the `Localisation preference <../configuration/preferences.html#Localisation>`_ on the Preferences page for more information.

----

Action Bar
^^^^^^^^^^

.. image:: ../_static/images/parts/action_bar.png
   :align: right
   :scale: 50%

The Action Bar appears at the top of all screens. It will show different information and different buttons depending on a\) the particular screen and b\) preferences you have set.

The Action Bar can display:

* The app name (|ed|)
* Optionally configured information:

  * Fast Clock
  * Children's Timer Status and Countdown
  * Full Screen or Action Bar Only left/right swipe
  * |WTS| Name

* Optionally configured buttons:

  * Emergency Stop  (EStop)
  * Track Power
  * Flashlight
  * Throttle Web View
  * Throttle Layout Switching
  * In Phone Loco Sound
  * Children's Timer

The optional buttons are enabled and configured via the corresponding preferences in the `Throttle Screen Action Bar <../configuration/preferences.html#throttle-screen-action-bar-preferences>`_ preference group.  (Other than the Children's Timer which is configured in the `Children's Timer <../configuration/preferences.html#children-s-timer-preferences>`_ preference group.)

Emergency Stop Button
"""""""""""""""""""""

.. image:: ../_static/images/parts/estop.png
   :align: right
   :scale: 50%

The *Emergency Stop* Action Bar button is enabled with the `Emergency Stop button? <../configuration/preferences.html#emergency-stop-button>`_ preference.

Clicking this button will attempt to quickly stop all locos controlled by the device / phone.  Locos controlled by other people/devices are not stopped.

Track Power Button
""""""""""""""""""

.. image:: ../_static/images/parts/power_green.png
   :align: right
   :scale: 50%

The *Track Power* Action Bar button is enabled with the `Layout Power button? <../configuration/preferences.html#layout-power-button>`_ preference.

*Track Power*, when pressed will turn on/off the power to the track.  The colour of the button will change colour:

* 'Amber' = unknown state
* 'Red' = Power is Off
* 'Green' = Power is On

Flashlight Button
"""""""""""""""""

.. image:: ../_static/images/parts/flashlight_on.png
   :align: right
   :scale: 50%

The *Flashlight* Action Bar button is enabled with the `Flashlight button? <../configuration/preferences.html#flashlight-button>`_ preference.

*Flashlight*, when pressed will turn on/off the Device's camera light.

The device / phone must have a camera to be able to use this feature.

Throttle Web View Button
""""""""""""""""""""""""

.. image:: ../_static/images/parts/web_view.png
   :align: right
   :scale: 50%

The *Throttle Web View* Action Bar button is enabled with the `Throttle Web View button? <../configuration/preferences.html#throttle-web-view-button>`_ preference.

*Throttle Web View*, when pressed will show or hide the `Throttle Web View <../operation/interface.html#web-view-area-throttle-web-view>`_ panel on the |T-S|.

Note: the `Throttle Web View? <../configuration/preferences.html#throttle-web-view>` preference must be enabled for this to have an effect.

Layout Switch Button
""""""""""""""""""""

.. image:: ../_static/images/parts/throttle_switch_button.png
   :align: right
   :scale: 50%

.. todo:: Layout Switch Button

The *Layout Switch* Action Bar button is enabled with the `Show Layout Switch button <../configuration/preferences.html#show-layout-switch-button>`_ preference.

The *Layout Switch* buttons, when pressed ...


In Phone Loco Sound Button
""""""""""""""""""""""""""

.. todo:: In Phone Loco Sound Button

.. image:: ../_static/images/parts/in_device_sounds_outline.png
   :align: right
   :scale: 50%

The *In Phone Loco Sounds* Action Bar button is enabled with the `In Phone sounbds Button <../configuration/preferences.html#in-phone-sounds-button>`_ preference.

*In Phone Loco Sounds*, when clicked ...

Children's Timer Button
"""""""""""""""""""""""

.. image:: ../_static/images/parts/timer.png
   :align: right
   :scale: 50%

The *Children's Timer Button* Action Bar button is enabled with the `Show Timer Button? <../configuration/preferences.html#show-timer-button>`_ preference.

The *Children's Timer Button*, when pressed will activate the Timer for the preset time period.

.. note:: 
   :class: note-ed-hidden-title

   See the `Children's Timer section <../operation/advanced.html#children-s-timer>`_ of the Advance Operation page for more information.

Fast Clock
""""""""""

.. image:: ../_static/images/parts/fast_clock.png
   :align: right
   :scale: 50%

.. todo:: Fast Clock

The *Fast Clock* Action Bar button is enabled with the `Fast Clock Display <../configuration/preferences.html#fast-clock-display>`_ preference.

.. note:: 
   :class: note-ed-hidden-title

   See `JMRI's Fast Clock page <https://www.jmri.org/help/en/package/jmri/jmrit/simpleclock/SimpleClockFrame.shtml>`_ for information on how to set up a Fast Clock.

|br|

Children's Timer Status and Countdown
"""""""""""""""""""""""""""""""""""""

.. image:: ../_static/images/parts/childrens_timer_countdown.png
   :align: right
   :scale: 50%

.. todo:: Children's Timer Status and Countdown

.. note:: 
   :class: note-ed-hidden-title

   See the `Children's Timer part <../operation/advanced.html#children-s-timer>`_ of the Advance Operation page for more information.

|br|

Full Screen or Action Bar Only left/right swipe
"""""""""""""""""""""""""""""""""""""""""""""""

.. todo:: Full Screen or Action Bar Only left/right swipe

WiThrottle Server Name
""""""""""""""""""""""

.. image:: ../_static/images/parts/action_bar_server_name.png
   :align: right
   :scale: 50%

.. todo:: WiThrottle Server Name

|br|

|br|


----

Overflow Menu
^^^^^^^^^^^^^

.. image:: ../_static/images/parts/menu_throttle.png
  :align: right
  :scale: 50%

The *Overflow Menu* (or simply '*Menu*') appears in the Action Bar at the top of most of the `main screens <../operation/interface.html#main-screens>`_ is normally three dots (⁞) or three bars (≡).
It will show different options depending on a) the particular screen, b) preferences you have set and c) the state of certain elements in the app.

The Overflow Menu can display:

* `Intro/Setup Wizard <../operation/interface.html#intro-setup-wizard-screen>`_ (|C-S| only)
* `Clear Recent List <../operation/interface.html#connection-screen>`_ (|C-S| only)
* `Throttle <../operation/interface.html#throttle-screen>`_ (All except the |T-S| only)
* `Turnouts/Points <../operation/interface.html#turnouts-points-screen>`_ (All except the *Turnout/Points Screen* only)
* `Routes <../operation/interface.html#routes-screen>`_ (All except the |R-S| only)
* `Power <../operation/operation.html#turn-track-power-on>`_
* `Preferences <../configuration/preferences.html>`_
* `Function Defaults <../operation/interface.html#function-defaults-screen>`_ (|T-S| only)
* Gamepads (|T-S| only)

  * `Gamepad Test 1 <../operation/interface.html#gamepad-test-screen>`_
  * `Gamepad Test ... <../operation/interface.html#gamepad-test-screen>`_

* `Loco Sounds <../operation/interface.html#in-phone-loco-sounds-screen>`_ (|T-S| only)
* `View Log <../operation/interface.html#view-log-screen>`_
* `Exit <../operation/operation.html#exiting-engine-driver>`_
* `About <../operation/interface.html#about-screen>`_
