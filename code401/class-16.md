# AWS: Cloud Servers

## AWS EC2

1. What is an EC2 Instance?

   - An EC2 (Elastic Compute Cloud) instance is a virtual server that you can use to run applications in the Amazon Web Services (AWS) cloud.

2. Name 2 use cases for EC2.

   1. Web hosting: You can use an EC2 instance to host a web server and run a website or web application. This allows you to scale your website or web application as needed, and to take advantage of the security and reliability of the AWS infrastructure.

   2. Data processing: You can use an EC2 instance to process large amounts of data, such as for data analytics or machine learning. This allows you to leverage the computing power of the AWS cloud to quickly and efficiently process your data.

3. Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.

   - One reason to use Amazon Elastic Container Service (ECS) instead of a service such as Heroku, DigitalOcean, or Render.com is that ECS allows you to easily scale your containerized applications up or down based on your resource needs. ECS also offers integration with other AWS services, automatic container orchestration, and high availability.

## EC2 for Humans

1. Where can we find EC2 on the AWS Console?

   1. On the main dashboard, click the "Services" menu in the top left corner.

   2. In the "Compute" category, click the "EC2" option.

2. Explain the general difference between T2 Micro and XL.

   - T2 Micro instances are designed for workloads that do not require high performance or a lot of CPU resources, while XL instances are designed for workloads that require a lot of CPU resources and can benefit from high-performance processors. T2 Micro instances are generally smaller and less expensive than XL instances, but they may not be suitable for resource-intensive workloads.

3. Explain a “Compute Cycle” to a non-technical friend.

   - A compute cycle is a unit of processing power used to run an application or perform a task. It refers to the amount of time that a computer's processor spends executing instructions, and it is typically measured in units of time such as seconds or minutes.

## Elastic Beanstalk

1. What is Elastic Beanstalk?

   - Elastic Beanstalk is a convenient and easy-to-use service that allows you to quickly and easily deploy and run web applications in the AWS cloud. It simplifies the process of deploying and managing applications, and it offers a number of useful features such as automated scaling and monitoring.

2. Describe the relationship between EC2 and Elastic Beanstalk.

   - Elastic Beanstalk uses EC2 instances as the underlying compute resources for running applications. When you deploy an application using Elastic Beanstalk, AWS will create one or more EC2 instances and configure them to run your application.

3. Name some benefits of using Elastic Beanstalk.

   1. Ease of use
   2. Automated scaling
   3. Integrattion with other AWS services
