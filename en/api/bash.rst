API consumption in command line interface
=================

Here is a sample script for server to server API usage :

.. code-block:: bash
    $ wget [url script]
    $ ./adback-refresh-tags [token] [options]
    
Crontab update command :

.. code-block:: bash
    $ 0 */6 * * * /usr/bin/bash [path to script] [token]  > [your js output file]
