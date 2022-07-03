*******************************************
Frequently Asked Questions
*******************************************
 
.. meta::
   :keywords: FAQ frequently asked questions

.. include:: ../include.rst

.. sidebar::

  .. contents:: On This Page
     :local:
     :depth: 3
    
Connecting - Wifi and WiThrottle
--------------------------------

Q. Why doesn't my Android device automatically connect to my WiFi network?

  A. I have noticed that some older android phones won't automatically reconnect to a network that does not have internet access, and nothing I have been able to do can resolve it.

I have in the past put a shortcut on the homepage to the network settings to make it easy to get there and select the network, before starting ED.

Q. I can't connect to my Server /Railroad

  A1. Check the following:

  * Check that you are connected to a WiFi network
  * Check that you are connected to the same WiFi network as your |WTS|
  * Check that JMRI and its |WTS| feature are started

  A2. Possible Mobile data connection problem

  If |ed| can see the |WTS| but displays an error when you try to connect to it… If you are using a phone with a SIM, and the WiFi network your JMRI server is on does not have internet access. You may have to turn 'mobile data' off on your device.  See `[here] for more information <./wifi_issues.html>`_.

Q. |ed| Connects, but I can't control any locos

  A. Powering the layout on

  Some DCC command stations need you to turn the track power on before you can use it.

  .. note:: 
    :class: note-ed-hidden-title

    See the `Turn Track Power On <../operation/operation.html#turn-track-power-on>`_ notes for more information.

Q. Why doesn't |ed| automatically find my |WTS|?

  I can manually connect to my Server / Railroad by entering an IP address, but it never finds it automatically.

  A1. One reason can be your router doesn't not support the 'Bonjour' protocol. There is not much you can do if this is the case other than trying a different router.

  A2. 4.5ghz and 5ghz. |todo|

Q. If |ed| can't find my Server/Railroad automatically 

  A. Look for the IP address and port in the WiThrottle window in JMRI 

  Type them in the two fields and click :guilabel:`Connect`

Q. Why doesn't |ed| remember the servers I have connected to?

  A. Check the |ed| preferences and make sure the ``Maximum Recent Locos`` preference is not set to zero.

----

Connecting to different servers/railroads
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Q. I want to switch to a different server on the same network. 

  A. You need to exit |ed| and restart.

Q. I want to switch to a different server on a different network. 

  A. You need to exit |ed|, change WiFi networks in the Android settings, then restart |ed|.

----

Save/load preferences for different servers
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can set up different preferences for different server/railroads and have them automatically load when you connect to that |WTS|.
The most common use of this (so far) is to remember the locos relevant to that railroad.  e.g. I run N scale and HO Scale.  When I connect to one of the N Scale layouts I use it shows me my N Scale locos in the recent locos list, but when I connect to one of the HO layouts I use, it shows me the my recently used HO locos.

.. note:: 
  :class: note-ed-hidden-title

  See the `Auto Host Specific Import/Export <../configuration/preferences.html#auto-host-specific-import-export>`_ preference for more information.

Q. What is this **jmri.mstevetodd.com** in the server list?

  A. *jmri.mstevetodd.com* is a demo server, which can be used for testing. It has roster entries, turnouts, routes and an active panel for you to try.

  .. note:: 
    :class: note-ed-hidden-title

    You can use the `Hide Demo Server? <../configuration/preferences.html#hide-demo-server>`_ preference to permanently remove it from the list if you wish.

Q. How do I clear unwanted servers from the list

  A. Swipe right on an entry to remove it.

Selecting locomotives to control
--------------------------------

Q. Why can't I can't see my loco in the roster?

  A. The loco needs to be added to the JMRI roster on your server computer.  Refer to the JMRI documentation to see how.

Q. Why is my loco is not remembered in the recent locos list?

  A1. If the loco is in your roster, check the preference ``Roster in Recent Locos?`` so that locos in the roster will be included in the recent locos list.

  A2. If no locos are remembered (and you have confirmed the preference above) make sure the ``Maximum Recent Locos`` preference is not set to zero.

Q. The JMRI loco list is too long, I can't find my locos easily

  A. You can use the filter option to reduce the list 

|todo|

Q. How do I work with Consists

  A1. On the fly Consists in |ed| 

  |ed| can create consists on-the-fly by simply select multiple locos, one after the other...

  |todo|

  Note: Make sure that the ``Drop Loco before acquire?`` preference is set to 'No'.

  A2. DCC 'Advanced Consists' (CV19)
 
  Note you can't create a DCC 'Advanced Consists' (CV19) with |ed|, but you can control one if it has already been setup.

  |todo|

  Remember that this type of consist can cause problems later if the loco has not been removed from the consist first and you want to control it as an individual loco. 

  A3. JMRI Consists

  |todo|

  Creating consists in JMRI effectively create DCC 'Advanced Consists' (CV19) and appear in the loco list in |ed| much like any other loco. 

Q. I can't create on-the-fly consists?

  A. Make sure that the ``Drop Loco before acquire?`` preference is set to 'No'.

Q. The lights of the locos in my consist are wrong?

  A1. If you use on-the-fly consists, you can control the lights by clicking ``Select`` then click on the ``Edit Lights`` button

  A2. You can control the lights with a Long click on the ``Select`` Loco button, if you set the ``Control consist Lights on long click`` preference.

Q. Can't control my loco?

  A. If you can control the lights but not the motor, check that the loco is not in a 'normal' consist.

