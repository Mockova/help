Pagerduty Integration
=====================

PagerDuty is a reliable SaaS provider that plugs into IT monitoring tools and
provides alerts of all forms. This article with show you how to extend
Testomato's notifications with PagerDuty to alert the
appropriate member of your team.

Connecting PagerDuty means you can receive alerts (e.g. SMS, phone calls,
iOS/Android push notifications) with automatic alert escalation for all your
Testomato incidents, and you'll also be able to track them from the PagerDuty
dashboard.

In Pagerduty
~~~~~~~~~~~~

1. Login to `PagerDuty <https://www.pagerduty.com/>`_.

2. From the Configuration menu, select **Services**.

3. On your Services page: If you are creating a new service for your integration,
click **+Add New Service**. If you are adding your integration to an existing
service, click the name of the service you want to add the integration to.
Then click the Integrations tab and click the **+New Integration button**.

.. image:: /notifications/pagerduty/add-new-service.jpg
   :alt: Pagerduty Integration - Add new Service
   :align: center

.. image:: /notifications/pagerduty/new-integration.jpg
   :alt: Pagerduty Integration - new integration
   :align: center

4. Select your app from the **Integration Type** menu and enter an **Integration Name**.
If you are creating a new service for your integration, in General Settings,
enter a Name for your new service. Then, in Incident Settings, specify the
**Escalation Policy**, **Notification Urgency**, and **Incident Behavior**
for your new service.

5. Click the **Add Service** or **Add Integration** button to save your new
integration. You will be redirected to the Integrations page for your service.

.. image:: /notifications/pagerduty/integration-settings.png
   :alt: Pagerduty Integration Settings
   :align: center

4. Copy the Integration Key for your new integration:

.. image:: /notifications/pagerduty/integration-key.png
   :alt: Pagerduty Integration Key
   :align: center

In Testomato
~~~~~~~~~~~~

1. Open `Instant Notifications Settings <https://www.testomato.com/user/notifications-settings>`_
page in Testomato, scroll down to PagerDuty integration.

.. image:: /notifications/pagerduty/pagerduty-settings.png
   :alt: Pagerduty Integration
   :align: center

Paste Service API key from Pagerduty
