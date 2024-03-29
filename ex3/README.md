## Exercise 4
In this exercise, we will cover the basics of Real User Monitoring. These are some of the best practices that should be followed every time the Dynatrace JavaScript agent is deployed, be it an automated or manual injection. 

More information can be found here: [How to use Dynatrace > Real User Monitoring > Setup and configuration > Web applications](https://www.dynatrace.com/support/help/how-to-use-dynatrace/real-user-monitoring/setup-and-configuration/web-applications/)

There are 3 tasks in this exercies:
- [ ] Task1 Exploring an application
- [ ] Task2 Selecting the appropriate JavaScript frameworks
- [ ] Task3 Reviewing a user session

### Task 1. Understanding an application

Reference: https://www.dynatrace.com/support/help/how-to-use-dynatrace/real-user-monitoring/setup-and-configuration/web-applications/initial-configuration/define-your-applications-via-the-my-web-application-placeholder

1. Select Applications from the navigation menu.
2. Click the My web application placeholder application.
3. Go through the various details of application such as 
   a. Time to Visually Complete
   b. Top Javascript errors
   c. Top User Actions
    ![Deploy](https://github.com/jsharma19/gettingstarted_hotsession/blob/master/assets/application%20overview.PNG) 
   


### Task 2. Selecting the appropriate JavaScript frameworks

1. Select Applications from the navigation menu.
2. Select My Web Application
3. Click the Browse button (...) and select Edit.
4. Select "Async request..."
5. Enable the following framewoks as shown in the screen below
6. Click on Save

   ![Deploy](https://github.com/performgohot19/DEM/blob/master/assets/202-ConfigFramework.png)

### Task 3. Reviewing a user session

Reference: https://www.dynatrace.com/support/help/how-to-use-dynatrace/real-user-monitoring/how-to-use-real-user-monitoring/cross-application-user-session-analytics/identify-individual-users-for-session-analysis/

We will be review user sessions of our application.
A user session, sometimes known as a "visit," is a group of user actions that are performed in your web application during a limited period of time. A single session typically includes multiple page loads, 3rd-party content requests, service requests, and user actions (for example, button clicks and file downloads). Each user session includes at least one user action.

![Deploy](https://github.com/jsharma19/gettingstarted_hotsession/blob/master/assets/user%20sessions.PNG)

Click on Any of the user session to look at different user actions and its metrics


---


