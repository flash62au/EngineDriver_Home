:orphan:

******************************************
Consist Function Follow 
******************************************

.. meta::
   :keywords: Consist Function Follow

.. include:: ../include.rst

.. sidebar::

  .. contents:: On This Page
     :local:
     :depth: 3

----
 
**Engine Driver - Consist Function Follow Preferences**

By default, in |ed|, if you activate a DCC function while controlling a Consist/Multiple Unit train only the function on the lead loco will actually be activated.
|ed| provides options (preferences) that will activate the functions on the other locos in the consist/multiple unit train given a number of possible rules.

The following document provides information on the different rule types and how to use them.

.. contents:: This document is in two distinct sections:
    :depth: 1
    :local:
    :class: in-this-section

Overview
========

Introduction
------------

Function Labels
~~~~~~~~~~~~~~~

Most (all bar one) of the Throttle Layouts in |ed| show a number of DCC Function Buttons below or beside the Sliders for the individual Throttles on the Screen.

By default:

* If you select a loco from a WiThrottle, or DCC-EX, Roster Entry, it will show the labels on the buttons as they have been configured in the Roster Entry on the server.

  * If you enter the DCC address of the loco, it will show Engine Driver's 'Default Function Labels'.
  * All 32 functions will be shown. They are:

    * F0 / Light
    * F1 / Bell
    * F2 / Horn / Whistle
    * F3 - F31

  * Which function buttons, how many function buttons and what labels are displayed, can be changed via the Menu ‣ Function Defaults from the Throttle Screen
  * If you select a Loco from the Recent Locos or Recent Consists lists that was originally selected from a roster, |ed| will attempt to show the Labels from the WiThrottle Server roster entry.

Functions in consists / Multiple Unit Trains 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

By default DCC Functions are only sent to the first loco in a Consist / Multiple Unit train.

There are a number of preferences, explained in this document, that can be used to override this default behaviour.

----

Terminology
-----------

The following terms are useful to understand as they are used throughout this document:

* Loco Functions / DCC Functions
* Default Function Labels / Default Functions
* Throttle Function Labels / Throttle Functions
* Function Label Matching

Loco Functions or DCC Functions: 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

These are the functions (F0, F1, F2, etc) that are programmed into a given loco decoder. The behaviour of a given Loco Function is set by this programming. Engine Drive activates these functions but cannot change them.

Roster Entry Function Labels or Roster Functions: These are the function labels defined in the JMRI DecoderPro "Function Labels" panel of a given roster entry. Roster Function Labels are mapped to a given Loco Function (e.g. F0, F1, F2, etc) by DecoderPro. The behaviour of a given locomotive function (F1, F2, etc.) is set by the programming of the decoder and is not changed by its label. |ed| uses these Roster Functions Labels but cannot change them. By definition a Roster Function is associated with a specific loco.

Default Function Labels or Default Functions: 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: /_static/images/consist_follow_functions/default_function_labels.png
   :alt: Default Function Labels
   :scale: 50%
   :class: align-right

|ed| allows the definition of a set of default function labels which are used in the throttle display. The Default Function Labels can be used in place of loco Roster Function Labels or can be used when loco Roster Function Labels have not been defined. Default Function Labels can be defined manually in |ed| or copied from the Roster Function Labels of a given loco. 

These Default Function Labels exist only in |ed| and do not affect the JMRI Roster Function Labels.

Default functions are defined as the pair for each button: a) Function Number, and b) Label. The order of the function buttons displayed therefore do not have to be in numeric sequence of the 0-28.

Throttle Function Labels or Throttle Functions: 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

These are the function labels are defined in JMRI (or EX-CommandStation) and are used by |ed| in the throttle display of a given locomotive or consist. Depending on |ed| preferences these are copied from the loco Roster Function Labels or from the |ed| Default Function Labels. 

In addition, when Default Functions are used, |ed| provides the ability to map a given Default Function to a loco Roster Function (and hence to a Loco Function).

Function Label Matching: 
~~~~~~~~~~~~~~~~~~~~~~~~

.. figure:: /_static/images/consist_follow_functions/consist_follow_function_preference2.png
   :alt: Preferences
   :scale: 40%
   :class: align-right

.. figure:: /_static/images/consist_follow_functions/consist_follow_function_preference1.png
   :alt: Preferences
   :scale: 40%
   :class: align-right

Engine Driver's Function Label Matching allows each Throttle Function to be mapped to a Function Label in the Roster Entry for each/any loco, based on a one of several label matching 'rules'. 

