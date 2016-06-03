List User Projects :code:`GET /user/{id}/projects`
=================================================

Get a list of all user projects.

Request
-------

.. code-block:: bash

    curl https://www.testomato.com/api/user/{id}/projects?{apikey=value}

Request Parameters
~~~~~~~~~~~~~~~~~~

============== =================================================================
Parameter      Description
============== =================================================================
id             User ID (*required*)
apikey         An API key unique to each user (*required*)
============== =================================================================

Response
--------

.. literalinclude:: get-projects.json
   :language: json
