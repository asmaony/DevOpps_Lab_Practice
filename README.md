## LAB_1-Introduction to Amazon EC2
#### We will introduce basic understanding of launching,resizing,managing an Amazon EC2 Instance.

#### 1. launch a web server with termination protection enabled:

In this task, we will launch an Amazon EC2 instance with termination protection. Termination protection prevents from accidentally terminating an EC2 instance.The instance will include a User Data script that will install a simple web server.



![Screenshot (36)](https://github.com/user-attachments/assets/f0375bc9-d94b-4b14-bf36-e4b379b6e5fb)


#### 2. Monitor the Instance:

Monitoring is an important part of maintaining the reliability, availability, and performance of Amazon Elastic Compute Cloud (Amazon EC2) instances and  AWS solutions.


![Screenshot (37)](https://github.com/user-attachments/assets/56018457-3173-4a4b-a112-10cf6be7704f)


#### 3. Modify the security Group that the web server is using to allow HTTP access:

When we launched the EC2 instance, it is  provided a script that installed a web server and created a simple web page. In this task, we will access content from the web server.




![Screenshot (38)](https://github.com/user-attachments/assets/5c0a8718-743f-45a0-b6eb-ff3dabc774f1)


![Screenshot (39)](https://github.com/user-attachments/assets/02a279e8-34c9-42ae-a341-21205a26be2f)


#### 4. Resize Amazon EC2 Instance to scale:



 In this stage, an EBS volume being modified goes through a sequence of states: Modifying, Optimizing, and finally Complete.



![Screenshot (41)](https://github.com/user-attachments/assets/752d16ba-0f8b-4a06-883e-cfd109c96577)

#### 5. Test terminaation protection:

We can delete the instance when we no longer need it. This is referred to as terminating the instance. We cannot connect to or restart an instance after it has been terminated.



#### Terminate the EC2 Instance:

In this task, you will learn how to use termination protection.



![Screenshot (43)](https://github.com/user-attachments/assets/92c6d0c7-6637-408b-964e-de252dc1c405)


## LAB_2-Introduction to Amazon Simple Storage Service S3

## 1.Create a bucket:
In this task,We will create a bucket to hold our EC2 report data and then examine the diffrent bucket configuration option.

#### 2.Upload an object to the bucket:
In this task we test uploading objects to reportbucket.

#### 3.Make an object Public:
Here ,we configure permissions on our bucket and our object to test accessibility.
#### 4.Test connectivity from EC2 Instance:
In this task, we connect our EC2 to test connectivity and security to the S3 report bucket.
#### 5.Create a bucket policy:
Here we use the AWS policy generator to create a bucket policy to enable read and write access from the EC2 instance to the bucket to ensure your reporting application can successfully write to S3.


#### 6.Explore versioning


























