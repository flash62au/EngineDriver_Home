************************
Loco Icons in the Roster
************************

.. meta::
   :keywords: loco roster icons images

.. include:: ../include.rst

----

The **Roster List**, and **Recent Locos List** on the Select Loco screen will automatically show icons for your locos only if:

* The **Web Server** (not just the |WTS|) is running on the JMRI server
* The loco itself has an icon added for it in the JMRI roster |br|\ OR
* A locally cached or manually chosen image is available for the loco (see below)
* For the **Recent Locos list**, the loco was originally selected from a roster and the loco had an icon. (i.e. Not entered as a DCC Address)

**For WiThrottle servers that do support a roster but don't support Locomotive Icons**  (e.g. DCC++EX)

There are three ways to load & store your Locomotive Icon Image in Engine Driver 2.32.142 and above.

1. **Automatically from your existing JMRI Roster & Media**
  
  * Start JMRI and capture and load your images into JMRI Roster & Media panel as normal
  * Start the |WTS|.
  * Start the Web Server.
  * Connect |ed| to JMRI |WTS| Discovered Server 'My JMRI Railroad' or type in the IP address : Port# 
  * Click ``Select`` and load your Locos then ``Release`` and repeat until you've loaded all the locomotives you require with Icons into a throttle. 
 
  These Loco Icons will automatically be saved/cached on the Android device/phone in a new '/Android/data/jmri.enginedriver/files/recent_engine_list/**recent_engine_list**' folder for you.

  Requirements for this to work:

    * Have identical names (from JMRI Roster ID to DCC++EX EXRAIL Roster ID)  example ID;    "PE 1225"
    * Have image icons displayed for the locomotives

2. **Manually entered directly into your Android Engine Driver folder**
  
  * Capture then rename the image exactly like the Roster ID name in JMRI & EXRAIL and save as a .PNG file
  * Then place the engine Image into your Android device/phone in the |br|\ '/Android/data/jmri.enginedriver/files/recent_engine_list' folder |br|\ example image name;  PE 1225.png

  Note: certain characters are not allowed in file names so need to be substituted with "_" (underscore) if you have used them in your roster name. They are:

  * / (forward slash) 
  * " (double quote)
  * \\ (backslash)
  * \* (asterisk)
  * ? (question mark)
  * < (less than)
  * > (greater than)

3. **Select an image on the phone/device (which can be taken on the phone's camera)**

 * In the **Roster List** on the Select Loco screen

   * Long press on the loco
   * press the :guilabel:`New Image` button, which will launch the Android system's default app for choosing images 
   * find and select an image
   * click :guilabel:`Save` |br|\ |br|\ You can replace an image with the :guilabel:`New Image` button or remove it with the :guilabel:`Remove` button

**General Notes on the Local Loco Icons:**

* If the loco already has an image in the JMRI Roster (of the currently connected |WTS|), you won't be able to choose a local image.
* If you later add an image in the JMRI Roster for the loco (or later connect to a |WTS| that has an image), it will automatically overwrite the local image with the one on the server.
* In the Recent Locos list you *can not* add images to locos entered by a DCC address. (i.e. not from the roster)  


.. note:: 
  :class: note-ed-hidden-title
  
  For adding a roster to DCC++EX see `Roster Entries <https://dcc-ex.com/automation/EX-RAIL-intro.html#roster-entries>`_.
