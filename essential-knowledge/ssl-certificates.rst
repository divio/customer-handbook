.. _knowledge-ssl-certificates:

SSL certificates and HTTPS on Divio projects
=============================================


SSL allows you to serve your sites using HTTPS, giving your users a guarantee of data integrity and privacy when they
visit.

We provide SSL certificates free and by default. All Divio sites can be accessed using the HTTPS protocol instead of
plain HTTP.


Renewal
--------

Certificates have a 90-day lifetime, and are renewed automatically 40 days before expiry.


Custom certificates
--------------------

If you have your own certificate, this can be applied to sites with eligible subscriptions - just drop us a line and
we'll set it all up for you.


HTTPS redirects
----------------

By default, we don't redirect HTTP users to HTTPS, because for some cases this might not be appropriate. However unless
you have a good reason not to, we advise that you set this up for your site, so that when your visitors arrive on a url
such as http://example.com/ they will be redirected to https://example.com/.

.. seealso:: How to set up HTTPS redirects in:

  * :ref:`HTTP redirects <developer:redirects>`
  * :ref:`Aldryn Django projects <developer:django_protocol_redirects>`
  * :ref:`Express.js applications <developer:how-to-express-js-https>`
