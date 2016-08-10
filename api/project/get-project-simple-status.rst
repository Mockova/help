Read Project State :code:`GET /project/{id}/simple-status`
========================================================================

Request
-------
.. code-block:: bash

    curl "https://www.testomato.com/api/project/{id}/simple-status?{apikey=value}"

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

.. literalinclude:: get-project-simple-status.json
   :language: json
