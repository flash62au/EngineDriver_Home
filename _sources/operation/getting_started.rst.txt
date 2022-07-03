=============================
Quick Start / Getting Started
=============================

.. meta::
   :keywords: operation

.. include:: ../include.rst

* Install |ed| from the `Google Play Store <https://play.google.com/store/apps/details?id=jmri.enginedriver>`_ or by `direct download <../downloads/index.html>`_. 
* Confirm that your devices meet the `Prerequisites <../prerequisites/index.html>`_
* **Start your WiThrottle server**

  * For JMRI, Start the `WiThrottle <https://www.jmri.org/help/en/package/jmri/jmrit/withrottle/Protocol.shtml>`_ function of JMRI, located in DecoderPro under Tools, Throttles. |br|\ It is also highly recommended that you start the `JMRI Web Server function <https://www.jmri.org/help/en/html/web/index.shtml>`_ (Tools, Start JMRI Web Server). 
  * For other devices, turning them on and waiting a minute or two should be sufficient.

    See the `Prerequisites <../prerequisites/index.html>`_ page for more information.

* **On your Android device/phone** 
  
  * Make sure you are connected to same network as the |WTS|'s network.

  * Start |ED| 

    * The first time you run |ED| you will need to go through the Setup Wizard to agree to the permissions and select a few key preferences  
   
      See the `Setup Wizard <../configuration/setup_wizard.html>`_ page for more information.

  * Wait for your server's address to show up in 'Discovered Servers'

  * Click on the Discovered server

    * If your |WTS| does not show up, check that are on the same network as the |WTS|.   
    * If the server *never* appears in the discovered list, type in the IP address and Port of the |WTS| (Using the values shown on the JMRI WiThrottle window) and press :guilabel:`Connect`. |br|\ Note: this situation is sometimes possible even if you are on the same network. |br|\ |br|\ See the `WiFi connection <./wifi_issues.html>`_ page for more assistance if you have connection issues. |br|\ |br|\ 

  * If needed, turn the track power on with :menuselection:`Menu --> Power` and confirm the button is 'green'  (This is not required by all DCC Command Stations.)
  
  * On the Throttle screen, click on the :guilabel:`Select` loco button

  * On the next (Loco Select) screen, either:

    * Click on a loco from the Roster or Recent lists |br|\ or
    * Enter the loco address (verify short or long), and press :guilabel:`Acquire`

      You will be returned to the |T-S|.

      For Consists / multiple units, see the note below.

  * Operate your loco 
  
    * Use the slider, or volume hardware buttons, or optional buttons for speed
    * Use the :guilabel:`Forward` and :guilabel:`Reverse` buttons to control direction

  * Press your phone's Menu button to access screens for Turnout, Route and Power control, as well as adjust settings and set numerous preferences
  * You can also 'swipe/fling' left or right to jump quickly back and forth between the Throttle, Routes, Turnouts and Web pages. (Use Preferences to choose which are in the left / right swipe list) |br|\ |br|\ 

  * To release a single loco (or consist), click :guilabel:`Select` again and click the :guilabel:`Release` button

  * To release all locos, just press the :guilabel:`Back` button and exit the app. |br|\ This will also stop your locos (can be overridden in preferences)

Note:

* To create a consist 'on-the-fly', simply select additional locos for the same throttle, then select which way the new loco if facing. Direction and speed will be sent for all. Release will release all for that throttle

