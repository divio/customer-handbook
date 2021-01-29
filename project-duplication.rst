.. _project-duplication:

Duplicating projects
====================

Why duplication is useful
-------------------------

You might want to duplicate a project for a number of reasons, for example:

* to explore radical changes or development that you don't want to do on the original
* to prepare the launch of site-wide development or content changes, without disturbing the original
* to punch out a completely new project, based on an original
* to provide team members or clients with an exact copy of a project for training purposes

Refer here to see :ref:`how to duplicate a project <copy-project>`.

The three different ways of duplicating a project
-------------------------------------------------

Copy
~~~~

A copy is the simplest form of duplication. The new project will be an exact but independent copy of the original,
and will include its code, database content, media and environment variables.
A copy preserves the Test server's Git branch only; all other branches are discarded.

Fork
~~~~

A fork is similar to a copy, with the distinction that the new project retains the original's Git history in its codebase.
A fork is therefore useful when you want a duplicate in order to undertake substantial new development,
as it allows you to merge back changes from the duplicate into the original using Git.
A fork will include all the branches of the original.

Read more about `How to use Git <https://docs.divio.com/en/latest/how-to/use-git/>`_ and 
`How to configure  Git hosting <https://docs.divio.com/en/latest/how-to/resources-configure-git/>`_ in Divio projects.

Mirror
~~~~~~

Whereas copies and forks exist independently of the original they were created from, a mirror remains dependent upon the original,
and shares its codebase. Whatever changes made to the codebase of the original will also be applied to those of each mirror. 
This is useful when you have a large number of franchise-type sites that share exactly the same functionality.
Rather than needing to make, test and deploy the same changes hundreds of times, the mirror functionality allows you to do this just once,
on the original, and then deploy the changes to all the mirrors.
