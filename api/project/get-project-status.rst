Read project status :code:`GET /project/{id}/status`
========================================================================

Request
-------
.. code-block:: bash

    curl "https://www.testomato.com/api/project/{id}/status?{apikey=value}"

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

.. literalinclude:: /api/project/get-project-status.json
   :language: json
