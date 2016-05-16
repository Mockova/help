How Does Testomato Check My Page?
=================================

Testomato is an easy automated monitoring service that actively monitors your
website without requiring advanced technical knowledge or complicated
maintenance, allowing you to check your website for problems that impact users
directly. This is article will give you a quick overview of how Testomato works.

In order to monitor your website, Testomato downloads and scans your HTML code
similar to other popular web crawlers (like Googlebot). However, we use our own
crawler, the :doc:`Testomotobot </testomatobot/about>`.

Testomato downloads your HTML source code in order to run checks, but it does
not execute any of the JavaScript on your website. This means that while we can
catch errors in your UI just like a common user would, we do not run your
website in a browser and are unable to find problems that may occur across
different browsers.
