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

To make it easy to switch sound profiles we recommend enabling the Action Bar button by setting the `In phone sounds button <./preferences.html#in-phone-sounds-button>`_ preferences: :menuselection:`Menu --> Preferences --> Throttle Screen Action Bar Preferences --> In phone sounds button`

Loco Sounds
-----------

There is built in Support for a number of different type of locos:

* Steam - 4 in-built profiles
* Diesel - 3 in-built profiles
* Plus you can create you own Custom profiles (see below)

Each IPLS Profile has a different number of speed steps. As the loco speed increases or decreases to a certain point a different sound will repeatedly play.  |ed| can't tell the actual speed of your loco, only the throttle setting.  This is most apparent when the loco has momentum configured in the decoder.  There is a preference that allows you to approximate the momentum of your loco for the IPLS in |ed| and an option to not clip the sounds (which enforces a minimum delay) These can be altered with the `In Phone Momentum <../configuration/preferences.html#in-phone-momentum>`_ and the `Don't clip loco step sounds <../configuration/preferences.html#don-t-clip-loco-step-sounds>`_ preferences.

The volume of the Loco Sounds, the Bell Sounds and the Horn/Whistle sound can be altered independently with the `In Phone Loco Sounds Volume <../configuration/preferences.html#in-phone-loco-sounds-volume>`_, the `In Phone Bell Sounds Volume <../configuration/preferences.html#in-phone-bell-sounds-volume>`_ and the `In Phone Horn/Whistle Sounds Volume <../configuration/preferences.html#in-phone-horn-whistle-sounds-volume>`_ preferences.

See `In Phone Loco Sounds (IPLS) <../operation/operation.html#virtual-sounds-in-phone-loco-sounds-ipls>`_ for details on how to activate and use the In Phone Loco sounds.

Bell, Horn/Whistle
------------------

.. todo:: Bell, Horn/Whistle

The Bell and Horn/Whistle (long) can also be configureated to be activated by the DCC Function buttons (F1 and F2) if the `F1 and F2 activate Bell and Horn? <../configuration/preferences.html#f1-and-f2-activate-bell-and-horn>`_ preference is set.

See `In Phone Loco Sounds (IPLS) <../operation/operation.html#virtual-sounds-in-phone-loco-sounds-ipls>`_ for details on how to activate and us the In Phone Loco sounds.


Custom .ipls Files
==================

You can add custom IPLS files in the ``../Android/data/jmri.enginedriver/files/`` folder of you android device. They will appear in the list of profiles that can be selected in the ``Throttle 1 Loco Sounds`` or ``Throttle 2 Loco Sounds`` preferences.

To create a custom .ipls you need to have at least the following files:

* an .ipls file (which is a text file of instructions that you create)
* an engine idle sound
* at least one engine running sound (up to 16)

Optionally you can also have:

* An Engine start-up sound
* Bell sounds
* Horn/Whistle sounds

In the case of the Bell and Horn/Whistle sounds you can optionally include start-up and end sounds.


The .ipls file, which you will need to create, includes the instructions on which sounds to use in which circumstances, along with the name for this .ipls that will appear in the drop down lists.

.ipls File Format
-----------------

The first character of each line is the instruction/sound type.

Lines starting with **"/"** are comments.

*Avoid additional spaces* i.e don't put a space before or after the colon. (ED will try to trim any leading and trailing spaces, but best to avoid them.)

**n:** - Mandatory = name that will appear in the drop lists in Engine Driver

**b0:** - Optional = Bell start sound  (optional even if the b1: sound is included) |BR|
**b1:** - Optional = Bell loop sound |BR|
**b2:** - Optional = Bell end sound  (optional even if the b1: sound is included)

**h0:** - Optional = Horn/Whistle start sound  (optional even if the h1: sound is included) |BR|
**h1:** - Optional = Horn/Whistle loop sound |BR|
**h2:** - Optional = Horn/Whistle end sound  (optional even if the h1: sound is included)

**h+:** - Optional = short horn / whistle

**l0:** - Mandatory = Loco idle |BR|
**l1:** - Mandatory = loco running, low speed |BR|
**l2:** - Optional = loco running, next speed |BR|
**l3:** - Optional = loco running, etc. |BR|
**\.\.** |BR|
**l15:** - Optional = loco running, etc. |BR|
**l16:** - Optional = loco running, etc. 

   Maximum of 16 steps |BR|
   Not all 16 are required, but there must not be any missing steps between 0 and the last provided step

**l+:** - Optional = Loco Start-up Sound   *MAX 12 seconds* 

Sounds files can be .wav or .mp3 format.  Other formats may usable but are untested.

Each sound is internally limited to one megabyte storage, which represents approximately 5.6 seconds at 44.1kHz stereo, however all sounds have a time limit maximum of approximately 12 seconds.

By default, the sound files are expected to be in ``../Android/data/jmri.enginedriver/files/`` (i.e the same folder the .ips file is in) however you can put them in subfolders by prepending the sound file name with ``<folder name><forward slash>``. 
e.g. **sample/bell_start.mp3**     - will look for **../Android/jmri.enginedriver/files/sample/bell_start.mp3**


Sample .ipls
------------

The `sample files are available here <../_static/ipls/sample.zip>`_ as a compressed zip file.  To use it extract the files, including the subfolder to ``../Android/data/jmri.enginedriver/files/`` on your Android device.

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

----

Sourcing sound files to use in custom .ipls
-------------------------------------------

Sourcing suitable sound files can be difficult. Sounds files for decoders can generally be converted to a suitable format, but as these are usually proprietary in nature so I advise against doing so unless they are clearly open source.

`Zimo has a large collection of sound files <http://www.zimo.at/web2010/sound/tableindex_EN.htm>`_, many of which are described as 'Free' (the ones with .zip files), which are suitable to be used to create .ipls, though the legalities of doing so for this purpose are unclear.