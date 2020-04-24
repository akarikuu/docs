Account Management
----------------------

Mattermost offers a self-service portal where you can manage your Mattermost:

* Subscription purchases
* Licenses
* Account password
* Organization information
* Payment methods

The self-service portal applies to on-premises Mattermost deployments only. Cloud deployments will be supported in a future release.

How do I purchase a subscription?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

1. Log in to your Mattermost customer profile. If you haven't created a profile, follow the steps provided on the landing page, validate your email address, and then log in.
2. Choose a subscription type, enter the number of users in the **Order summary** field.
3. (Optional for E20) You can add Premier Support, the cost of which is automatically added to your order total.
4. Select **Next Step**.
5. Enter your billing and payment information.
6. Accept the **Terms**
6. Select **Complete**.


Is my subscription active immediately?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Yes, once your payment is successfully processed your license is immediately available in your account.

Is there a limit to the subscription value I can purchase?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Yes. The current limit is $5000

How many users can have access to an account?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

My card was declined
~~~~~~~~~~~~~~~~~~~~~



How do I apply my license key?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. note::

   If you are not a System Admin, you will not have access to the System Console to apply the license.


Navigate to the **Subscriptions** page of your Mattermost account. Select **Download License** to download the license key for your subscription. Then, in Mattermost,
open **System Console > About > Edition and License**. Follow the steps provided to apply your license key.


How do I renew the Enterprise Edition subscription?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Log in to the Customer Portal and select the Enterprise Edition you want to renew, the user count, and your contact information. To find the user count you want to renew for, log in to Mattermost as a System Admin and go to **System Console > Site Statistics**, where **Total Active Users** displays the user count on your server.

After submitting the renewal form, our renewal team will get in contact with you about your new subscription.

New users added during the subscription period will have a retroactive charge. `Learn more here <https://docs.mattermost.com/overview/faq.html#how-can-i-add-more-users-to-my-subscription>`__.

For information on what happens when the Enterprise Edition subscription expires, see our `frequently asked questions about licensing <https://about.mattermost.com/pricing/#faq>`__.

What happens when the Enterprise Edition subscription expires?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~



How is user defined for Enterprise Edition subscriptions?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

See our `frequently asked questions about licensing <https://about.mattermost.com/pricing/#faq>`__.

How can I add more users to my subscription?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can add more users during your subscription period without requesting a license.

During the annual renewal, a retroactive charge will be placed for any unique users added during the past subscription period that is above the licensed total unique users in the current paid subscription. The retroactive charge per user will be the initial subscription cost per user.

Do I need to pay for deactivated users?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

No. If you deactivate a user that user is not counted as an active user during your annual renewal process. You can deactivate users manually via System Console and also via Active Directory/LDAP synchronization, the CLI tool, and the server APIs.

If you choose to pull SQL reports from the database to monitor individual activity to make deactivation decisions, and you are running under high user load, we recommend the reports are pulled from a read replica of the database.

Can I use the same license key on multiple Enterprise Edition servers?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Customers who purchase the Premier Support add-on to E20 are licensed to run with the same Mattermost license key in a production deployment and up to 4 non-production deployments of Mattermost (for example: development, staging, user acceptance testing, etc.).

Without the purchase of Premier Support, license keys for unlocking the advanced features in Mattermost Enterprise Edition should only be applied to a single deployment. A deployment consists of either a single Mattermost application server, or multiple linked Mattermost application servers in a high availability configuration.


What happens if my department buys Mattermost Enterprise Edition and then central IT buys a high volume license that also covers my department?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Mattermost Enterprise Edition subscriptions and support benefits are licensed per production instance.

When the subscription term for your department's production instance expires, you can either discontinue your department's production instance and move to the instance hosted by central IT (which can optionally provision one or more teams for your department to control), or you can renew your subscription to maintain control of your department's instance (e.g., to configure or customize the system in a manner highly specific to your line-of-business) in addition to using the instance from central IT.


How do I delete my account?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

What happens when I delete my account?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
