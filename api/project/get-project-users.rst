Get Project Users and Their Roles :code:`GET /project/{projectId}/users`
========================================================================

Request
-------
.. code-block:: bash

    curl "https://www.testomato.com/api/project/{projectId}/users?{apikey=value}"

Request Parameters
~~~~~~~~~~~~~~~~~~

============== =================================================================
Parameter      Description
============== =================================================================
projectId      Your project ID or project name (*required*)
apikey         An API key unique to each project (*required*)
============== =================================================================

Response
--------

.. literalinclude:: get-project-users.json
   :language: json
