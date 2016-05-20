Start Project Checks :code:`GET /project/{id}/start?{apikey=value}`
===================================================================

Run Project Checks and return results URL.

Request
-------

.. code-block:: bash

   curl "https://www.testomato.com/api/project/{id}/start?{apikey=value}"

Request Parameters
~~~~~~~~~~~~~~~~~~

============== =================================================================
Parametter     Description
============== =================================================================
id             Your project ID or project name (*required*)
apikey         An API key unique to each project (*required*)
============== =================================================================

Response
--------

.. literalinclude:: /api/project/get-start-project.json
   :language: json

Response Parameters
~~~~~~~~~~~~~~~~~~~

============== =================================================================
Parametter     Description
============== =================================================================
projectId      A unique project ID
jobId	         A unique ID for each project job
start	         **ok** means your tests have successfully started
results	       The URL where you can view your results
============== =================================================================
