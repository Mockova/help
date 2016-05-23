Notifications Severity Levels
=============================

It may be useful for some users to receive  notifications for both errors and
 warnings, but it’s not necessary for everyone. This article will show you how
 to select the severity levels of alerts you'd like sent as email notifications.

Warnings and Errors
~~~~~~~~~~~~~~~~~~~

Testomato tests fall into two different levels of severity – **warnings** and **errors**.

The main distinction between the two is that a warning test could possibly fail
as a result of a false alert, meaning that it’s probably not a critical issue.
In simple terms, a warning  should not affect your visitors.

Here's a breakdown of the website tests we have on Testomato:

Warnings
~~~~~~~~

The following are considered warnings:

* Any timeouts (if the time required to download a page exceeds the period you
have entered in a project’s settings).
* Authentication request failures in password-protected areas.

.. note::

  Please note: In some cases, it possible to get a warning for an HTTP
  status code 200 OK if a timeout exceeds the period you have entered
  in a project’s Settings.


Errors
~~~~~~

Tests that fail for the following tests are considered errors:

* HTTP Status (i.e. 404 or 500 on pages where a 200 is expected)
* Found error message on the page (web server error pages, PHP, MySQL, etc.)
* Text found and missing text (string tests)
* Download Error (Testomatobot is unable to download page content)

Change Notifications Severity
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

How to set a severity level for email notifications:

Open :doc:`Instant Notifications Settings </notifications/instant-notifications>`
or just open a :doc:`Project Settings </projects/project-settings>`.
Then scroll down to *Projects Notifications* and chose your preferences.

.. image:: /notifications/notifications-severity.png
   :alt: Notifications Severity
   :align: center
