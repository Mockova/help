Read Project Information :code:`GET /project/{id}/`
===================================================

This endpoint return Project Information

Request
-------

.. code-block:: bash

   curl "https://www.testomato.com/api/project/{id}/?{apikey=value}"

Request Parameters
~~~~~~~~~~~~~~~~~~

============== =================================================================
Parametter     Description
============== =================================================================
id             Your project ID or project name (**required**)
apikey         An API key unique to each project (*required*)
============== =================================================================

Response
--------

.. literalinclude:: /api/project/get-results.json
   :language: json
