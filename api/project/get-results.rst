Read Project Results :code:`GET /project/{id}/job/{jobid}/results`
==================================================================

Return Project Results

Request
-------

.. code-block:: bash

   curl "https://www.testomato.com/api/project/{id}/job/{jobid}/results?{apikey=value}"

Request Parameters
~~~~~~~~~~~~~~~~~~

============== =================================================================
Parametter     Description
============== =================================================================
id             Your project ID or project name (*required*)
jobid          A selected job ID (*required*)
apikey         An API key unique to each project (*required*)
============== =================================================================

Response
--------

.. literalinclude:: get-results.json
   :language: json

Response Parameters
~~~~~~~~~~~~~~~~~~~

============== =================================================================
Parametter     Description
============== =================================================================
jobId          A unique project job ID
startedAt      Time when job started (unix timestamp)
duration       Duration of the job
total          The total number of tests performed
failed         The number of failed tests
areas          List of protected areas IDs
results        Array of test results – each result has a testId, testName etc.
============== =================================================================
