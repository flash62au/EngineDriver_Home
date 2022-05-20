*******************************************
Contributing
*******************************************

.. |br| raw:: html

   <br />

----
Code
----

On the Android device you intend to test on

* On your phone make sure that the developer options are enabled and ``Android debugging`` is on, and ``unknown sources`` is on.

Here are all the steps needed for Microsoft Windows:

* On Githib, clone the JMRI/EngineDriver repository. `(See Cloning a repository in GitHub) <https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository>`_ 
* Install Android Studio.
* Open Android Studio |br|\ (If necessary, close any open project and restart, so you get the Welcome Wizard)
* Select ``Check out project from Version control`` -> Git
* In the Clone Repository window, enter the Git Repository URL: ``https://github.com/JMRI/EngineDriver``, -> ``Clone``.  Note this is the original repoisitory, not your clone.
* Open the project. 
* Only if needed...

  * Take the Run -> Run... -> Edit Configurations option
  * In the Run/Debug Configurations window, press the "+", then Android App
  * Enter Name "EngineDriver", and select Module: EngineDriver
  * Click Run.
  * You will likely get one or more error messages about missing components. Click on the link in each message and Android Studio will automatically download the missing components.

To test you changes:

* Connect your phone via USB
* In the Select Deployment Target window, your attached phone should show under Connected Devices.
* Select your device and press `run`` or `debug``.
* EngineDriver should compile and be installed on your device.

To publish your changes:

* Android Studio, commit and push you changes to *your own* github repository.. To do this you will need to define a new remote ``https://github.com/<your name>/EngineDriver``
* Go to GitHub and issue a pull request for your branch to be pulled into the original repository. Once it's merged in by one of the admins, your changes will go live!


-------------
Documentation
-------------

All documentation is done using **reStructuredText**, for which you can find information on the official website: `reStructuredText <https://docutils.sourceforge.io/rst.html>`_
or the `Sphinx <https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html>`_ document builder tool website.
**reStructuredText** is a markdown type language, for typesetting documents from websites to PDF or LaTeX documents. 
This Website is built upon this technology, so you should make yourself familiar with this by looking through the links provided.

reStructuredText `QuickReference Guide <https://docutils.sourceforge.io/docs/user/rst/quickref.html>`_ 

The steps listed here provide guidance on how to edit and preview changes to the documentation.

* You need to install a number of tools on you local machine:
 
  * An appropriate text editor. |br|\ For Windows we recommend the free `Visual Studio Code IDE (VSC) <https://code.visualstudio.com/>`_. 

    * If using VSC, we recommend installing the ``reStructuredText Syntax highlighting`` extension.

  * A version of Git. |br|\ For Windows we recommend the free `GitHub Desktop <https://desktop.github.com/>`_.
  * A current version of Python 3 (which also installs pip). |br|\ The Microsoft Store contains Python published by the Python Software Foundation for Windows. 

* Then use pip to install the required packages; 'sphinx' and the theme 'sphinx_rtd_theme'.  Open and command prompt and enter: 
  
  * ``pip install -U sphinx``
  * ``pip install sphinx-rtd-theme``
  
* On Githib

  * Clone the EngineDriver_Home repository. `(See Cloning a repository in GitHub) <https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository>`_ 
  * open the repository settings, go to the 'Pages' section and chnage the 'soruce-branch' to ``gh-pages`` ``/ (root)``.

* Using Github Desktop, clone you repository to your local machine.
* Edit the files in the ``EngineDriver_Home/docs`` folder. 
* Save, then check and preview your changes by running ``make github`` from the root of the ``EngineDriver_Home`` folder. |br|\ This must be done from ``cmd.exe`` in Windows, not ``PowerShell``. If any warnings are reported, fix these and run make github again. Then go to your local directory ``EngineDriver_Home/docs/_build/html`` and open ``index.html`` in Chrome or another browser.  
* Use Github Desktop to commit and then push your changes. |br|\ You can check the actions to see if it built correctly. |br|\ You can preview the pages on github at ``https://<yourname>.github.io/EngineDriver_Home``
* Go to GitHub and issue a pull request for your branch to be pulled into the main branch. |br|\ Once it's merged in by one of the admins, your changes will go live!
