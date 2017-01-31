API consumption in command line interface
=========================================

Here is a script for server to server API usage in bash :

.. code-block:: bash

    $ wget [url script]
    Usage: ./adback-refresh-tags [token] [options]

    Options :
    -c : output custom message script (JS output)
    -a : output analytics script (JS output)
    -html : change the output method (html output)

Crontab that update js tag every 6 hours :

.. code-block:: bash

    $ 0 */6 * * * /usr/bin/bash [path to script] [token]  > [your js file]
