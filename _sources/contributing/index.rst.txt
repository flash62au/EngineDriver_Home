*******************************************
Contributing
*******************************************

.. meta::
   :keywords: contributing developing

.. include:: ../include.rst

.. sidebar::

  .. contents:: On This Page
    :local:

Contributing to the Code
========================

|ed| is open source software written in Java. The source code is available on `github.com/JMRI/EngineDriver <https://github.com/JMRI/EngineDriver>`_.

It is recommended that you contact M Steve Todd if you intend to contribute to the code base, before you start working.

On the Android device you intend to test on

* Make sure that the developer options are enabled and ``Android debugging`` is on, and ``unknown sources`` is on.  You can also use the Virtual Devices in Android Studio to test you cade.

Here are all the steps needed for Microsoft Windows:

* On GitHub 
  
  * Clone the JMRI/EngineDriver repository. `(See Cloning a repository in GitHub) <https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository>`_ 
  * Create a Personal Access Token that will allow you remotely update your repository.  See \[`here <https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token>`_\] for details.   Copy the full code of the token somewhere as you will need it later.

* Install `Android Studio <https://developer.android.com/studio>`_.
* Open Android Studio |br|\ (If necessary, close any open project and restart, so you get the Welcome Wizard)
* Select ``Check out project from Version control`` -> Git
* In the Clone Repository window, enter the Git Repository URL: ``https://github.com/JMRI/EngineDriver``, -> ``Clone``.  |br|\ *Note this is the original repository, not your clone.*
* Open the project. 
* Only if needed...

  * Take the Run -> Run... -> Edit Configurations option
  * In the Run/Debug Configurations window, press the "+", then Android App
  * Enter Name "EngineDriver", and select Module: EngineDriver
  * Click ``Run``.
  * You will likely get one or more error messages about missing components. Click on the link in each message and Android Studio will automatically download the missing components.

To test your changes:

* Connect your phone via USB
* In the Select Deployment Target window, your attached phone should show under Connected Devices.
* Select your device and press ``run`` or ``debug``.
* EngineDriver should compile and be installed on your device.

To publish your changes:

* Android Studio, commit and push your changes to *your own* GitHub repository.. |br|\ To do this you will need to define a new remote ``https://github.com/<your name>/EngineDriver``
* Go to GitHub and issue a pull request for your branch to be pulled into the original repository. Once it's merged in by one of the admins, your changes will go live!

Contributing to the Localisation (Languages)
============================================

We are always looking for people to help with maintaining and expanding the non-English versions of the text in the code.

It is possible to do so via the methods described in `Contributing to the Code <./index.html#contributing-to-the-code>`_ but if you are not a developer this can be daunting.  

If you are interested in helping with this please please :doc:`contact <../contact/index>` the developers and we can provide a simpler way to contribute.


Contributing to the Documentation
=================================

This documentation is open source and can be accessed on `github.com/flash62au/EngineDriver_Home <https://github.com/flash62au/EngineDriver_Home>`_

All this documentation is done using **reStructuredText**, for which you can find information on the official website: `reStructuredText <https://docutils.sourceforge.io/rst.html>`_
or the `Sphinx <https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html>`_ document builder tool website.
**reStructuredText** is a markdown type language, for typesetting documents from websites to PDF or LaTeX documents. 
This Website is built upon this technology, so you should make yourself familiar with this by looking through the links provided.

reStructuredText `QuickReference Guide <https://docutils.sourceforge.io/docs/user/rst/quickref.html>`_ 

The steps listed here provide guidance on how to edit and preview changes to the documentation.

* You need to install a number of tools on you local machine:
 
  * An appropriate text editor. |br|\ For Windows we recommend the free `Visual Studio Code IDE (VSC) <https://code.visualstudio.com/>`_. 

    * If using VSC, we recommend installing the ``reStructuredText Syntax highlighting`` extension.

  * A version of Git. |br|\ For Windows we recommend the free `GitHub Desktop <https://desktop.github.com/>`_.
  * A current version of 'Python 3' (which also installs 'pip'). |br|\ The Microsoft Store contains Python published by the Python Software Foundation for Windows. 

