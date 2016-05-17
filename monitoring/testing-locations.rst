Testing Locations
=================

:doc:`Testomatobot </testomatobot/about>` is Testomato's crawling tool, which is
 used to download the HTML code of your page content.

In some cases, network latency between our users and Testomatobot can cause
 false timeouts and affects the ability to get a project's test results when
 it's located farther away.

To avoid this issue, we offer other Testomatobot testing locations to minimize
the influence of our connection.

This means that Testomatobot downloads pages and measures response times
from the following locations:

* USA (San Jose, California)
* USA (Dallas, Texas)
* USA  (Chicago, Illinois)
* USA (Washington, D.C.)
* Europe (London, United Kingdom)
* Europe (Frankfurt, Germany)
* Europe (Prague, Czech Republic)
* Asia (Singapore)
* Asia (Tokyo, Japan)
* Australia (Melbourne, Australia)

Downloaded content is transferred back to our central location (in Prague)
where it's processed, saved, and necessary notifications are sent.

Based on your server IP, we'll automatically assign your project to
the closest testing point.

You can manually adjust the testing location in your project's **Project Settings**.

Change Testing Location
-----------------------

How to change Testing Location:

1. Click on the project you'd like to view.
2. Click to **Project Settings** button.
3. Scroll down to **Testing location** and select the location you would like to monitor from.

.. image:: /monitoring/testing-locations.png
   :alt: Testing Locations
   :align: center
