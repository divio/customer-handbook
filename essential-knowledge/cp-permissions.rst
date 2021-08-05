.. _knowledge-cp-permissions:


.. # For the "X" symbol

.. include:: <isogrk1.txt> 


.. # For the "check" mark 

.. include:: <isopub.txt> 

.. raw:: html

  <style>

    /* Addons */

    table.addons th {
    background-color: darkgray;
    }

    table.addons tr:nth-child(1), tr:nth-child(2), tr:nth-child(3) {
    background-color: lightcoral;
    }

    table.addons td:nth-child(6), td:nth-child(7), tr:nth-child(2) td:nth-child(2), tr:nth-child(4), tr:nth-child(5){
    background-color: lightgreen;
    }

    table.addons tr:nth-child(1) td:nth-child(6), tr:nth-child(2) td:nth-child(6){
    background-color: lemonchiffon;
    }

    table.addons tr td:first-child {
    background-color: white;
    }
    
    table.addons tr:nth-child(3) td:nth-child(2), table.addons tr:nth-child(4) td:nth-child(2) {
    background-color: lightgray;
    }

    table.addons tr:nth-child(2n) td:first-child {
    background-color: whitesmoke;
    }
  

    /* Boilerplates */

    table.boilerplates th {
    background-color: darkgray;
    }

    table.boilerplates tr:nth-child(1), tr:nth-child(2), tr:nth-child(3) {
    background-color: lightcoral;
    }

    table.boilerplates tr:nth-child(2) td:nth-child(2), tr:nth-child(3) td:nth-child(6), tr:nth-child(4), tr:nth-child(5){
    background-color: lightgreen;
    }

    
    table.boilerplates tr:nth-child(1) td:nth-child(6), table.boilerplates tr:nth-child(2) td:nth-child(6){
    background-color: lemonchiffon;
    }

    table.boilerplates tr td:first-child {
    background-color: white;
    }
    
    table.boilerplates tr:nth-child(3) td:nth-child(2), table.boilerplates tr:nth-child(4) td:nth-child(2) {
    background-color: lightgray;
    }

    table.boilerplates tr:nth-child(2n) td:first-child {
    background-color: whitesmoke;
    }
    

    /* Applications */

    table.applications th {
    background-color: darkgray;
    }

    table.applications tr:nth-child(1), tr:nth-child(2) {
    background-color: lightcoral;
    }

    table.applications tr:nth-child(2) td:nth-child(2), tr:nth-child(3), tr:nth-child(4) {
    background: lightgreen;
    }
    
    table.applications tr td:first-child {
    background-color: white;
    }
    
    table.applications tr:nth-child(3) td:nth-child(2) {
    background-color: lightgray;
    }
    
    table.applications tr:nth-child(2n) td:first-child {
    background-color:whitesmoke;
    }

  </style>


Control panel permissions reference
===================================

The following table shows the different permission options for the different
types of users with respect to addons, boilerplates and applications.


Addons
------

.. list-table::
  :widths: 20 30 20 20 20 25 30
  :header-rows: 1
  :class: addons

  * - User level
    - Create new addon
    - Manage addon settings
    - Manage addon collaborators
    - Upload new addon version
    - Install/ upgrade to a project [#f1]_ 
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
  :widths: 30 20 20 20 20 25
  :header-rows: 1
  :class: boilerplates

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
  :class: applications
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

