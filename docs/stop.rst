.. _stop-pensando-elk:

Stop
======================

To stop the cluster from running, issue the following command in the install-dir

.. code-block:: bash

    docker-compose down


This will stop the following containers:

- pensando-elasticsearch
- pensando-kibana
- pensando-logstash

To see if all of the containers are stopped, you can issue the following command:

.. code-block:: bash

    docker ps

You should not have any containers running. [1]_



.. [1] If this system has other containers, you may have output but hopefully not any of the above pensando-elk containers.
