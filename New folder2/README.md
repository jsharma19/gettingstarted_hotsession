## Exercise 3
In this exercise, we will cover the basics of Dynatrace auto discovery,Hosts, Transactions and Services. These are some of the auto discovered view and information created by OneAgent after deployment.

More information can be found here: 
	1. Transactions and Services (https://www.dynatrace.com/support/help/how-to-use-dynatrace/services-and-transactions/)
	2. Hosts (https://www.dynatrace.com/support/help/how-to-use-dynatrace/hosts/)
	3. Smartscape (https://www.dynatrace.com/support/help/how-to-use-dynatrace/smartscape/)

There are 3 tasks in this exercises:
- [ ] Task1 Exploring Smartscape
- [ ] Task2 Exploring the hosts view
- [ ] Task3 Exploring Transactions and Services

### Task 1. Exploring Smartscape



1. Select Smartscape from the navigation menu.
2. Click the Services layer in the Smartscape screen.
3. Spend time understanding the various horizontal and vertical dependencies.

   ![Deploy](https://github.com/jsharma19/DEM/blob/master/assets/108-Smartscape.JPG)




### Task 2. Exploring the hosts view

1. Click hosts from Navigation Menu
2. Select your host 

  ![Deploy](https://github.com/jsharma19/DEM/blob/master/assets/Hosts%20-109.PNG)

  ![Deploy](https://github.com/performgohot19/DEM/blob/master/assets/202-ConfigFramework.png)

### Task 3. Explore Transactions and Services 

Dynatrace understands your applications’ transactions from end-to-end. This transactional insight is visualized through Service flow, which illustrates the sequence of service calls that are triggered by each service request in your environment. With Service flow you see the flow of service calls from the perspective of a single service, request, or their filtered subset. Along with the specific services that are triggered, you can also see how each component of a request contributes to the overall response time.

Once you have identified a service to be monitored, execute the following steps :

1. Select Transactions and Services from Navigation Menu
2. Click on "easyTravel Customer Frontend". This opens up the service view of Customer Frontend Service.
3. In the services view, click on " View Service Flow". This will open up the service flow  
4. Paste the CSS Selector which you copied earlier from your browser's Developer Tool. Since the CSS Selector also picks up some additional text, we can apply a clean up rule.
5. Click on Save

   ![Deploy](https://github.com/jsharma19/DEM/blob/master/assets/service-110.PNG)
