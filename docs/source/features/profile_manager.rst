Profile manager
===============

In MapEditor, different profiles can be added to energy assets' In and OutPorts. A user can choose a profile from the list of pre-defined EDR or MapEditor's DB profiles (such as standard NEDU profiles), but also define and choose their own profiles. Adding custom profiles, as well as deleting them, is done through the *Profile manager*.

Uploading custom profiles
-------------------------

To access the *Profile manager*, click on *View* menu item on the menu bar (nr.1), and go to *Settings* (nr.2).

.. image:: images/profile_manager1.png
  :width: 800
  :alt:

Navigate to *Profiles plugin* and click on *Upload profiles* (nr.3). For it to be recognized by MapEditor, a custom profile should be provided as a CSV file that adheres to a certain format. The formatting rules are listed at the bottom of the window (see the green box).
Profiles can be stored in different groups, depending on the access rights. For example, a user can define a personal profile (accessible only by the user that defined it), a profile related to a certain project (accessible by users working on the same project), or a profile that will be stored to EDR or MapEditor's database (accessible by everyone).
To upload a custom profile, choose the appropriate access group from the dropdown menu (nr.4).

.. image:: images/profile_manager2.png
  :width: 800
  :alt:

An example CSV file used to create a custom profile is shown below.

.. image:: images/profile_manager4.png
  :width: 800
  :alt:

In this example, a custom profile will be added to a project group (nr.5). Select whether the profile values should be averaged or summed over time (depending on the unit the values represent) (nr.6), and click on *Select files* (nr.7) to select the desired files to be uploaded.

.. image:: images/profile_manager3.png
  :width: 800
  :alt:

If a profile is successfully uploaded, a message is displayed on the window.

.. image:: images/profile_manager5.png
  :width: 800
  :alt:

Once a profile is uploaded, it can be added to an asset's port by selecting it from the *Profile class* dropdown menu.

.. image:: images/profile_manager6.png
  :width: 800
  :alt:

Deleting profiles
-----------------

To delete an uploaded file, navigate again to *Profiles plugin* by clicking on *View* menu item on the menu bar (nr.1), and going to *Settings* (nr.2).

.. image:: images/profile_manager8.png
  :width: 800
  :alt:

Select *Delete profiles* (nr.1), scroll down to the profile created above (nr.2), and click on *Delete profiles* (nr.3).

.. image:: images/profile_manager9.png
  :width: 800
  :alt:
