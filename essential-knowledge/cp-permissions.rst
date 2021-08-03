.. _knowledge-cp-permissions:

Control panel permissions reference
====================================

The following table shows the different permission options for the different
types of users with respect to addons, boilerplates and applications.


.. list-table:: Addons
  :widths: 20 20 20 20 20 20 25
  :header-rows: 1
 
  * - User level
    - Create new addon
    - Manage addon settings
    - Manage addon collaborators
    - Upload new addon version
    - Install/upgrade to a project [#f1]_ 
    - Manage settings on a project [#f1]_ 

  * - Anyone
    -
    -
    -
    - 
    - Only for public addons
    - Only for already installed addons

  * - Organisation collaborator
    - Added as collaborator with "can update"
    -
    -
    - 
    - Only for public addons
    - Only for already installed addons

  * - Addon collaborator
    - n/a
    -
    -
    -
    -
    - 

  * - Addon collaborator with "can update"
    - n/a
    -
    - (can also remove themselves?)
    -
    -
    - 
  * - Organisation owner/admin
    - 
    -
    -
    -
    - 
    - 



.. list-table:: Boilerplates
  :widths: 20 20 20 20 20 25
  :header-rows: 1
 
  * - User level
    - Create new boilerplate
    - Manage boilerplate settings
    - Manage boilerplate collaborators
    - Upload new boilerplate version
    - Create a project with boilerplate

  * - Anyone
    -
    -
    -
    - 
    - Only for public boilerplate

  * - Organisation collaborator
    - Added as collaborator with "can update"
    -
    -
    - 
    - Only for public boilerplate

  * - Boilerplate collaborator
    - n/a
    -
    -
    -
    - 

  * - Addon collaborator with "can update"
    - n/a
    -
    - (can also remove themselves?)
    -
    -

  * - Organisation owner/admin
    - 
    -
    -
    -
    - 


.. list-table:: Applications
  :widths: 20 20 20 20
  :header-rows: 1
 
  * - User level
    - Create new application
    - Manage application settings
    - Manage collaborators

  * - Anyone
    -
    -
    -

  * - Organisation collaborator
    - Added as collaborator
    -
    - 

  * - Organisation owner/admin
    - 
    -
    - 


Addons
------

+---------------+-------------+--------------+---------------+---------------+-------------------+------------------+
| User level    |  Create new | Manage addon | Manage addon  | Upload new    |Install/ upgrade to|Manage settings on| 
|               |  addon      | settings     | collaborators | addon version |a project [#f1]_   |a project [#f1]_  |
+===============+=============+==============+===============+===============+===================+==================+
| Anyone        |             |              |               |               | Only for public   | Only for already |
|               |             |              |               |               | addons            | installed addons |
+---------------+-------------+--------------+---------------+---------------+-------------------+------------------+
| Organisation  |Added as     |              |               |               | Only for public   | Only for already |
| collaborator  |collaborator |              |               |               | addons            | installed addons |
|               |with "can    |              |               |               |                   |                  |
|               |update"      |              |               |               |                   |                  |
+---------------+-------------+--------------+---------------+---------------+-------------------+------------------+
| Addon         | n/a         |              |               |               |                   |                  |
| collaborator  |             |              |               |               |                   |                  |
+---------------+-------------+--------------+---------------+---------------+-------------------+------------------+
| Addon         | n/a         |              | can also      |               |                   |                  |
| collaborator  |             |              | remove        |               |                   |                  |
| with "can     |             |              | themselves    |               |                   |                  |
| update"       |             |              |               |               |                   |                  |
+---------------+-------------+--------------+---------------+---------------+-------------------+------------------+
| Organisation  |             |              |               |               |                   |                  |
| owner/admin   |             |              |               |               |                   |                  |
+---------------+-------------+--------------+---------------+---------------+-------------------+------------------+


Boilerplates
------------

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
------------

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




.. rubric:: Footnotes

.. [#f1] Access to a project is a prerequisite for this action.


.. only:: Internal

 For migration:

 Add owners as *Collaborators with "can update"* if they are not an admin of the organisation already.
