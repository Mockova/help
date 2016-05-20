Get project users and their Roles :code:`GET /project/{projectId}/users`
========================================================================

Request
-------
.. code-block:: bash

    curl "https://www.testomato.com/api/project/{projectId}/users?{apikey=value}"

Request Parameters
~~~~~~~~~~~~~~~~~~

============== =================================================================
Parametter     Description
============== =================================================================
projectId      Your project ID or project name (*required*)
apikey         An API key unique to each project (*required*)
============== =================================================================

Response
--------

.. literalinclude:: /api/project/get-project-users.json
   :language: json
