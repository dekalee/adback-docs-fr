Cache storage
=============

If you don't want to use ``Redis`` as the default cache storage, you can create
a new driver which implements the ``Dekalee\AdbackAnalytics\Driver\ScriptCacheInterface``.

After creating your service, you have to add the alias ``dekalee_adback_analytics.script_cache``.
