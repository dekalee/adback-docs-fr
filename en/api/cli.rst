API consumption in command line interface
=========================================

Here is a script for server to server API usage in bash :

.. code-block:: bash

    $ wget https://raw.githubusercontent.com/dekalee/adback-bash-refresh/master/adback-refresh-tags
    $ chmod +x adback-refresh-tags
    $ ./adback-refresh-tags [token] [options]


Options :
---------

- -c : output custom message script (JS output)
- -a : output analytics script (JS output)
- -html : change the output method (html output)


Crontab that update js tag every 6 hours :

.. code-block:: bash

    $ 0 */6 * * * /usr/bin/bash [path to script] [token] [options]  > [your output file]
