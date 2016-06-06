
Common Server Error Messages
============================

Testomato is sensitive to **Common Error Messages**. They are a marker for us to indicate
that something is broken on your website.

PHP Errors
----------

Testomato is sensitive to **all types of PHP error messages**:

* :code:`Fatal error`
* :code:`Catchable fatal error`
* :code:`Warning`
* :code:`Parse error`,
* :code:`Notice`
* :code:`Strict Standards`
* :code:`Deprecated`,
* :code:`Unknown error`

Database Errors
---------------

* `All MySQL error messages <https://dev.mysql.com/doc/refman/5.5/en/error-messages-server.html>`_
* Database connection errors:
   * :code:`The server encountered an internal error`
   * :code:`Internal server error`
   * :code:`Can't connect to MySQL server`
   * Nette :code:`Your browser sent a request that this server could not understand or process`
   * Wordpress :code:`Error establishing a database connection`

PHP Debuggers
-------------

XDebug
~~~~~~

.. figure:: xdebug.png
   :align: center
   :alt: Xdebug error

   `XDebug output <https://xdebug.org/>`_ example.

Tracy
~~~~~

.. figure:: tracy.png
   :align: center
   :alt: Tracy Error Message

   `Nette/Tracy <https://github.com/nette/tracy>`_ bluescreen example

Symfony
~~~~~~~

.. figure:: symfony.png
   :align: center
   :alt: Symfony error

   `Symfony <https://symfony.com/>`_ error pages example

Others
------

* `Phusion Passenger <https://www.phusionpassenger.com/>`_ errors
* Blank page (page without any content)

.. note:: We have an example page that shows randomly generated examples of some of the most common error messages: https://www.testomato.com/example/error.php
