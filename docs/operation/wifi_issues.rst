*******************************************
WiFi Issues
*******************************************

.. meta::
   :description: JMRI Engine Driver Throttle
   :keywords: Engine Driver EngineDriver JMRI manual help wifi 

-------------
Wrong Network
-------------

TBA

---------
Firewalls
---------

TBA


---------------------------------
Using Mobile Data instead of WiFi
---------------------------------

*UPDATE: as of EngineDriver 2.26.115, EngineDriver now handles this situation by "forcing" the local wifi connection. 
There is an "Allow Mobile Data Connection" preference that can be enabled if needed.*

Recent versions of Android have a very confusing "feature", sometimes called "Smart Network Switching", that will ignore a connected WiFi network if that network cannot reach the Internet. 
The network shows as connected, and EngineDriver server discovery works, but clicking on the discovered server or Connect button does not work.

EngineDriver will show a message "Using MOBILE network, not WiFi. check WiFi settings", when this mode is encountered.

Some devices have a setting to turn off this feature, some do not. 
Some provide a notification that "Wi-Fi has no internet access, Tap for options", followed by "This network has no internet access. Stay connected?" that can be used to disable this feature and remain connected to the wifi. 
If you missed the prompt, you can "forget" the network, and reenter your wifi credentials to get the prompt again.

Workaround: If you are unable to turn off the feature, you can enable "Airplane Mode", then enable ONLY WiFi, and then connect your wifi.
