---
title: "Connect your AWS Cloud Account to Colony"
date: 2020-10-16T10:35:57+03:00
weight: 06
draft: false
---

1\. Click a cloud provider to use.
 ![04_page](/images/prerequisite/04_page.png)
 
2\. Select the cloud provider or Kubernetes cluster. 
 ![04_page](/images/prerequisite/05_page.png)

3\. Follow the instructions to create a cloud account in Colony. This cloud account will be used to deploy your application environment on the cloud provider and also to delete those resources when you're done with the environment.
 ![04_page](/images/prerequisite/06_page.png)
 
 <br>To create the cloud account, you will need your AWS Role Arn or Azure authentication token.
 <br>For example, in AWS, when the stack's creation completes:
 
  ![04_page](/images/prerequisite/08_page.png)

 <br>You will find the __Role Arn__ in the stack's __Outputs__ tab:
 ![04_page](/images/prerequisite/09_page.png)

4\. Click __Authenticate & Complete__.
 ![04_page](/images/prerequisite/10_page.png)

<br>The cloud account is created.
 ![04_page](/images/prerequisite/12_page.png)
 
