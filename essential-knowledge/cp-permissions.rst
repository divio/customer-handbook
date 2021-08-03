.. _knowledge-cp-permissions:


.. # For the "X" mark

.. include:: <isogrk1.txt> 


.. # For the "Check" mark 

.. include:: <isopub.txt> 

Control panel permissions reference
===================================

The following table shows the different permission options for the different
types of users with respect to addons, boilerplates and applications.


Addons
------

.. list-table::
  :widths: 20 30 20 20 20 25 30
  :header-rows: 1

  * - User level
    - Create new addon
    - Manage addon settings
    - Manage addon collaborators
    - Upload new addon version
    - Install/upgrade to a project [#f1]_ 
    - Manage settings on a project [#f1]_ 

  * - Anyone
    - |KHgr|
    - |KHgr|
    - |KHgr|
    - |KHgr|
    - Only for public addons
    - |check| Only for already installed addons

  * - Organisation collaborator
    - |check| Added as collaborator with "Can update"
    - |KHgr|
    - |KHgr|
    - |KHgr|
    - Only for public addons
    - |check| Only for already installed addons

  * - Addon collaborator
    - n/a
    - |KHgr|
    - |KHgr|
    - |KHgr|
    - |check|
    - |check|

  * - Addon collaborator with "Can update"
    - n/a
    - |check|
    - |check|
    - |check|
    - |check|
    - |check|

  * - Organisation owner/admin
    - |check|
    - |check|
    - |check|
    - |check|
    - |check|
    - |check|


Boilerplates
------------

.. list-table::
  :widths: 20 20 20 20 20 25
  :header-rows: 1

  * - User level
    - Create new boilerplate
    - Manage boilerplate settings
    - Manage boilerplate collaborators
    - Upload new boilerplate version
    - Create a project with boilerplate

  * - Anyone
    - |KHgr|
    - |KHgr|
    - |KHgr|
    - |KHgr|
    - Only for public boilerplates

  * - Organisation collaborator
    - |check| Added as collaborator with "Can update"
    - |KHgr|
    - |KHgr|
    - |KHgr|
    - Only for public boilerplates

  * - Boilerplate collaborator
    - n/a
    - |KHgr|
    - |KHgr|
    - |KHgr|
    - |check|

  * - Boilerplate collaborator with "Can update"
    - n/a
    - |check|
    - |check|
    - |check|
    - |check|

  * - Organisation owner/admin
    - |check|
    - |check|
    - |check|
    - |check|
    - |check|


Applications
------------

.. list-table:: 
  :widths: 20 20 20 20
  :header-rows: 1

  * - User level
    - Create new application
    - Manage application settings
    - Manage collaborators

  * - Anyone
    - |KHgr|
    - |KHgr|
    - |KHgr|

  * - Organisation collaborator
    - |check| Added as collaborator
    - |KHgr|
    - |KHgr|

  * - Application collaborator 
    - n/a
    - |check|
    - |check|
    
  * - Organisation owner/admin
    - |check|
    - |check|
    - |check|


.. [#f1] Access to a project is a prerequisite for this action.

