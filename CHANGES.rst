CHANGES
=======

master (unreleased)
-------------------

0.1.2 (2012.04.13)
------------------

* Added the ``SECURE_HSTS_INCLUDE_SUBDOMAINS`` setting. Thanks Paul McMillan
  for the report and Donald Stufft for the patch. Fixes #13.

* Added the ``X-XSS-Protection: 1; mode=block`` header. Thanks Johannas Heller.


0.1.1 (2011.11.23)
------------------

* Added the ``X-Content-Type-Options: nosniff`` header. Thanks Johannas Heller.

* ``SECURE_PROXY_SSL_HEADER`` setting now patches ``request.is_secure()`` so it
  respects proxied SSL, to avoid redirects to http that should be to https.


0.1.0 (2011.05.29)
------------------

* Initial release.

