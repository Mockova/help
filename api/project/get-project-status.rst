Read Project State :code:`GET /project/{id}/status`
========================================================================

Request
-------
.. code-block:: bash

    curl "https://www.testomato.com/api/project/{id}/status?{apikey=value}"

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

.. literalinclude:: get-project-status.json
   :language: json
