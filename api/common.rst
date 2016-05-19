Common API Responses
====================

OK : Success response
~~~~~~~~~~~~~~~~~~~~~
.. code-block:: json

   {
       "message": "Success message",
       "code": 200,
       "ok": true,
       "error": false
   }

ERROR: Missing API endpoint
~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: json

    {
      "message": "API endpoint not found",
      "code": 404,
      "ok": false,
      "error": true
    }

ERROR: Invalid API key
~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: json

    {
      "message": "You don't have required permission to selected project.",
      "code": 401,
      "ok": false,
      "error": true
    }

ERROR: Project not found
~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: json

    {
	    "message": "Project \"xxxx\" not found.",
	    "code": 404,
	     "ok": false,
	    "error": true
	  }
