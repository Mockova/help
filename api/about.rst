Testomato API
=============

Testomato  `REST <https://en.wikipedia.org/wiki/Representational_state_transfer>`_
API provides simple interfaces for Testomato functionality. To use a REST API,
your application makes an HTTP request and parses the JSON formatted response.

The API can be used to do the following with continuous integration:

* Starting a project
* Getting project information
* Reading project results

.. contents:: In this article
   :local:
   :depth: 1

How to Access the Testomato API
-------------------------------

All API endpoints require authentication via an API key. Each project has its own unique API key that protects your data against unwanted access. An API key parameter is mandatory in all requests.

You can find your API Key at the bottom of the Settings tab in your project dashboard:

Apimato
------

Apimato is a command line tool written in PHP/Python for the purpose of executing Testomato API tasks. For more information, please visit Apimato GitHub Repository.

How to Install Apimato

The best way to install Apimato is to download the latest package using Composer:

.. code-block:: bash

    php composer.phar require testomato/apimato

or

.. code-block:: bash

    git clone git@github.com:testomato/apimato.git

How to Use Apimato
------------------

Run the following from the PHP/Python command line:

.. code-block:: bash

    php apimato -h   # for php version
    apimato -h       # for python version
