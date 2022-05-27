******************************************
ESU MobileControl II
******************************************

.. meta::
   :description: JMRI Engine Driver Throttle
   :keywords: Engine Driver EngineDriver JMRI manual help ESU MobileControl MC2 MCII 

----

As well as being able to control speed of the selected throttle with the control knob, it's also possible to switch direction via the zero-position end-stop switch.

Up to three trains can be controlled at once - the train being operated by the control knob is highlighted by the small 'v' in the speed indicator. Switch between operated trains by clicking the appropriate speed indicator. It is also possible to assign one of the device side
buttons to switch to the next operated train - by default, the bottom-right button is assigned to this function.

When assigned to control a train, the Green LED is lit. When no trains are assigned, the Green LED flashes.
In addition, you can use the Stop button to pause the currently operated train, or to stop all controlled trains. A short press of the Stop button (default, less than 1/2 second) pauses operation of the currently controlled train. The Red LED will flash quickly to denote this. On a second press of the Stop button, the currently operated train will resume at the previous set speed. A long press of the Stop button (default, greater than 1/2 second) will stop all controlled trains. The Red LED will flash slowly to denote this. On a second press of the Stop button, all controlled trains will remain stationary and it will be possible to again control the currently selected train.

Whilst in stop mode, the on-screen speed change buttons and bar are disabled for currently stopped throttles. Switching between controlled throttles is also disabled. 

It is possible to configure the device side buttons to perform various actions. The default assignment is as follows:

Top-left
  Increase speed
Bottom-left
  Decrease speed
Top-right
  Toggle direction
Bottom-right
  Select next throttle

These assignments can be modified via the ESU MobileControl II Options page in Preferences.
