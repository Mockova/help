Check Examples
==============

Monitoring strings are one of Testomato's most versatile features, but one that
often gets overlooked.

There are a lot of ways to use strings in your checks that might not be obvious.
With that in mind, this article will show you a few ways you can use strings
to check your website.


Check for Facebook meta tags
----------------------------

Most content is shared to Facebook as a URL, so it's important that you mark up
your website with Open Graph tags to take control over how your content appears
on Facebook.

Check for all important graph meta tags:

================ ================ ==============================================
Source           Method           Rule
================ ================ ==============================================
HTML On Page     matches          :code:`<meta property="og:image"`
HTML On Page     matches          :code:`<meta property="og:type"`
HTML On Page     matches          :code:`<meta property="og:title"`
HTML On Page     matches          :code:`<meta property="og:description"`
HTML On Page     matches          :code:`<meta property="og:image"`
================ ================ ==============================================

Check for at last one of important meta tags:

================ ================ ==============================================
Source           Method           Rule
================ ================ ==============================================
HTML On Page     matches          :code:`<meta property="og:(url|type|title|description|image)"`
================ ================ ==============================================

More about `Open Graph Markup <https://developers.facebook.com/docs/sharing/webmasters#markup>`_.

Check if selected keyword are presents
--------------------------------------
Follow example will check if your page contains **meta tag** keywords with
at last *testing* and *testomato* in content.

================ ================ ==============================================
Source           Method           Rule
================ ================ ==============================================
HTML On Page     matches          :code:`<meta name="keywords" content=".*(testing|testomato).*">`
================ ================ ==============================================

Check for :code:`<title>` content
---------------------------------

================ ================ ==============================================
Source           Method           Rule
================ ================ ==============================================
HTML On Page     contains         :code:`<title>Hello, I'm Roman.</title>`
HTML On Page     matches          :code:`<title>.*</title>`
================ ================ ==============================================


Check canonical URL
-------------------

You can check exact link and URL:

================ ================ ==============================================
Source           Method           Rule
================ ================ ==============================================
HTML On Page     contains         :code:`<link rel="canonical" href="https://www.testomato.com/">`
================ ================ ==============================================

or you can check if you don't forget add any canonical link:

================ ================ ==============================================
Source           Method           Rule
================ ================ ==============================================
HTML On Page     matches          :code:`<link rel="canonical" href=".*">`
================ ================ ==============================================



Check for :code:`<h1>` content
------------------------------

You can check exact :code:`<h1></h1>` content:

================ ================ ==============================================
Source           Method           Rule
================ ================ ==============================================
HTML On Page     contains         :code:`<h1>Hello, I'm Roman.</h1>`
================ ================ ==============================================

or you can match only the most important part of :code:`<h1></h1>` content:

================ ================ ==============================================
Source           Method           Rule
================ ================ ==============================================
HTML On Page     matches          :code:`<h1>.*</h1>`
HTML On Page     matches          :code:`<h1>Hello.*</h1>`
================ ================ ==============================================


Google Analytics Code Presence
------------------------------

Find the tracking code or property ID of your Google Analytics account on your website.
Enter your ID: UA-xxxxxx-x

================ ================ ==============================================
Source           Method           Rule
================ ================ ==============================================
HTML On Page     contains         :code:`UA-xxxxxx-x`
================ ================ ==============================================

.. note:: Replace UA-xxxxxx-x with your real Google Analytics ID code.

Important page elements
-----------------------

================ ================ ==============================================
Source           Method           Rule
================ ================ ==============================================
HTML On Page     contains         :code:`<button>Sign Up</button>`
HTML On Page     contains         :code:`<button>Add to cart</button>`
HTML On Page     contains         :code:`<div id="cart"`
================ ================ ==============================================


HTTP Header Testing
-------------------

Test for HTTP headers to ensure that an application is responding, the correct
cookie is served, or an API returns the correct content-type (e.g. application/JSON).

================ ================ ==============================================
Source           Method           Rule
================ ================ ==============================================
HTTP Header      contains         :code:`wikidi-http-header:X-Powered-By:PHP/5`
HTTP Header      contains         :code:`wikidi-http-header:Content-Type:application/json`
================ ================ ==============================================
