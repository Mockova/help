robots.txt
==========

In your :doc:`Testomato pre-configured checks <project/add/index>`, we include a
 check for a robots.txt file on your website. This check should be viewed as a
 warning rather than a serious error that affects the experience of your users.

The  Robots Exclusion Protocol (REP) or robots.txt is a text file webmasters or
website owners create to instruct robots (typically those used by search engines) how to crawl and index pages on their websites and online applications.

A **robots.txt file** is used to stop web crawlers (e.g. Googlebot) from crawling certain pages of your site. If you block a certain page with your robots.txt, it will not appear in search engine results.

What You Need to Know:

* You normally only need a robots.txt file if your site or application has content you don't want indexed by search engines.
* If you want your whole site to be indexed, you do NOT need to include a file.
* You should place your robots.txt in the top-level of your web server. Example: :code:`http://yourwebsite.com/robots.txt`
* Malicious crawlers often ignore robots.txt so it should not be relied on as a security mechanism.
robots.txt files are publicly available. Anyone can see what sections of your server you don't want indexed.
Useful Tips to Remember:

The filename robots.txt is case sensitive.

* Example: "robots.txt" NOT "Robtots.TXT"
* Each subdomain on a root domain uses separate robots.txt files.
* Only one "Disallow:" line is allowed for each URL.

To learn more about robots.txt files and how to create your own, we suggest
reading this `quick guide from Google <https://support.google.com/webmasters/answer/6062608?hl=en&ref_topic=6061961>`_.

You can also visit `The Web Robots Pages <http://www.robotstxt.org/>`_ for more information
about what robots.txt is, how to use it, and other commonly asked questions about robots.
