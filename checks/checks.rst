What Are Checks?
===============

With Testomato, you can check your page content for the following:

Common server error messages
----------------------------

Testomato is sensitive to follow *Common Error Messages*, they are marker for us,
that something is broken on website.

* All types of PHP error messages
* `All MySQL error messages <https://dev.mysql.com/doc/refman/5.5/en/error-messages-server.html>`_
* `XDebug output <https://xdebug.org/>`_
* `Nette/Tracy debug output <https://github.com/nette/tracy>`_
* Database connection errors
* Blank page (page without content)

HTTP Status Codes
-----------------

* 200 OK
* 301 Moved Permanently
* 302 Found
* 303 See Other
* 307 Temporary Redirect
* 403 Forbidden
* 404 Not Found
* 405 Method Not Allowed
* 500 Internal Server Error
* 501 Implemented
* custom status code

Get more information about `HTTPS Status Codes <https://en.wikipedia.org/wiki/List_of_HTTP_status_codes>`_.

.. image:: /dashboard/http-status-codes.png
   :alt: HTTP Status Codes
   :align: center

Other Ways to Use checks
------------------------

* Text on page
* HTML on page
* HTTP header content

.. image:: /dashboard/text-on-page.png
   :alt: Check for text on Page
   :align: center

.. note:: These checks are case sensitive, so make sure you PaY ClosE AtTentioN to the text you enter.
