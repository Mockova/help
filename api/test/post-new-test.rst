Create page check :code:`POST /test`
====================================

Create new page check with rules.

Request
-------

.. code-block:: bash

    curl -X POST -H 'Content-Type: application/json' \
    -d '{"name":"My Test", "url":"http://mysite.com/checked-page", "rules": []}' \
    'https://www.testomato.com/api/test/?projectId={projectId}&areaId={areaId}&apikey={apikey}'

Request Parameters
~~~~~~~~~~~~~~~~~~

============== =================================================================
Parametter     Description
============== =================================================================
projectId      Your project ID (*required*)
areaId         Group ID (see :doc:`How to get Group ID </api/areas/get-areas>`)
apikey         An API key unique to each project (*required*)
============== =================================================================

Request Body (JSON)
~~~~~~~~~~~~~~~~~~~

============== =================================================================
Field          Description
============== =================================================================
name           Name of the check (if skipped, a page title will be used)
url            URL of the page that will be checked
rules          An array of individual checks (*optional*)
options        Options_ for checks (*optional*)
============== =================================================================

.. code-block:: json

    {
      "name":"My Test",
      "url":"http://mysite.com/checked-page",
      "rules": [{
          "type": "text",
          "op": "match",
          "val": "testomato"
        }]
      }


Check syntax
~~~~~~~~~~~~

============== ================ ================================================
Field          Possible values	Description
============== ================ ================================================
type           * text           Text on page, HTML on page, HTTP status, HTTP
               * html           header or Redirect location
               * status
               * header
               * location

op             * eq             is equal to (only for HTTP status), contains or
               * sub            does not contain, equals, matches or does not
               * !sub           match, XPath (only for HTML)
               * eqs
               * match
               * !match
               * xpath

val            any string       Checked string, regex or XPath expression
============== ================ ================================================

Options
~~~~~~~

============== ================ ================================================
Field          Possible values	Description
============== ================ ================================================
g              true | false     Do not accept gzip encoding (default false)
l              true | false     Do not follow redirects (default false)
6              true | false     Only IPv6 (default false)
w              any string       Extra HTTP headers
============== ================ ================================================