Without Function Label Matching, Throttle Functions activate the associated Loco Function based on the associated function number of the Throttle Function in the throttle display, Generally, that means that the label in position 0 (top or left most) will activate F0, etc. (Note that however, it is possible to rearrange the function numbers in the default label screen so that is not always true.) So when operating a single loco, function matching allows |ed| to display functions in a standard order regardless of the function assignment of a given loco. 

So rather than remapping all locos in a roster to a standard function assignment, Function Label Matching feature can be used to provide a consistent throttle function display. Moreover, all locos in the roster do not have to have the same ordered programmed function assignment.

In the case of consists, Function Label Matching can be used to associate a given Throttle Function to a Loco Function via its match to its Roster Entry Function Label so that a particular function (or functions) can be activated on all locos in a consist.  

----

Default Function Label Preferences
----------------------------------

The following preferences provide options for when and how the default Function Labels are displayed. These preferences can also be accessed via the Function Defaults menu on the drop down from the Throttle display. Note the "Use default function labels?" is set to "Yes".

By changing the function numbers, you can effectively reorder the functions. This will work for both Roster and non-Roster locos.

'Use default function labels?' Preference
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can use this preference to have |ed| always display the Default Function Labels (configured inside |ed|) instead of the Function Labels from the Roster Entry. |ed| will ignore the roster data for the Throttle Function button labels. 

**NOTE: It is essential this is enabled if you wish to use any of the 'Special' matching options.**

'Number of Default Functions' Preference
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

When using Default Functions, you can use this preference to limit the number of Throttle Function Labels shown when a loco is acquired by using its DCC address alone..

'Number of Default Functions for Roster' Preference
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can use this preference to limit the Throttle Function Labels shown for when a locos is acquired from a Server Roster Entry that doesn't have any function labels configured for that Roster Entry.

'Consist Functions - Follow Rule Styles' Preference
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* Simple Text Matching (original)
* Complex
* Special Exact
* Special Partial
* Special Partial - Contains Only 

*See below for the meaning of these.*

----

Function Label Matching
-----------------------

NOTE: |ed| only uses Function Label Matching for the 'Special' options when:

1. The 'Use default function labels' preference is enabled.
2. The loco (or locos in a consist) are selected from the roster and 
3. One of the 'Consist Functions - Follow Rule Styles' preference is enabled. 

*If not all the above is true, the functions are activated purely #based on the function number.*

Options for 'Consist Functions - Follow Rule Styles' preference are:

* Simple Text Matching (original)
* Complex
* Special Exact
* Special Partial
* Special Partial - Contains Only 

*Note: For all Text Matching, case sensitivity is not required, meaning Lower and Uppercase labels will result in a successful match for a given function.*

|HR-DASHED|

'Simple Text Matching (original)' Option
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Simple Function Label Matching - Single loco operation with Default Functions – Some of the 'common' Default Function Labels are matched to loco Roster Function Labels to determine which Loco Function is activated.

These primarily handle F0 (Headlight), F1 (Bell) and F2 (Horn/Whistle), *NO other* functions are propagated to the remaining locos in the consist and no label matching is performed. That is, the Loco Function activated is determined by the position of the label in the throttle. e.g. the top-most function is F0.

The following additional preferences are enabled if the 'Simple Text Matching (original)' option is selected and impact how the functions behave:

* 'Selective Lead Unit Sound?' preference
* 'Always treat F1 as Sound?' preference
* 'Always treat F2 as Sound?' preference

This form of |ed| consisting is very simple to use and covers a large majority of situations in which the key functions restricted to the lead loco are Lights/Horn/Bell and the remainder are not propagated (or not used).

|HR-DASHED|

'Complex' Matching
~~~~~~~~~~~~~~~~~~

Using the 'Complex' option, |ed| searches for user supplied text and applies user supplied rules (supplied in a group of |ed| preferences) for matching function labels in the locos in the consist / multiple unit train.

This form of |ed| consist function matching allows you to specify the labels of the functions for which you want to specify a given propagation rule. It does NOT rely on the Roster Function Labels of the lead loco nor the use of Default Functions. It is likely useful when there are only a few specific functions (e.g. other lights) that you do want propagated to the other locos in the consist / multiple unit train.

*Note, for this option to have any effect:*

* The loco (or locos in a consist) must be selected from the roster.
* Some or all the rules need to be configured

|HR-DASHED|

The three 'Special' Matching Options
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

With the three 'Special' matching options you can specify the Throttle Function Label names to be matched (the base value), whether Exact or Partial matching is to be applied, and how the matched labels are to be propagated (to lead, lead and trail, or all locos). 

