.. _backup-project:

How to use our backup system
============================

Your backups are available from the *Backups* view of your project. 
It shows the Scheduled and On-demand backups that have been created.

In each case, the backups page will list when and what was backed up, with additional information and options to restore or download the backup. The On-demand view will also provide options to create new backups.

How to create backups
---------------------

* **Scheduled backups** are made according to the project's backup schedule, and require no intervention from the user.

* **On-demand backups** can be made whenever you require.

See also further information on `Divio backup system <../project-backups>`_.

To create a backup, from the *Backups* view of your project, 

* select *CREATE BACKUP ON DEMAND* for the server you want to backup
* choose what to backup: *database*, *media* or both
* hit **Create backup** (you may add a note to the backup)

The backup will appear in your list of *Backups*, once complete.

How to work with existing backups
---------------------------------

Each backup in the list of *Backups* has a date and time of the backup and 
shows whether it is media, database or both with their sizes among other things. 
You can also select a particular backup to view a more detailed information. 
More importantly, each backup has 

* a *Restore* option and

* an *options menu*, for further actions, such as *Prepare download*.

The Restore option
^^^^^^^^^^^^^^^^^^

The Restore functionality gives you flexibility. You can choose what to restore 
(database or media) and its destination (project and environment).

.. warning::

   A restore operation will overwrite content at the destination. 
   Take a backup before restoring unless you are sure you will no longer need that content.


The Download option
^^^^^^^^^^^^^^^^^^^

To download a backup to your own computer, select *Prepare download* from the action menu and 
choose the content you want to download. The files will be prepared asynchronously, and 
an email message containing links to the database and/or media files will be sent to you when they are ready.

The database will be made available in the form of a *binary Postgres database dump*.

The media files will be made available as a *tarred archive*, and will include a manifest file listing contents.
