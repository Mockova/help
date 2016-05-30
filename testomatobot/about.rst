About Testomatobot
==================

Testomatobot is the toolset we use to send web forms, download web pages, and
download resources that will be checked, according to your project
configurations.

However, unlike a normal website crawling tool, it's not used for crawling the
internet. We only use it to download Testomato projects' URLs.

On average, Testomato doesn't need to access your site for longer than a
5-minute interval. Testomatobot allows us to access multiple sources on your
server (e.g. your homepage, robots.txt, favicon.ico, etc.)

You can locate Testomatobot easily in your server logs with the following user agent HTTP header field:

.. code-block:: none

    Testomatobot/1.0 (%os%; +http://www.testomato.com/testomatobot) minicrawler/%version%

IP addresses for Testomatobot:

.. code-block:: none

    217.31.53.128/27
    217.31.54.192/27
    217.31.55.64/27
    50.57.53.25
    23.253.162.51
    23.253.21.216

How to Change Your User Agent String
------------------------------------

If your page has been configured to redirect search engine bots (e.g. Yahoo,
Google, Bing) to a different page, you can select a different user agent in
your project Settings tab.

For example, if Google's bot wants to crawl  example.com/abc it would be sent
(redirected) to example.com/bcd instead.

1. Click on the project you'd like to view or select a project from the All
   Projects menu in the top right corner.

2. Once in the project dashboard, click on the Settings tab and scroll down to
   User Agent string.

.. image:: /testomatobot/user-agent-string.png
   :align: center

3. Select the user agent string you would like to use. Your new settings will
   update automatically.

If you don't want Testomatobot to access your server (i.e. due to overloading),
please contact us at  support@testomato.com.
