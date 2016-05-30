Monitoring behind login
=======================

Testomato can monitor pages behind login (password protected areas of your
website). If you entrust us with your credentials (password + login) we will a
utomatically login before each check is performed. Checks are run in a separate
session that logs you in using credentials you configure in a login form.

Follow these security tips:

.. warning:: We have to store your credential (password + login) unencrypted. While we will do everything to ensure your safety, please be extra careful.

Follow these security tips:

* Use a testing account just for Testomato.
* Don’t use the same password you are using for your admin account
* Use a restricted user account, not an amin account.
* Use a strong, long password and change password once in a while.
* Use HTTPS certificates (they are `available free of charge <https://letsencrypt.org/>`_)
* Do not hesitate to contact us (support@testomato.com) if you notice any suspicious behavior.

Monitoring behinf login allows you to check:

* System administration
* Applications behind a login page
* Membership areas
* Etc.

Create password-protected group
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

1. Click on the project you'd like to view.

2. Scroll down and click on the **Start monitoring behind login** button.


.. image:: /checks/behind-login/start-monitoring-behind-login.png
   :alt: Start monitoring begind login
   :align: center

3. Enter the URL of the page that contains the **login form** and click **Submit**.

.. image:: /checks/behind-login/login-page.png
   :alt: Enter login page
   :align: center

4. Find the login form and click **Select**.

.. image:: /checks/behind-login/chose-login-form.png
   :alt: Chose login form
   :align: center

5. Name your group and enter the login credentials. You can verify your credentials using the *Verify credentials* button at the bottom of the page.

.. image:: /checks/behind-login/enter-credentials.png
   :alt: Enter credentials
   :align: center

All done! Your password-protected group is ready for you to add some new checks.

Edit credentials
~~~~~~~~~~~~~~~~

1. Click on the project you'd like to view.

2. Scroll down to the password-protected group you'd like to manage.

3. Click the **lock** icon next to your password-protected area's name.

.. image:: /checks/behind-login/edit-credentials.png
   :alt: Edit credentials
   :align: center

4. Fill in the new credentials you'd like to have sent to your form.

.. image:: /checks/behind-login/new-credentials.png
   :alt: Enter new credentials
   :align: center

Delete password-protected group
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

1. Click on the project you'd like to view.
2. Scroll down to the password-protected group you'd like to delete.
3. Click the trash icon next to the right of your password protected area's name.

.. image:: /checks/behind-login/delete-group.png
   :alt: Delete group
   :align: center

4. Click **OK** to confirm.
