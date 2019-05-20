## LAB8: Data Ingestion through Launch
In this exercise, the goal is to set up data ingestion through Launch so that the customer behaviour on BT UK's website is streamed to Adobe Experience Platform in real-time.

**Thank you for attending the Adobe Summit Tech Labs for Adobe Experience Platform. If you have feedback or follow-up questions after the Labs, please contact Wouter Van Geluwe - vangeluw@adobe.com directly.**

### Learning Objectives

- Learn how to create an XDM Schema in Adobe Experience Platform
- Learn how to create Datasets in Adobe Experience Platform
- Learn how to create a streaming endpoint and configure the Adobe Experience Platform extension in Launch
- Learn how to create Rules in Launch to stream data to Adobe Experience Platform
- Learn how to integrate Adobe Experience Platform Launch onto a webpage

### Lab Resources

- Adobe Experience Platform: [https://platform.adobe.com](https://platform.adobe.com)
- Launch URL: [https://launch-demo.adobe.com](https://launch-demo.adobe.com)

### Story

BT UK wants to receive customer behaviour in real-time in Adobe Experience Platform and link all attributes and behavior to the Unified Profile in real-time. The ultimate end goal is to activate this information and these profiles in real-time as well, to any channel.
As you may know, customer retention is a key focus area for any company, and the same goes for BT UK. 
In order to act immediately and appropriately upon customer behavior, the behavior needs to be available as soon as possible, and preferably, should be linked to an actionable customer profile.
BT UK would like to activate that data to several solutions like Adobe Target and Adobe Audience Manager, but also to channels like a call center or an in-store environment.
In this lab, we'll focus on capturing the data as soon as possible.

### [Before we start](./info.md)
Read through this info to know where to find usernames, passwords and computer numbers.

### [Exercise 0 - Explore the BT website](./ex0.md)
In this exercise, you'll explore the BT website that is installed on your local machine.

### [Exercise 1 - Configure Schema's and Set Identifiers](./ex1.md)
In this exercise, you'll configure the required XDM schema's to capture profile information and customer behavior. In every XDM schema, you'll also have to configure a primary identifier to link all the information to.

### [Exercise 2 - Retrieve Datasets](./ex2.md)
In this exercise, you'll retrieve the required datasets to capture and store profile information and customer behavior.

### [Exercise 3 - Create Streaming Endpoint](./ex3.md)
In this exercise, you'll configure the Adobe Experience Platform extension in Launch and you'll create your own streaming endpoint.

### [Exercise 4 - Configure Launch Rules](./ex4.md)
In this exercise, you'll configure 2 Launch Rules to capture customer profile attributes and customer behavior and send it to Adobe Experience Platform.

### [Exercise 5 - Publish your configuration on the BT website](./ex5.md)
In this exercise, you'll publish your Launch configuration and make sure that your local BT website uses your Launch configuration.

### [Exercise 6 - Stream Data to Adobe Experience Platform](./ex6.md)
In this exercise, you'll go on your local BT website and behave like a customer, streaming data to Platform.

---
![Go Back to All Tech Lab Content](./images/expsuccess.png)
---




