*******************************************
WiFi Issues
*******************************************

.. meta::
   :keywords: WiFi 

.. include:: ../include.rst

.. sidebar::

  .. contents:: On This Page
    :local:

Many of the problems that people have with |ed| relate to connection issues.

Below are several common problems.

Wrong Network
-------------

.. todo:: Wrong Network

Recent versions of Android have a very confusing *feature*, sometimes called 'Smart Network Switching', that will ignore a connected WiFi network if that network cannot reach the Internet. 

This can cause problems if you sometimes use your device to connect to the internet on one network, but you |WTS| is on a different network that does not have an internet connection. 

Some devices have a setting to turn off this feature, some do not. 
Some provide a notification that "Wi-Fi has no internet access, Tap for options", followed by "This network has no internet access. Stay connected?" that can be used to disable this feature and remain connected to the WiFi. 
If you missed the prompt, you can 'forget' the network, and reenter your WiFi credentials to get the prompt again.

Firewalls
---------

.. todo:: Firewalls

Your PC's firewall software can prevent |ed| from connecting. You may need to add an exception in your firewall software for JMRI or disable the firewall to allow |ed| to connect.


Using Mobile Data instead of WiFi
---------------------------------

.. note:: 
  :class: note-ed
  
  *UPDATE: as of EngineDriver 2.26.115, EngineDriver now handles this situation by "forcing" the local WiFi connection.  There is an* ``Allow Mobile Data Connection`` *preference that can be enabled if needed.*

Recent versions of Android have a very confusing *feature*, sometimes called 'Smart Network Switching', that will ignore a connected WiFi network if that network cannot reach the Internet. 
The network shows as connected, and EngineDriver server discovery works, but clicking on the discovered server or Connect button does not work.

EngineDriver will show a message "Using MOBILE network, not WiFi. check WiFi settings", when this mode is encountered.

Some devices have a setting to turn off this feature, some do not. 
Some provide a notification that "Wi-Fi has no internet access, Tap for options", followed by "This network has no internet access. Stay connected?" that can be used to disable this feature and remain connected to the WiFi. 
If you missed the prompt, you can "forget" the network, and reenter your WiFi credentials to get the prompt again.

Workaround: If you are unable to turn off the feature, you can enable 'Airplane Mode', then enable ONLY WiFi, and then connect your WiFi.


Disconnections
--------------

.. todo:: Disconnections


|ed| and/or the Android device can occasionally lose the connection even after it successfully connected.  There can be a lot of causes.  If ED does lose connection it will buzz, vibrate and take you to *Reconnecting Screen*.   It will repeatedly and indefinitely attempt to reconnect.

* Other networks on the same channel
* distance to router / location of the router
* Too Many Devices Are Connected
* objects in the way (particularly metal objects)
* Interference  (Other electrical devices close to the phone or the router )

If JMRI does not receive any feedback from your device/phone within a configured period, JMRI will stop all the locos you have selected on you device/phone.

* Disable haptic Alert


.. note:: 
  :class: note-ed-hidden-title
  
  See `Feedback on Disconnect preference on the Preferences page <../configuration/preferences.html#feedback-on-disconnect>`_ to disable the audible and haptic warnings.
