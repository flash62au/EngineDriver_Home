*******************************************
Configuration
*******************************************

.. meta::
   :keywords: configuration preferences

.. include:: ../include.rst

.. sidebar::

  .. contents:: On This Page

Configuring Engine Driver
-------------------------

**Engine Driver** is highly configurable.

Most configuration options are found in the ``Preferences`` which is accessed via the overflow menu which is normally three dots (⁞) or three bars (≡).

Some of the many Preferences include:

* You can turn off the ``stop on release`` preference
* You can set a Maximum value and Maximum change% for the throttle sliders. 
* If the throttle slider is too small for your fingers, increase the size. 
* You can set the initial web page for the full-size web panel, or enable the smaller web view on the throttle screen. 
* There are also settings to help maximize the use of your device's smaller screen by hiding items not relevant to you.

Look around in Preferences, there are a huge number of settings to personalize **Engine Driver**, including many more if you enable ``Show Advanced Preferences``.

.. note:: 
  :class: note-ed-hidden-title

   See the `Preferences <./preferences.html>`_ page for a full list of the available preferences.

The **Functions buttons** are changed via the ``Function Buttons`` menu option: :menuselection:`Menu --> Functions Buttons`

Some of the Function button preferences include:

* You can set the default labels and function numbers to display. 
* If you have entered labels for a roster entry in JMRI, these labels will be used for that entry, and can be copied from the dialog (access the menu after selecting a loco). 
* You can remove buttons by blanking out the labels.

.. note:: 
  :class: note-ed-hidden-title

   See the `Function Buttons <./functions.html>`_ page for more information.


Configuring the WiThrottle server
---------------------------------

JMRI
^^^^

* Check your preferences/settings to insure you allow or disallow the control features desired. 
* If you've defined your turnouts/points and routes in a panel file, make sure to specify 'user names' for those you'd like to see listed on your throttle. 
* You can also 'filter' the turnouts shown using the WiThrottle->Filter Controls option in the WiThrottle window.
* Entering roster entries, and defining routes and turnouts on the server will all make your **Engine Driver** throttle more powerful and easier to use (though not required). 
* **Engine Driver** will show additional info if the JMRI Web Server is started (such as roster details and icon images).

DCC++EX WiFi
^^^^^^^^^^^^

Refer to the `developer's instructions <https://dcc-ex.com/advanced-setup/wifi-config.html>`_.

MRC WiFi
^^^^^^^^

For MRC users: David Fuller has provided some `additional setup information <https://enginedriver.mstevetodd.com/sites/enginedriver.mstevetodd.com/files/EngineDriver_App-MRC_Wi-Fi_Module_Settings.pdf>`_.


Digitrax LnWi
^^^^^^^^^^^^^

Refer to the `Digitrax LnWi manufacture's instructions <https://www.digitrax.com/tsd/product/LNWI>`_.

WifiTrax
^^^^^^^^

Refer to the `WifiTrax manufacture's instructions <http://www.wifitrax.com/manuals/hardwareManuals.html>`_.


Engine Driver - Configuration Details
-------------------------------------

For more information on the items above see:

* `Preferences page <./preferences.html>`_
* `Function Buttons page <./functions.html>`_
* `In Phone Loco Sounds page <./ipls.html>`_
* `Gamepads page <./gamepads.html>`_
* `Loco Icons in the Roster page <./loco_icons.html>`_
* `Moving to a new device/phone page <./new_device.html>`_

|todo|

.. toctree::
  :hidden:
  :includehidden:

  setup_wizard
  preferences_index
  functions
  ipls
  gamepads
  loco_icons
  new_device