Q. I sometimes accidently press the volume keys

  A. You can disable the volume keys in the preferences.

Q. I sometimes accidently press the direction button when changing speed

  A. You can:

    * Disable 'Direction change while moving?' preference (recommended)
    * Increase speed slider/button height
    * Decrease loco and direction button height

Q. No Locomotive Icons appear in the Roster

  A. The Roster List, and Recent Locos List on the Select Loco screen will automatically show icons for your locos only if:

    * The **Web Server** (not just the |WTS|) is running on the JMRI server
    * The loco itself has an icon added for it in the JMRI roster |br|\ OR
    * A locally cached or manually chosen image is available for the loco (see 'Locomotive Icons' on the `Operation screen <../operations/index.html>`_)

Q. Why can't I control 6 locos

  A. only the 'Simple' throttle layout allows for 6 throttles

Changing the appearance of Engine Driver
----------------------------------------

Global changes (Themes)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Q. I want to change the appearance of the app

  A. You can switch between different themes by changing the preference. 

    * The original theme 
    * The high contrast theme. Similar to the original theme, without the textured background with deeper blacks and brighter whites. 
    * The high contrast outline theme. For people who like white text on a black background.
    * The Dark theme. 
    * The Colourful theme.

----

Changing the Throttle screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Q. I want to change the appearance of |T-S|

  A. There are a number of different |T-S| designs/layouts.  Look at the `Operation <../operaion/index.html>`_ screen for details

    * Default / Original /Horizontal
    * Simple  
    * Vertical
    * Vertical Left
    * Vertical Right
    * Big Buttons - Left
    * Horizontal Switching/Shunting
    * Vertical Switching/Shunting
    * Vertical Switching/Shunting Left
    * Vertical Switching/Shunting Right 

    |ed| will automatically reload the throttle sceen after closing the preferences screen. 

Q. I want vertical sliders, not horizontal

  A. See the 'Simple' and 'Vertical' Throttle screen type options above.

Q. I want to control more than one train 

  A. You can control between one and six trains with |ed|, depending on which |T-S| type (see above) you have chosen. Each train can have one or more locomotives in consist. 

     The screen space is shared between throttles, so set the “Number of Throttles” appropriately.

     Note that the different Throttle Screen options (above) support different numbers on throttles.

Q. In want to change the labels of the function buttons that are displayed 

  A1. Change the function button defaults in |ed|, for locos without Roster Entries

  A2. Roster entries include function button labels, and can be changed in JMRI

Q. My locos have different functions but all the Function buttons appear the same for every locomotive 

  A1. There is a Preference “Use default function labels?” which can override the labels from the roster entry.  Confirm that you have not turned it on.

  A2. You need to setup the individual functions for each of your locos in JMRI.

Q. My loco shows the wrong Function labels 

  A. Functions of loco are generally set in the JMRI roster.  |ed| may be showing the functions of a loco with the same address from the Roster.

      This can happen if you entered an address to select the loco rather than selecting from the roster list.

      You can force the default function labels in the preferences.

----

Speed slider VS speed buttons
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Some people find the speed slider difficult to control.

  There are options to:

  * Change the height of slider
  * Add speed buttons to the ends of the slider (with further options to increase the separation)
  * Replace the slider with large speed buttons only.

      (If you are using a gamepad or ESU MCII, then you may like to remove the slider AND the speed buttons.)

Q. I have a small screen Android device.  It doesn't fit well?

  A1. Try the 'Immersive mode' (Full Screen) preference. (see below)

  A2. Reduce the height of the loco select and direction buttons

  A3. Keep the number of locos to 1 or two.

Direction Buttons
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Q. I don't like the direction buttons in that order

  A. If you tend to think that forward should be to the right and reverse to the left, you can change the buttons positions in the preferences.

  You can also change them on the fly.

  Labeling the direction buttons for the directions/conventions of your railroad/railway.

  e.g. North South, West East, Up Down.

  <stuff goes here>


Hiding the title bar and navigation bar
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

Immersive mode (Full Screen)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

Swiping up or Down
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

----

Showing the web page at the bottom of the throttle screen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

See the Web Throttle view 

See the Web Throttle view preference  

<also point to the swipe up option>

Loco selection screen
--------------------------------------------

|todo|

----

Locos in the roster not showing
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|todo|

  A1. check you don't have a filter 

  A2. ???


Changing the connection screen
--------------------------------------------

Q. You can't remove test server by swiping right

  A. you can't remove it with a swipe, but there is a preference to remove it.  

  See the `Hide Demo Server <../configuration/preferences.html#hide-demo-server>`_ preference for more information.

Changing the turnouts screen
--------------------------------------------

|todo|

Conserving power on your phone/tablet
-------------------------------------

Q. My Phone/table runs out of power too quickly

  A. You should

  * Keep the brightness of the device as low as practical
  * Disable Bluetooth and NFC if you are not using them
  * You can also try:

    * Set the preference to dim screen on swipe up.  If you are not using the throttle temporarily (i.e the train does not need any control for a little while), dim the screen until you need it back.
    * Set the preference to dim screen on shake.  If you are not using the throttle temporarily (i.e the train does not need any control for a little while), dim the screen until you need it back.

  If your device has an AMOLED display, theoretically, the High Contrast Outline theme should use less power (though this is unproven).

.. note:: 
  :class: note-ed-hidden-title

  See the :doc:`../configuration/conserving_power` page for more information.
