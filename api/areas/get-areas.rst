List Project Groups :code:`GET /areas/{projectId}`
==========================================================

Get a list of groups in :doc:`Project </api/project/index>`

Request
-------

.. code-block:: bash

    curl https://www.testomato.com/api/areas/{projectId}?{apikey=value}

Request Parameters
~~~~~~~~~~~~~~~~~~

============== =================================================================
Parameter      Description
============== =================================================================
projectId      Your project ID (*required*)
apikey         An API key unique to each project (*required*)
============== =================================================================

Response
--------

.. literalinclude:: get-areas.json
   :language: json
