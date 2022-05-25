*******************************************
Gamepads
*******************************************

.. meta::
   :description: JMRI Engine Driver Throttle
   :keywords: Engine Driver EngineDriver JMRI manual help gamepad

.. |br| raw:: html

   <br />

----------------------------------------------
Connecting your Gamepad to your Android Device
----------------------------------------------

The following instructions work for the **mocute** and **MagicSeeR1** gamepads. 
Other devices require similar steps, but the mechanism to change the ``mode`` may be different. 

* Turn on
  
  * For the **mocute** gamepads
  
    * On the gamepad, the small button is Start/Power. Press for a couple seconds until LED comes on. 

  * For the **MagicSeeR1** gamepads (Mode B)

    * There is a dedicated on/off switch. 

* On your **Android device** go to the settings, then Bluetooth, and make sure Bluetooth is turned ON. 
* Now click ``More Settings``. Within a few seconds a new device should appear in the ``Available devices`` section. (The name of the device may make it apparent that it is the gamepad, but it may just be a string of hexadecimal numbers.) 
* Select the new device. Many devices will be paired at this point, but if it asks for a pairing code try ``0000`` or ``1234`` (check the instructions that came with the gamepad.) 
* After pairing you should see an item in the Notifications regarding the gamepad. Click that item and make sure that “Show virtual keyboard” is ON. 
* Set the mode of the gamepad:

  * For the **mocute** gamepads (MTK mode)
  
    * Turn your gamepad OFF by holding the Start/Power button for about 5 seconds until the LED goes out and stays out. 
    * Move the slide switch on the side to the ``GAME`` position (towards the joystick). 
    * Hold down the button specified in your gamepad instructions for MTK mode. Typically this is the ``Y`` button. While still holding that button down, press the Start/Power button until the LED turns on. Release the buttons as soon as the LED turns on. |br|\ |br|\ This configuration procedure should only be required once. In the future your gamepad should be in MTK mode when you turn it on. |br|\  *(This not true of the MagicSeeR1 which must be set every time you turn it on)* |br|\ |br|\
  
  * For the **MagicSeeR1** gamepads (Mode B)
  
    * Turn the device on by moving the slide switch on the side to the ``ON`` position
    * Wait for the gamepad to connect to Android device (the LED will stop blinking)
    * Hold down the ``Mode`` buton and press the ``B`` button. |br|\ |br|\ **This configuration procedure which must be done every time you turn it on**

We have found that some gamepads work well in **iCade** mode as well. Feel free to experiment. To use iCade mode, follow the steps above but use the button your instructions specify for iCade (typically “X”). 


--------------------------------------
Running Engine Driver with the Gamepad
--------------------------------------

* Set up the gamepad and connect to the Android device (see above)
* Start Engine Driver
* Connect to a wiThrottle server 
* Select a loco as normal and return to the Throttle page. 
* In the Engine Driver preferences
 
  * Select a gamepad type. |br|\ In the Gamepad section of Engine Driver's Preferences, select a gamepad corresponding to the gamepad mode you configured on the device (above).

    * For the **mocute** gamepads we recommend ``MTK-rotate`` for MKT mode, and ``iCade+DPAD-rotate`` for iCade mode. 
    * For the **MagicSeeR1** you must use ``MagicSeeR1 Android-Game B``.

  * You can optionally change what the gamepad buttons do. (`See Gamepad Configuration <../configuration/gamepads.html>`_ for details.)

* On the Throtttle Screen

  * When you press any of the buttons on the gamepad for the first time, a test page will appear.  Press all four DPad buttons in turn and the Four main buttons to pass the test, and return to the throttle page.

    * Pressing ``Skip`` will complete the test and allow you to use the gamepad, even if it is not functioning correctly.  (e.g. The mode is incorrect)
    * Pressing ``Reset`` will reset all the gamepads you have connected, and will force you back to the test screen when attempt to use them again.

  * By default, The DPAD (joystick) on the gamepad will control throttle up, down and direction. 
  * By default, The four individual Buttons on the gamepad will control functions F0, F1, F2 and STOP for the selected throttle. 
  * If you have engines assigned to more than one Engine Driver throttle, by default a short press of the ``Start`` Button will move the gamepad to the next assigned throttle. If you have changed the Preferences for the ``Start`` Button Action to ``ESTOP``, then a short press will set the speed for all your Engine Driver throttles to zero. 
  * If the ``Select`` Button is present on your gamepad, by default, pressing it will move the gamepad to the next assigned throttle.
  * Engine Driver's on-screen buttons continue to function as before. Use them to add or drop locos, and to access any additional function buttons. 

