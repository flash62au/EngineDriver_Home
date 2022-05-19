*******************************************
Contributing
*******************************************

----
Code
----

TBA

-------------
Documentation
-------------

The steps listed here provide guidance on how to make and preview complex changes.

* You need to install a numbe rof tools on you local machine:
 
 * An appropriate text editor. For Windows we recommend the free `Visual Studio Code IDE (VSC) <https://code.visualstudio.com/>`_.
 * A version of Git. For Windows we recommend the free `GitHub Desktop <https://desktop.github.com/>`_.
 * A current version of Python 3 (which also installs pip). The Microsoft Store contains Python published by the Python Software Foundation for Windows. 

* Then use pip to install the required packages pip install 'sphinx' and the theme 'sphinx_rtd_theme'.  Open and command propmt and enter: 
  
 * pip install -U sphinx
 * pip install sphinx-rtd-theme
  
* On Githib, clone the EngineDriver_Home repository. `(See Cloning a repository in GitHub) <https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository>`_ 
* Using Github Desktop, clone you repository to your local machine.
* Edit the files in the EngineDriver_Home/docs folder. 
* Save, then check and preview your changes by running 'make github' from the root of the dcc-ex.github.io folder. This must be done from cmd.exe in Windows, not PowerShell. If any warnings are reported, fix these and run make github again. Then go to your local directory EngineDriver_Home/docs/_build/html and open index.html in Chrome or another browser.  
* Use Github Desktop to commit and then push your changes.  You can check the actions to see if it built correctly.  You can preview the pages on github at https://<yourname>.github.io/EngineDriver_Home
* Go to GitHub and issue a pull request for your branch to be pulled into the main branch. Once it’s merged in by one of the admins, your changes will go live!
