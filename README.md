## What is CI/CD ?
---
- CI/CD is a method to frequently deliver apps to customers by introducing automation into the stages of app development.

### CI
- CI stands for Continuous Integration. This is the process of developers commiting code to master branch multiple times a day, fully automated build and test process which gives feedback within few minutes, by doing so, you avoid the integration hell that tends to happen on the last few days before the deadline.

### CD

- CD stands for Continuous Delivery which is just an extenstion on CI. This means that on top of having automated your testing, you also have automated your release process and you can deploy your application at any point of time by clicking on a button. In continuous Delivery the deployment is completed manually.

### CDE

- CDE is Continuous Deployment which is one step further than CD by automatically deploying to production if all stages have passed succesfully. there is no human intervention, and only a failed test will prevent a new change to be deployed to production. 


### Difference between CD and CDE ?

The main difference is that in continuous Delivery (CD) the deployment is completed manually and needs a human to make that final click before deployment. Where as CDE automatically depolys to production without the need of any human unless some code had failed.

### Webhook?

- A webhook is an HTTP-based callback function that allows lightweight, event-driven communication between 2 application programming interfaces (APIs).
- In other words Webhooks are automated messages sent from apps when something happens. 

- Example: Automatically receive an email every morning about your first meeting in case you forget to check your calendar.