-------------------------
Remapping gamepad buttons
-------------------------

All the buttons of the gamepad that can be accessed by Engine Driver can be remapped to perform most of the features and functions of the Engine Driver Throttle Screen.

`See Gamepad Configuration <../configuration/gamepads.html>`_ for details.

-----------------
Multiple gamepads
-----------------

Engine Driver supports up to 4 gamepads at the same time.  All the gamepads must be of the same type.

As you connect each gamepad, you will be force to go to the gamepad test screen.  The new gamepad will be automatically assigned to the next throttle that does not have a gamepad assigned to it.

An indicator ``1``, ``2`` etc. will show near the throttle speed to indicate which throttle each gamepad is controlling.  Only one gamepad can be active on a single throttle at one time.

----

-----------------
Sample gamepads 
-----------------

^^^^^^^^^^^^^^^
Tested gamepads
^^^^^^^^^^^^^^^

These we have had the most success with…

**Mocute ...**

.. image:: ../_static/images/gamepads/bt_controller1.jpg
   :scale: 50 %

They are available from a variety of different sellers on ebay and elsewhere. 
Their quality is not brilliant which is reflected in the price, so don't expect a long life from them.

**MagicSeeR1**

.. image:: ../_static/images/gamepads/bt_controller2.jpg
   :scale: 50 %

This has been successful, **but you need to re-select 'mode B' every time you switch it on.**  
These seem to be slightly better quality than the one above, but are more expensive.

**Flydigi Wee 2**

This has been successful.

**Utopia 360**

This has been successful with the 'Android C' mode.

**DIY Arduino ESP32 + keypad + Rotary Encoder**

This is a DIY gamepad with a keypad and physical dial.

See https://github.com/flash62au/WiTcontroller for details.

**Normal Keyboard**

This has been successful.  See below for the keystroke meanings when using a keyboard.

Note: In the gamepad test screen, just select 'Skip' to use the keyboard.


^^^^^^^^^^^^^^^^^^^^^^^^
Not Recommended gamepads
^^^^^^^^^^^^^^^^^^^^^^^^

These work, but have issues which make them not recommended. 

TBA

^^^^^^^^^^^^^^^^^^^^
Unsupported gamepads
^^^^^^^^^^^^^^^^^^^^

**VR Box**

Support for this type of gamepad was removed from engine driver.

.. image:: ../_static/images/gamepads/vrbox.png
   :scale: 70 %


----

-----------------
Keyboard Commands
-----------------

For use when ``Keyboard`` is selected as the gamepad type:

* 'Up' or 'Page Up' or '+' or '=' = Increase Speed
* 'Media Next' = Increase Speed * 2
* 'Down' or 'Page Down' or '-' = Decrease Speed
* 'Media Previous' = Decrease Speed * 2
* 'Home' or 'X' = Stop
* Left or '[' = Reverse (Forward if buttons swapped in preferences)
* Right or ']' = Forward (Ahead) (Reverse if buttons swapped in preferences)
* 'D' = Direction - Toggle Forward/Reverse
* 'N' = Next Throttle
* 'End' or 'Z' = All stop |br|\
* F00 - F28 = Function |br|\ Must be 'F' followed by two digits |br|\  or 'F11' followed by two 'F' button equivalents F10=0, F1-F9=1-9
* '0'-'9' = Functions 0-9 |br|\ Without a preceding 'F', 'S' or 'L' |br|\ or 'F10' - 'F9'  F10=0, F1-F9=1-9 |br|\
* S000 - S100 = Speed |br|\ Must be 'S' followed by three digits |br|\  or 'F12' followed by two 'F' button equivalents F10=0, F1-F9=1-9 |br|\
* 'L' = Limit Speed
* 'P' = Pause Speed
* In Phone Loco Sounds (IPLS)  
  * 'B' = Bell 
  * 'H' = Horn / Whistle 
  * Shift + 'H' = Short Horn 
  * 'M' or 'Volume Mute' = Mute IPLS
* T0 - T5 = Specify a throttle for next command |br|\ Must be 'T' followed by one digit |br|\ or 'Esc' followed by two 'F' button equivalents F10=0, F1-F9=1-9 |br|\ The following command will sent to the specified throttle regardless of the currently selected gamepad throttle.

All other keyCodes are ignored.

These same keycodes are used by the DIY Arduino controllers.