Read Project Information :code:`GET /project/{id}/`
===================================================

Read information about a project.

Request
-------

.. code-block:: bash

   curl "https://www.testomato.com/api/project/{id}/?{apikey=value}"

Request Parameters
~~~~~~~~~~~~~~~~~~

============== =================================================================
Parameter      Description
============== =================================================================
id             Your project ID or project name (**required**)
apikey         An API key unique to each project (*required*)
============== =================================================================

Response
--------

.. literalinclude:: get-project.json
   :language: json
