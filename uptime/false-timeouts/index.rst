Getting false timeouts
======================

Why Does Testomato Say My Site Is Down When It's Not? Testomato may occasionally
report your site is down or unavailable, but everything looks fine when you go
and investigate the problem for yourself.

Location Matters
----------------

:doc:`Uptime Monitoring </uptime/what-is-uptime-monitoring>`  in Testomato is
done externally rather than internally. This means that :doc:`Testomatobot </testomatobot/about>`
tests and monitors your site or server from a location that is outside the local
network where your server is hosted.

In some cases, a project may be unavailable to Testomato a very short period of
time due to problems with network latency, i.e.  how long it takes data to get
from one point to another.

To help avoid sending alerts about false timeouts or short-term issues, we
retest your project a second time before we send an alert if Testomato is
unable to connect with your site or server.

We have also started adding more testing locations in Testomato to help minimize
the influence of our connection on your project test results.

How to Evaluate the Problem
---------------------------

You can dig deeper into the details of an outage by analyzing the HTTP header
response for the request made to your website.

To view recent results:

1. Click the *gear icon* of the timed out test.

.. image:: page-settings.png
   :alt: Page settings
   :align: center

2. Scroll down and click **Show HTTP response headers** at the bottom of
   the page.

This will open up a more detailed report, containing information about the
trace-route and the content of the returned data:

For details about older incidents, select the issue in your Issues Timeline
located in the **Reports** of your project's dashboard.
