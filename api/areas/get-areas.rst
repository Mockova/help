List Project Areas (groups) :code:`GET /areas/{projectId}`
==========================================================

Get a List of Areas (groups) in a :doc:`Project </api/project/index>`

Request
-------

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

.. literalinclude:: get-areas.json
   :language: json
