
Common server error messages
============================

Testomato is sensitive to follow **Common Error Messages**, they are marker for us,
that something is broken on website.

* All types of PHP error messages
   * :code:`Fatal error`
   * :code:`Catchable fatal error`
   * :code:`Warning`
   * :code:`Parse error`
   * :code:`Notice`
   * :code:`Strict Standards`
   * :code:`Deprecated`
   * :code:`Unknown error`
* `All MySQL error messages <https://dev.mysql.com/doc/refman/5.5/en/error-messages-server.html>`_
* `XDebug output <https://xdebug.org/>`_
* `Symfony <https://symfony.com/>`_ error pages
* `Nette/Tracy debug output <https://github.com/nette/tracy>`_
* `Phusion Passenger <https://www.phusionpassenger.com/>`_ errors.
* Database connection errors:
   * :code:`The server encountered an internal error`
   * :code:`Internal server error`
   * :code:`Can't connect to MySQL server`
   * Nette :code:`Your browser sent a request that this server could not understand or process`
   * Wordpress :code:`Error establishing a database connection`
* Blank page (page without content)

We have an example page generate randomly some of common error messages:
* https://www.testomato.com/example/error.php

Testomato is sensitive for follow content:
