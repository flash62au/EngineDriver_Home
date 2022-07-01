*******************************************
Function Buttons
*******************************************

.. include:: ../include.rst

----

|todo|

DCC Functions
=============

|todo|

* Roster
* DCC Addresses

* Latching
* Non Latching

* default function buttons

Linking Functions to IPLS buttons
=================================

|todo|

Functions and Gamepads
======================

|todo|

Advanced Consist Function Mapping
=================================


|todo|

Which style of rules to follow in a consist when function buttons are pressed.

Note: If 'Use Default function labels' is enabled, 'Special...' will also apply to the lead (or only) loco.


You can now arrange the default function labels on ED any way you want, and as long as the equivalent function has a similar name it doesn't matter what function number it is, it will activate it correctly.

I have added two new options to the menu "Special Exact" and "Special Partial"
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


