Check Examples
==============

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

Check for :code:`<title>` content
---------------------------------
================ ================ ==============================================
Source           Method           Rule
================ ================ ==============================================
HTML On Page     contains         :code:`<h1>Hello, I'm Roman.</h1>`
HTML On Page     matches          :code:`<h1>.*</h1>`
HTML On Page     matches          :code:`<h1>Hello.*</h1>`
================ ================ ==============================================

Check for :code:`<h1>` content
------------------------------

================ ================ ==============================================
Source           Method           Rule
================ ================ ==============================================
HTML On Page     contains         :code:`<h1>Hello, I'm Roman.</h1>`
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
