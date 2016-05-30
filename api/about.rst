About API
=========

Testomato  `REST <https://en.wikipedia.org/wiki/Representational_state_transfer>`_
API provides simple interfaces for Testomato functionality. To use a REST API,
your application makes an HTTP request and parses the JSON formatted response.

The API can be used to do the following with continuous integration:

* Starting a project
* Getting project information
* Reading project results

How to Access the Testomato API
-------------------------------

All API endpoints require authentication via an API key. Each project has its
own unique API key that protects your data against unwanted access. An API key
parameter is mandatory in all requests.

You can find your API Key at the bottom of the Settings tab in your
project dashboard:

.. toctree::
   :maxdepth: 1
   :caption: Testomato API
   :glob:

   api/**/index
   api/common
