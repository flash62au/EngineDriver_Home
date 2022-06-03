*******************************************
WiFi Issues
*******************************************

.. meta::
   :keywords: WiFi 

.. include:: ../include.rst

.. sidebar::

  .. contents:: On This Page

Many of the problems that people have with |ed| relate to connection issues.

Below are several common problems.

Wrong Network
-------------

|todo|

Recent versions of Android have a very confusing *feature*, sometimes called 'Smart Network Switching', that will ignore a connected WiFi network if that network cannot reach the Internet. 

This can cause problems if you sometimes use your device to connect to the internet on one network, but you WiThrottle server is on a different network that does not have an internet connection. 

Some devices have a setting to turn off this feature, some do not. 
Some provide a notification that "Wi-Fi has no internet access, Tap for options", followed by "This network has no internet access. Stay connected?" that can be used to disable this feature and remain connected to the WiFi. 
If you missed the prompt, you can 'forget' the network, and reenter your WiFi credentials to get the prompt again.

Firewalls
---------

|todo|

Your PC's firewall software can prevent **Engine Driver** from connecting. You may need to add an exception in your firewall software for JMRI or disable the firewall to allow **Engine Driver** to connect.


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

|todo|

* Disable haptic Alert

