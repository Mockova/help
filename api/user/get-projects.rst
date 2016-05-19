GET User projects
=================

Return list of all User Projects

Request
-------

:code:`GET /user/{id}/projects`

.. code-block:: bash

    curl https://www.testomato.com/api/user/{id}/projects?{apikey=value}

Request Parameters
~~~~~~~~~~~~~~~~~~

============== =================================================================
Parametter     Description
============== =================================================================
id             Your user ID (*required*)
apikey         An API key unique to each user (*required*)
============== =================================================================

Response
--------

.. literalinclude:: /api/users/get-projects.json
   :language: json
