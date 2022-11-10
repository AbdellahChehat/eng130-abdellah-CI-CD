## What is CI/CD ?
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

<img width="728" alt="Screenshot 2022-11-08 at 10 21 30" src="https://user-images.githubusercontent.com/115224560/200539789-939a61a7-f5cb-4fcb-8626-8d5b2ea3f1c0.png">


## What is Jenkins

- An open source automation server which enables developers around the world to reliably build, test, and deploy their software.

![image-3](https://user-images.githubusercontent.com/115224560/201057032-54868f46-ce8c-4bc7-aaa9-53f9f7bc1e88.png)




## Benefits of Jenkins

- It is an open-source tool with great community support.
- It is easy to install.
- It is free of cost.

---
-  create a new SSH key pair called-  eng130_jenkins_abdellah - eng130_jenkins_abdellah.pub

-Step 1: Create a new CICD pipeline
  - Step 2: generate a new ssh keypair
  - step 3: Copt file.pub to github repo 
  - step 4 copy private key in jenkins
  - Stgep 5: Create a new job to test the CI
