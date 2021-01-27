.. _ram-storage-policy:

Divio policy and technical constraints on RAM, storage and other services
=========================================================================

Divio’s soft limit
------------------

Divio operates on soft limits to make sure your website stays online.
Even if you exceed the limits of your subscription, your service won't be interrupted. 
If your project consistently consumes more than your plan, we'll get in touch to discuss options.

CDN and transfer volume calculations
------------------------------------

Divio projects automatically use CDN (content delivery networks) to optimise delivery of files from our site to your users.

Your project's transfer volume will be calculated only on the traffic that we serve to the CDN - 
not the traffic that the CDN serves to your users.

Project Git repository size
---------------------------

We don't impose limits on the size of your project's Git repository. 
However, as its size increases, both our infrastructure and Git itself have to work harder to manage it.

Above 100MB for its Git repository, we cannot guarantee that a project will function smoothly, 
especially when our platform is under heavy load. It can cause:

* slower deployments
* deployment timeouts
* long backup times

If your project's Git repository, including its history, exceeds 800 MB you are likely to run into persistent deployment problems.

If you need to store large amounts of data, please use the dedicated media  directory, which uses S3 for storage.

See also `How to interact with your project’s media storage <https://docs.divio.com/en/latest/how-to/interact-storage/>`_  
in our `Developer Handbook <https://docs.divio.com/en/latest/>`_.
