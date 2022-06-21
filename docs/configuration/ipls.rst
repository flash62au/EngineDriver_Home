*******************************************
In Phone Loco Sounds (IPLS)
*******************************************

.. meta::
   :keywords: virtual sounds IPLS In Phone Loco Sounds

.. include:: ../include.rst


Virtual Sounds / In Phone Loco Sounds (IPLS)
============================================

|ed| can play synchronised locomotive sounds through your Android device/phones or through a BlueTooth speaker connected to it.

To enable In Phone Loco Sounds (IPLS) select an option in `Throttle 1 Loco Sounds <./preferences.html#throttle-1-loco-sounds>`_ or `Throttle 2 Loco Sounds <./preferences.html#throttle-2-loco-sounds>`_ (or both) preferences. Once enabled for either throttle a new menu option will be available from Throttle Screen to make subsequent changes easier: :menuselection:`Menu --> Loco Sounds`

To make it easy to switch sound profiles we recommend enabling the Action Bar button by setting the `In phone sounds button <./preferences#in-phone-sounds-button>`_ preferences: :menuselection:`Menu --> Preferences --> Throttle Screen Action Bar Preferences --> In phone sounds button`

Loco Sounds
-----------

|todo|

Bell, Horn/Whistle
------------------

|todo|

Custom IPLS Files
=================

|todo|

You can add custom IPLS files in the ``../Android/data/jmri.enginedriver/files/`` folder. They will appear in the list of profiles that can be selected in the ``Throttle 1 Loco Sounds`` or ``Throttle 2 Loco Sounds`` preferences.

::

    / sample custom 'In-Phone Loco Sounds' (.ipls) file
    /
    / - the first character of each line is the instruction/sound type
    / - Lines starting with "/" are comments
    / - Avoid additional spaces (it will try to trim leading and trailing spaces) 
    /   i.e don't put a space before or after the colon.
    / - this .ipls file MUST be placed in ../Android/data/jmri.enginedriver/files/
    / - By default, the sound files are expected to be in ../Android/data/jmri.enginedriver/files/
    /   however you can put them in subfolders by prepending the sound file name with <folder name><forward slash>  
    /   e.g. sample/bell_start.mp3     - will look for ../Android/jmri.enginedriver/files/sample/bell_start.mp3
    / - The files used for the inbuilt sounds can be copied from here: https://github.com/flash62au/EngineDriver/tree/master/EngineDriver/src/main/res/raw
    / - Sounds files can be .wav or .mp3 format.  Other formats may usable but are untested.
    / - Each sound is internally limited to one megabyte storage, which represents approximately 5.6 seconds at 44.1kHz stereo
    /
    / n: = name that will appear in the drop lists in Engine Driver
    /
    n:Diesel Loco - 4 steps
    /
    / b0: Bell start sound  b1: Bell loop sound  b2: Bell end sound
    /
    b0:sample/bell_start.mp3
    b1:sample/bell_loop.mp3
    b2:sample/bell_end.mp3
    /
    / h0: Horn/Whistle start sound  h1: Horn/Whistle loop sound  h2: Horn/Whistle end sound
    /
    h0:sample/horn_start.mp3
    h1:sample/horn_loop.mp3
    h2:sample/horn_end.mp3
    /
    / h+: short horn / whistle
    /
    h+:sample/SD40_NathanP3_Short.wav
    /
    / l0: Loco idle  l1:.. l16: Loco steps/notches 
    / - MAX 16 
    / - Not all 16 are required, but there must not be any missing steps between 0 and the last
    /
    l0:sample/diesel_645turbo_idle.mp3
    l1:sample/diesel_645turbo_d1k.wav
    l2:sample/diesel_645turbo_d2.wav
    l3:sample/diesel_645turbo_d3.wav
    l4:sample/diesel_645turbo_d4.mp3
    /
    / l+: Loco Startup Sound   MAX 12 seconds 
    /
    l+:sample/diesel_645turbo_start.mp3

