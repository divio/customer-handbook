.. _knowledge-mirrors:

What are mirrors?
=================

A mirror is a duplicate of a project that shares its codebase with the original project while independently setting up
its own database and media storages.

Here are some advantages that mirroring a project provides. 

* As long as a project is deployed, you can create a mirror anytime even if the project is not in its final stage as you
  can always update mirrors with the original project.
* For product companies who would like to provide a standalone instance of their product to different customers as
  mirrors can provide

    * flexible options for development/production workflows. e.g. a development of the base project can be maintained
      with a complex dataset for testing, completely independent of its mirrors.
    * strict synchronisation of codebase, but completely separate billing, user access and so on; 
    * complete isolation of data/storage between mirrors and their original.

* For multisite projects:

    * instead of managing sites separately which is too cumbersome and inefficient, mirrors are centralized and can be
      managed from the original project
    * significant reduction in time, maintenance and most of all the cost of implementation of design and integration
    * consistency across brands especially for franchisee sites
    * many resources can be distributed efficiently such as press releases and other organisation information
    * each mirror also enjoys setting up its own database and object storage independently to perform its unique duties.
    
You may refer to :ref:`running multisite applications <knowledge-multi-site-applications>` as well as :ref:`how to
create a multi-site Django project using mirrors <multisite-mirrors>` in our developer handbook.

Hence, mirrors can provide great solutions for the current complex and multifaceted digital world.
