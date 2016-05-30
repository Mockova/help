Monitoring behind login
=======================

Testomato can monitoring pages *behind login* (password protected areas of your web).
If you entrust us your credentials (password + login) we will automatically login
before each check will be performed. Checks are run in a separate session
that logs you in using credentials you configure in a login form.

.. warning:: We have to store your credential (password + login) unencrypted. While we will do everything for your safety, but be extra carefull.

Follow few security tips:

* Use a testing account just for Testomato purpose.
* Don't use same password as have your admin account have.
* Use restricted user, not an amin account.
* Use strong generated long password and change password sometimes.
* Use HTTPS `certificates are for free now <https://letsencrypt.org/>`_
* Do not hesitate to contact us (support@testomato.com) when you notice any suspicious behavior.

Monitoring behinf login allows you to check:

* System administration
* Applications behind a login page
* Membership areas
* Etc.

Create password-protected group
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. Click on the project you'd like to view.

#. Scroll down and click to *Start monitoring behind login* button.

.. image:: /checks/behind-login/start-monitoring-behind-login.png
   :alt: Start monitoring begind login
   :align: center

#. Enter the URL of the page that contains the **login form** and click **Submit**.

.. image:: /checks/behind-login/login-page.png
   :alt: Enter login page
   :align: center

#. Find the login form and click **Select**.

.. image:: /checks/behind-login/chose-login-form.png
   :alt: Chose login form
   :align: center

#. Name your group and enter the login credentials. You can verify your credentials using the *Verify credentials* button at the bottom of the page.

.. image:: /checks/behind-login/enter-credentials.png
   :alt: Enter credentials
   :align: center

All done! Your password-protected group is ready for you to add some new checks.

Edit credentials
~~~~~~~~~~~~~~~~

#. Click on the project you'd like to view.

#. Scroll down to the password-protected group you'd like to manage.

#. Click the **lock** icon next to your password-protected area's name.

.. image:: /checks/behind-login/edit-credentials.png
   :alt: Edit credentials
   :align: center

#. Fill in the new credentials you'd like to have sent to your form.

.. image:: /checks/behind-login/new-credentials.png
   :alt: Enter new credentials
   :align: center

Delete password protected group
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. Click on the project you'd like to view.
#. Scroll down to the password-protected group you'd like to delete.
#. Click the trash icon next to the right of your password protected area's name.

.. image:: /checks/behind-login/delete-group.png
   :alt: Delete group
   :align: center

#. Click **OK** to confirm.
