*******************************************
About Engine Driver
*******************************************

.. include:: ../include.rst

What is 'Engine Driver'
-----------------------

.. image:: ../_static/images/screenshots/throttle_horizontal_switching_colorful.png
   :scale: 8 %
   :align: right

|edt| (normally just referred to as |ed| or just **ED**) is a free Android application that connects to a `WiThrottle™ Server <https://jmri.org/help/en/package/jmri/jmrit/withrottle/UserInterface.shtml>`_ [#WIT]_ to control model trains. 

Supported |wtss| include:

* `JMRI <https://jmri.org/>`_,
*  `DCC-EX <https://dcc-ex.com/>`_
*  `MRC Prodigy WiFi <https://www.modelrectifier.com/category-s/332.htm>`_
*  `Digitrax LnWi <https://www.digitrax.com/products/wireless/lnwi/>`_
*  `WifiTrax (for NCE) <http://wifitrax.com/products/product-WFD-30-detail.html>`_ 

|ed| can: 

* Control the speed direction and up to 29 DCC functions of you DCC enabled your locos
* Control from one to six locos or consists / multiple units can be controlled at the same time
* Easily create and edit on-the-fly consists / multiple units (software-defined)
* Control layout power, turnouts/points, routes, and access JMRI web panels and windows
* Play virtual loco sounds 

You can customise |ed| extensively to meet your needs.

Generally the |wtss| that |ed| connects to are either DCC Command Stations, or are designed to talk to DCC Command Stations (e.g. JMRI) to subsequently talk to DCC Decoder equipped locos on a layout.  However DCC++EX is currently experimenting with the possibility of controlling DC locos or even Slot cars instead.

.. note:: 
  :class: note-ed-hidden-title

  See the :doc:`/operation/index` page for details on how to use |ed|.

|ed| is open source software which is available on `github.com/JMRI/EngineDriver <https://github.com/JMRI/EngineDriver>`_. This documentation is also open source and can be accessed on `github.com/flash62au/EngineDriver_Home <https://github.com/flash62au/EngineDriver_Home>`_. Contribution to both the code and documentation is welcome.  See [`Contributing <../contributing/index.html>`_] for details.

|ed| currently has minSDKVersion of 16, which equates to minimum Android OS version of 4.1 (JELLYBEAN). 
Info on minSDKVersion available in the `Engine Driver manifest <https://developer.android.com/guide/topics/manifest/uses-sdk-element#ApiLevels>`_.

What's a 'WiThrottle Server'?
-----------------------------

WiThrottle stands for 'WiFi Throttle', and a 'WiThrottle Server' is just software running on your JMRI computer, DCC-EX Command Station, or dedicated device. It's called a 'Server' because it allows you to connect to it and it 'serves', or services, requests from another application. That application is called a 'Client'. So in this case |ed| is the client.

The WiThrottle Protocol itself is a standard for how WiFi throttles can communicate with the WiThrottle Server, much like the DCC standard is a standard for how data packets communicate with decoders. What this means for you, is that |ed| can talk to any WiThrottle compatible server, which in turn can talks to your DCC encoders in your locos.

.. note:: 
  :class: note-ed-hidden-title

  See the :ref:`WiThrottle Servers <prerequisites/index:withrottle servers>` section of the Prerequisites page for information on the different WiThrottle Servers.

----

.. [#WIT] 'WiThrottle' is a trademark owned by Brett Hoffman. It is also an `iOS app <https://www.withrottle.com/html/home.html>`_ developed by Brett Hoffman which has similar capabilities to Engine Driver. |br|\ The 'WiThrottle protocol' is a communications protocol developed by Brett Hoffman.  It is used JMRI, |ed|, the wiThrottle app and a number of other apps and DCC Command Stations. |br|\ References in this website to a '|wts|', refer to a server that can communicate using the 'WiThrottle protocol'.

Roadmap
-----------

|ed| doesn't really have a roadmap.  Code changes (bug fixes and features) are done depending on several factors, including:

* Who is available to work on it 
* Who among the available people is interested enough to do the work
* Are there enough people likely to use it to make it worth the effort

At the moment there are only a few of us doing any work on |ed|, so things happen when they happen.

See the :doc:`/contact/index` page if you are having problems or wish to make a suggestion.

Alternates to Engine Driver
---------------------------

|ed| is not the only app that can connect to JMRI, |wtss| or DCC++EX, so it is worth your time to investigate to alternates.

See the `JMRI WiThrottle page <https://www.jmri.org/help/en/package/jmri/jmrit/withrottle/UserInterface.shtml>`_ for a list of similar or related apps.

See the `DCC++EX page <https://dcc-ex.com/throttles/index.html>`_ for a list of similar or related apps.
