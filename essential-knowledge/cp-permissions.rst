.. _knowledge-cp-permissions:

Control panel permissions reference
====================================

The following table shows the different permission options for the different
types of users with respect to addons, boilerplates and applications.


Addons
----------

+---------------+-------------+--------------+---------------+---------------+-----------------+-----------------+
| User level    |  Create new | Manage addon | Manage addon  | Upload new    | Install/upgrade | Manage settings | 
|               |  addon      | settings     | collaborators | addon version | to a project*   | on a project*   |
+===============+=============+==============+===============+===============+=================+=================+
| Anyone        |             |              |               |               | Only for public | Only for already|
|               |             |              |               |               | addons          | installed addons|
+---------------+-------------+--------------+---------------+---------------+-----------------+-----------------+
| Organisation  |Added as     |              |               |               | Only for public | Only for already|
| collaborator  |collaborator |              |               |               | addons          | installed addons|
|               |with "can    |              |               |               |                 |                 |
|               |update"      |              |               |               |                 |                 |
+---------------+-------------+--------------+---------------+---------------+-----------------+-----------------+
| Addon         | n/a         |              |               |               |                 |                 |
| collaborator  |             |              |               |               |                 |                 |
+---------------+-------------+--------------+---------------+---------------+-----------------+-----------------+
| Addon         | n/a         |              | can also      |               |                 |                 |
| collaborator  |             |              | remove        |               |                 |                 |
| with "can     |             |              | themselves    |               |                 |                 |
| update"       |             |              |               |               |                 |                 |
+---------------+-------------+--------------+---------------+---------------+-----------------+-----------------+
| Organisation  |             |              |               |               |                 |                 |
| owner/admin   |             |              |               |               |                 |                 |
+---------------+-------------+--------------+---------------+---------------+-----------------+-----------------+

*Access to a project is a prerequisite for this action.


Boilerplates
-------------

+---------------+-------------+--------------+---------------+---------------+-----------------+
| User level    | Create new  | Manage       | Manage        | Upload new    | Create          | 
|               | boilerplate | boilerplate  | boilerplate   | boilerplate   | project with    |
|               |             | settings     | collaborators | version       | boilerplate     |
+===============+=============+==============+===============+===============+=================+
| Anyone        |             |              |               |               | Only for public |
|               |             |              |               |               | boilerplate     |
+---------------+-------------+--------------+---------------+---------------+-----------------+
| Organisation  |Added as     |              |               |               | Only for public |
| collaborator  |collaborator |              |               |               | boilerplate     |
|               |with "can    |              |               |               |                 |
|               |update"      |              |               |               |                 |
+---------------+-------------+--------------+---------------+---------------+-----------------+
| Boilerplate   | n/a         |              |               |               |                 |
| collaborator  |             |              |               |               |                 |
+---------------+-------------+--------------+---------------+---------------+-----------------+
| Boilerplate   | n/a         |              | can also      |               |                 |
| collaborator  |             |              | remove        |               |                 |
| with "can     |             |              | themselves    |               |                 |
| update"       |             |              |               |               |                 |
+---------------+-------------+--------------+---------------+---------------+-----------------+
|  Organisation |             |              |               |               |                 |
|  owner/admin  |             |              |               |               |                 |
+---------------+-------------+--------------+---------------+---------------+-----------------+


Applications
-------------

+---------------+------------+--------------+---------------+
| User level    | Create new | Manage       | Manage        |
|               | application| application  | collaborators |
+===============+============+==============+===============+
| Anyone        |            |              |               |
+---------------+------------+--------------+---------------+
| Organisation  |Added as    |              |               |
| collaborator  |collaborator|              |               |
+---------------+------------+--------------+---------------+
| Applications  | n/a        |              |               |
| collaborator  |            |              |               |
+---------------+------------+--------------+---------------+
|  Organisation |            |              |               |
|  owner/admin  |            |              |               |
+---------------+------------+--------------+---------------+

.. note:: For migration:

 Add owners as *Collaborators with "can update"* if they are not an admin of the organisation already.
