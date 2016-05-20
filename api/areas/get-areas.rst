GET List of Groups
==================

Get a List of Groups in a Project

Request
-------

:code:`GET /areas/{projectId}`

.. code-block:: bash

    curl https://www.testomato.com/api/areas/{projectId}?{apikey=value}

Request Parameters
~~~~~~~~~~~~~~~~~~

============== =================================================================
Parametter     Description
============== =================================================================
projectId      Your project ID (*required*)
apikey         An API key unique to each project (*required*)
============== =================================================================

Response
--------

.. literalinclude:: /api/areas/get-areas.json
   :language: json
