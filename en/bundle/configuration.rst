Configuration
=============

Base parameters
---------------

.. code-block:: yaml

    dekalee_adback_analytics:
        access_token: your-token
        cache_service: your.redis.service

Getting your token
------------------

You can generate a token on the AdBack website :

1. Log in
2. Go on the `Api Access`_ page
3. Generate a token for the api client linked to your website

Cache service
-------------

To avoid any slow down of your application, the bundle uses some local cache to store the gathered informations.

The bundle already provides a driver for ``Redis``. You could only specify your redis service to make it work directly.
If you want to use another local cache service, you could check `how to implement a new driver`_.

.. _`Api Access`: https://www.adback.co/fr/admin/api/
.. _how to implement a new driver: cache_storage
