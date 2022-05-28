*******************************************
About
*******************************************
.. meta::
   :description: JMRI Engine Driver Throttle
   :keywords: Engine Driver EngineDriver JMRI manual help

.. |br| raw:: html

   <br />

----

.. image:: ../_static/images/screenshots/throttle_horizontal_switching_colorful.png
   :scale: 8 %
   :align: right

**Engine Driver Throttle** (normally just referred to as **Engine Driver** or just **ED**) is a free Android application that connects to a `WiThrottle™ Server <https://jmri.org/help/en/package/jmri/jmrit/withrottle/UserInterface.shtml>`_ [#WIT]_ to control model trains. 

Supported servers include `JMRI <https://jmri.org/>`_, `DCC-EX <https://dcc-ex.com/>`_, `MRC Prodigy WiFi <https://www.modelrectifier.com/category-s/332.htm>`_, `Digitrax LnWi <https://www.digitrax.com/products/wireless/lnwi/>`_, and `WifiTrax (for NCE) <http://wifitrax.com/products/product-WFD-30-detail.html>`_. 

**Engine Driver** can control:

* The speed direction and up to 29 DCC functions of you DCC enabled your locos
* Virtual loco sounds 
* From one to six locos or consists / multiple units can be controlled at the same time
* You can easily create and edit on-the-fly consists / multiple units (software-defined). 
* You can control layout power, turnouts/points, routes, and access JMRI web panels and windows.
* You can customise **Engine Driver** extensively to meet your needs

Generally the WiThrottle servers that **Engine Driver** connects to are either DCC Command Stations, or are designed to talk to DCC Command Stations (e.g. JMRI) to subsequently talk to DCC Decoder equipped locos on a layout.  However DCC++EX is currently experimenting with the possibility of controlling DC locos or even Slot cars instead.

.. note:: 
  :class: note-ed-hidden-title

  See the `Operation <../operation/index.html>`_ page for details on how to use **Engine Driver**.

**Engine Driver** is open source software. The source code is available on `github.com/JMRI/EngineDriver <https://github.com/JMRI/EngineDriver>`_. This documentation is also open source and can be accessed on `github.com/flash62au/EngineDriver_Home <https://github.com/flash62au/EngineDriver_Home>`_. Contribution to both the code and documentation is welcome.  See [`Contributing <../contributing/index.html>`_] for details.

**Engine Driver** currently has minSDKVersion of 16, which equates to minimum Android OS version of 4.1 (JELLYBEAN). 
Info on minSDKVersion available in the `Engine Driver manifest <https://developer.android.com/guide/topics/manifest/uses-sdk-element#ApiLevels>`_.


What's a 'WiThrottle Server'?
-----------------------------

WiThrottle stands for 'WiFi Throttle', and a “WiThrottle Server' is just software running on your JMRI computer, DCC-EX Command Station, or dedicated device. It's called a 'Server' because it allows you to connect to it and it 'serves', or services, requests from another application. That application is called a 'Client'. So **Engine Driver** in this case is the client.

The WiThrottle Protocol itself is a standard for how WiFi throttles can communicate with Command Stations, much like the DCC standard is a standard for how data packets communicate with decoders. What this means for you, is that **Engine Driver** can talk to any WiThrottle compatible server.


----

.. [#WIT] 'WiThrottle' is a trademark owned by Brett Hoffman. It is also an `iOS app <https://www.withrottle.com/html/home.html>`_ developed by Brett Hoffman which has similar capabilities to Engine Driver. |br|\ The 'WiThrottle protocol' is a proprietary protocol developed by Brett Hoffman.  It is used JMRI, **Engine Driver** and a number of DCC Command Stations. |br|\ References in this website to a 'WiThrottle Server', refer to a server that can communicate using the 'WiThrottle protocol'.
