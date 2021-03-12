.. _how-to-duplicate-project:

How to duplicate a project
==========================

To help you re-use work and speed up your workflow, Divio offers multiple options for project duplication - Copy, Fork
and Mirror.

You might want to duplicate a project for a number of reasons, for example:

* to explore radical changes or development that you don't want to do on the original
* to prepare the launch of site-wide development or content changes, without disturbing the original
* to punch out a completely new project, based on an original
* to provide team members or clients with an exact copy of a project for training purposes


Select your duplication option
------------------------------

To duplicate a project, select *Duplicate* from the project's options menu, in the organisation view:

.. image:: /images/options-menu-organisations-view.png
   :alt: 'options menu'
   :width: 685

or in the project view:

.. image:: /images/options-menu-project-view.png
   :alt: 'options menu'
   :width: 690

You need to give the duplicate a name, and decide whether to duplicate the project to the same organisation or a
different organisation.

From the *Copy type* select the appropriate duplication action: *Copy*, *Fork* or *Mirror*.


Copy, Fork, Mirror
~~~~~~~~~~~~~~~~~~~

Copy
^^^^

A copy is the simplest form of duplication. The new project will be an exact but independent copy of the original, and
will include its code, database content, media and environment variables.

A copy preserves the Test server's Git branch only; all other branches are discarded.


Fork
^^^^

A fork is similar to a copy, with the distinction that the new project retains the original's Git history in its
codebase.

A fork is therefore useful when you want a duplicate in order to undertake substantial new development, as it allows you
to merge back changes from the duplicate into the original using Git.

A fork will include all the branches of the original.


Mirror
^^^^^^

A mirror, unlike a copy and a fork, is dependent on the original it is created from. A mirror shares its codebase with
the original.  Whatever changes made to the codebase of the original will also be applied to each mirror.

Mirrors are useful when you have a large number of franchise-type sites that share exactly the same functionality.
Rather than needing to make, test and deploy the same changes hundreds of times, the mirror functionality allows you to
do this just once, on the original, and then deploy the changes to all the mirrors.


Select subscription options
---------------------------

After creating the duplicate, you will need to select a suitable subscription.