**These options must be used** in conjunction with the use of **Default Functions**. Each Throttle Function Label (which will be the Default Function Label) of the lead loco is compared to the Roster Function Label of the consisted locos and the function propagation and, if matches, activates the functions. The propagation rules for each function are individually specified for each function.

When any of the 'Special' options are selected, a new menu item will be available ('Consist Function Defaults') which will allow you to specify how the default functions should behave (Latching or Non Latching).

This form of |ed| consist function matching provides the maximum flexibility for specifying individual propagation rules for given functions. A special simple screen is provided for setting up the rules for each function.

For the three Special Label Matching Consist/Multiple Unit options, the function labels of the locos in the consist are matched against the text in the Default Function Labels and the rule attached to each function to determine which Loco Function, in which locos in the consist, are activated (the nature of the matching is determined by rules in the 'Consist Function Follow' screen).

*Note, for these options to have any effect:*

* The 'Use default function labels' preference must be enabled.
* The Default Function Labels need to be altered to suit your needs.
* The Consist Function Defaults need to be altered to suit your needs.
* The loco (or locos in a consist) must be selected from the roster and have function labels assigned

'Special - Exact Matching' Option
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Using the 'Special - Exact' option, the given label must exactly match the other. e.g. "Ditch Lights" matches "Ditch Lights" and does not match "Ditch", "Lights", "DitchLights" or "Ditch Light"

Special characters are treated in the same way as normal characters. e.g. "Prime.Mover" does not match "PrimeMover".

Character matching is case insensitive, e.g. "headlight" matches "Headlight".

Spaces (blanks) are treated in the same way as normal characters. e.g. "Horn" does not match "Horn  " and "EBell" does not match "E Bell". **WARNING: ensure you do not have any unintended trailing blanks.**

'Special Partial Matching' Option
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. todo:: 'Special Partial Matching' Option

IF

a) The whole of the default label is contained within the compared label. e.g. 
b) The whole of the compared label if contained within the default label

e.g. 

* "Light" (the base) will partially match to "Headlight" or "Ditch Light" (the compared).
* "Headlight" (the base) will partially match to "Light" (the compared).
* "Horn" (base) will partially match to "Horn K5LA"

Caution: Using short base words can result in unwanted and unexpected partial matches. e.g. "Brake" will partial match "Dynamic Brake", "Independent Brake" and "Brake Set/Release OFF". "Light" will partially match to "FrtHeadlight" and "RrHeadlight".

Special characters, case and blanks are handled in the same way as for Exact Matching.

'Special Partial - Contains Only' Option
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The 'Special Partial - Contains Only' option is similar to Special Partial Matching, except that comparison is only one way.

e.g. 

* "Light" (the base) will partially match to "Headlight" or "Ditch Light" (the compared).
* "Headlight" (the base) WILL NOT partially match to "Light" (the compared).

|HR-HEAVY|

|HR-HEAVY|

Consist Function Follow Preferences - Detailed Reference
========================================================

.. figure:: /_static/images/consist_follow_functions/consist_follow_function_preference2.png
   :alt: Preferences
   :scale: 40%
   :class: align-right

.. figure:: /_static/images/consist_follow_functions/consist_follow_function_preference1.png
   :alt: Preferences
   :scale: 40%
   :class: align-right

These preferences allow you to specify the way DCC functions will behave in a consist / multiple unit train.

Consist Functions - Follow Rule Style Preference
------------------------------------------------

.. todo:: See the XXX page for more information.

This preference sets which style of rules to follow in a consist /  multiple unit train when function buttons are pressed in |ed|.

.. figure:: /_static/images/consist_follow_functions/consist_follow_function_options.png
   :alt: Options
   :scale: 80%
   :class: align-right

Options:

* Simple text matching (original)
* Complex text matching
* Special Exact
* Special Partial
* Special Partial - Contains Only 

These options are described below in detail.

|HR-DASHED|

Simple Consisting Option and Related Preferences
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you select the 'Simple' option in the 'Consist Functions - Follow Rule Style' preference…

# The behaviour of F0 (Headlight) is determined by the Edit Consist Lights control on the throttle (select the consist on the throttle and then "Edit Lights" or simply long press on the consist to be taken directly to the 'Edit Lights' control.
# The 'Selective Lead Unit Sound' preference prevents any Throttle Function Label of 'Horn', 'Bell' and 'Whistler' (in this case these specific labels are built into the software and cannot be changed) from being propagated.
# The 'Always Treat F1 as Sound' preference will prevent F1 from being propagated regardless of function label.
# The 'Always Treat F2 as Sound' preference will prevent F2 from being propagated regardless of function label.

This form of |ed| function response is very simple to use and covers a large majority of situations in which the key functions restricted to the lead loco are Lights/Horn/Bell and the remainder are propagated (or not used).

'Selective Lead Unit Sound?' Preference
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

If this preference is enabled, Horn/Bell functions are only the Lead unit in an |ed| consist.

Only/any function with a 'label' that includes 'bell', 'horn' or 'whistle' as part of the label.

'Always treat F1 as Sound?' Preference
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

If this preference is enabled, F1 one is always treated as a sound and is always propagated to all locos in a consist.

This preference is ignored if 'Complex' or 'Special' options are selected in the 'Consist Functions - Follow Rule Style' preference.

'Always treat F2 as Sound?' Preference
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

If this preference is enabled, F2 one is always treated as a sound and is always propagated to all locos in a consist.

This preference is ignored if 'Complex' or 'Special' options are selected in the 'Consist Functions - Follow Rule Style' preference.

|HR-DASHED|

'Complex' Text matching Option
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Using the 'Complex' option, |ed| searches for text and applies a number of rules supplied in a group of |ed| preferences for matching labels in the locos.  The user entered string must match exactly against the labels assigned for each function in JMRI for the function to work on all locos in the consist.

These preferences (which are explained below) are only available to edit/change if 'Complex text matching' is selected for the 'Consist Functions - Follow Rule Style' Preference:

* If All matches Fail Action
* Headlight specific string 1
* Headlight specific Action 1
* String 2
* Action for String 2
* String 3
* Action for String 3
* String 4
* Action for String 4
* String 5
* Action for String 5

*Note, for this option to have any effect:*

* The loco (or locos in a consist) must be selected from the roster.
* One or more of the preferences below must be set

'If All matches Fail Action' Preference
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. todo:: 'If All matches Fail Action' Preference

Which locos in the consist should react to the function buttons if none of the rules below are met.

For the 'Complex' option only. This preference is ignored if 'Simple' or 'Special' options are selected in the 'Consist Functions - Follow Rule Style' preference.

'Headlight specific String 1' Preference
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. todo:: 'Headlight specific String 1' Preference

Comma separated string(s) to look for in the function labels of the locos in the consist to recognise the 'Headlight' function (normally F0).
For the 'Complex' option only. This preference is ignored if 'Simple' or 'Special' options are selected in the 'Consist Functions - Follow Rule Style' preference.
 
'Headlight specific Action 1' Preference
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. todo:: 'Headlight specific Action 1' Preference

Which locos in the consist should react to the found headlight functions.

For the 'Complex' option only. This preference is ignored if 'Simple' or 'Special' options are selected in the 'Consist Functions - Follow Rule Style' preference.

Each 'action' can be one of:

* Lead Loco - Partial Match
* Lead+Trail Locos - Partial Match
* All Locos - Partial Match
* Lead Loco - Exact Match
* Lead+Trail Locos - Exact Match
* All Locos - Exact Match

Note:

* 'Lead+Trail' refers to the first and last locos in the consist / multiple unit train. |br| i.e. If there are only two locos, then 'Lead+Trail Locos' will give the same result as 'All Locos'. |br| If more than two, then 'Lead+Trail' will give a different result.  The locos in the middle will not receive the function.

String 2, 3, 4, 5 Preferences
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. todo:: String 2, 3, 4, 5 Preferences

This applies to String 2, String 3, String 4, String 5
For the 'Complex' option only. This preference is ignored if 'Simple' or 'Special' options are selected in the 'Consist Functions - Follow Rule Style' preference.

Action for String 2, 3, 4, 5 Preferences
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. todo:: Action for String 2, 3, 4, 5 Preferences

This applies to Action for String 2, Action for String 3, Action for String 4, Action for String 5.

For the 'Complex' option only. This preference is ignored if 'Simple' or 'Special' options are selected in the 'Consist Functions - Follow Rule Style' preference.

|HR-DASHED|

'Special' Consist Function Matching Options
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. todo:: 'Special' Consist Function Matching Options

You can now arrange the default function labels on ED any way you want, and as long as the equivalent function has a similar name it doesn't matter what function number it is, it will activate it correctly.
Note, for these options to have any effect:
The 'Use default function labels' preference must be enabled.
The loco (or locos in a consist) must be selected from the roster
Note: If 'Use Default function labels' is enabled, 'Special…' will also apply to the lead (or only) loco.


'Special - Exact Matching' Options
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. todo:: 'Special - Exact Matching' Option

'Special Partial Matching' Options
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. todo:: 'Special Partial Matching' Option

'Special Partial - Contains Only' Options
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. todo:: 'Special Partial - Contains Only' Option