* Then use 'pip' to install the required packages; 'sphinx' and the theme 'sphinx_rtd_theme'.  |br|\ Open and command prompt and enter: 
  
  * ``pip install -U sphinx``
  * ``pip install sphinx-rtd-theme``
  
* On GitHub

  * Clone the ``https://flash62au.github.io/EngineDriver_Home`` repository. `(See Cloning a repository in GitHub) <https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository>`_ 
  * Open the your repository settings (the gear icon), go to the 'Pages' section and change the 'source-branch' to ``gh-pages`` ``/ (root)``.
  * Your repository must be ``public``

* On your PC
  
  * Using GitHub Desktop, clone your repository to your local machine
  * Edit the files in the ``EngineDriver_Home/docs`` folder
  * Save, then check and preview your changes by running ``make github`` from the root of the ``EngineDriver_Home`` folder. [#makegithub]_ |br|\ This must be done from ``cmd.exe`` in Windows, not ``PowerShell``. |br|\ If any warnings are reported, fix these and run make GitHub again
  * Preview your changes locally by going to your local directory ``EngineDriver_Home/docs/_build/html`` and open ``index.html`` in your web browser of choice.  
  * Use GitHub Desktop to commit and then push your changes

* In GitHub
  
  * You can check the 'actions' to see if it built correctly. |br|\ You can preview the pages on GitHub at ``https://<yourname>.github.io/EngineDriver_Home``
  * Issue a pull request for your branch to be pulled into the main branch. |br|\ Once it's merged in by one of the admins, your changes will go live!


.. [#makegithub] There is a batch file ``make github.bat`` in the ``EngineDriver_Home`` folder which should be able to be double-clicked on the run this command. It will pause at the end to allow you see if there are any issues.

Style Guidelines
----------------

* Use British/Australian/Canadian spelling e.g. 'colour' not 'color'.  |br|\ (Primarily because it is used in more English speaking countries)
*	Use railroad/railway terminology that is understandable by all English-speaking people. |br|\ Where there are clear differences from US to non-US terminology use both with a slash between and use the US version first. e.g. turnouts/points, consists/multiple units, switching/shunting.  (Primarily because JMRI uses the US terminology)
* In general use 'loco' instead of 'locomotive' or 'engine'
* Avoid the term 'Checked'. Use 'Enabled' instead.  ("Checked' is more a US term.)
* Use bolded \*\*Engine Driver\*\* or \|ed\| not 'Engine Driver app', 'EngineDriver' or 'Engine Driver Throttle' (except on the first page) - |ed|
*	No full stop at the end of a numbered or unnumbered list
*	Numbered lists should be avoided, unless there is a specific need
* Use first person (you and your; not I, me, my or am) language
*	A string of nouns should be sequenced in alphabetic order, unless it makes more sense within the context to display them in some other sequence
* Double quotes (") should only be used for quoting text from people, documents or web sites
*	No quotes around 'Also See' type references
*	Avoid '(above)' or '(below)' in text.  Use hypertext links instead
*	'TODO' or \|todo\| in the text means that it is still a work-in-process and needs to be updated.  It may be followed by descriptive text in italics describing the issue to be fixed
* Use \`\`\literal text blocks\`\` when describing preference values  - ``literal text blocks``
* Use \:menuselection\:\`Menu --> Preferences --> ..\` for menu descriptions - :menuselection:`Menu --> Preferences --> ..` 
* Use \:guilabel\:\`\GUI labels\` for buttons  - :guilabel:`GUI labels`
* Avoid using 'phone' alone. Preferably use 'Android device/phone'
* For dates, use dd-mmm-yyyy or yyyy-mm-dd to avoid confusion with the way dates are uniquely written in the US. |br|\ e.g. 2-Mar-2022 or 2022-3-2, not 2-3-2022 
* Heading levels:

  * ######### with overline, for parts - not really used
  * \*\*\*\*\*\*\*\*\*\*\*\* Page Titles
  * ========= for sections
  * \-\-\-\-\-\-\-\-\-\-\-\-\-\-\- for subsections
  * ^^^^^^^^^ for subsubsections
  * \"\"\"\"\"\"\"\"\"\"\"\"\"\"\" for paragraphs
  * \'\'\'\'\'\'\'\'\'\'\'\'\'\'\'\'\'\'\'\'\'\'\'\'\'\'\' for sub paragraphs
