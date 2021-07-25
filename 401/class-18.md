# AWS: S3 and Lambda

Describe “The Cloud”

“The cloud” refers to servers that are accessed over the Internet, and the software and databases that run on those servers. Cloud servers are located in data centers all over the world. By using cloud computing, users and companies don’t have to manage physical servers themselves or run software applications on their own machines.

What is a container (as it relates to computers and servers)?

A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.

What is auto-scaling?

AWS Auto Scaling monitors your applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost. Using AWS Auto Scaling, it’s easy to setup application scaling for multiple resources across multiple services in minutes. The service provides a simple, powerful user interface that lets you build scaling plans for resources including Amazon EC2 instances and Spot Fleets, Amazon ECS tasks, Amazon DynamoDB tables and indexes, and Amazon Aurora Replicas. AWS Auto Scaling makes scaling simple with recommendations that allow you to optimize performance, costs, or balance between them. If you’re already using Amazon EC2 Auto Scaling to dynamically scale your Amazon EC2 instances, you can now combine it with AWS Auto Scaling to scale additional resources for other AWS services. With AWS Auto Scaling, your applications always have the right resources at the right time.

What is bandwidth?

In computing, bandwidth is the maximum rate of data transfer across a given path. Bandwidth may be characterized as network bandwidth, data bandwidth, or digital bandwidth.

How do cloud providers compute service costs?

Cost per Rack Unit.
Cost per GB of Virtual RAM.
Cost per GB of Virtual Disk.


## Term	

### Server Instances:

A server instance is a collection of SQL Server databases which are run by a solitary SQL Server service or instance. The details of each server instance can be viewed on the service console which can be web-based or command-line based.
Containers:

### Containers
A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another.
Cloud Services:

### Cloud Services:

Cloud services are services available via a remote cloud computing server rather than an on-site server. These scalable solutions are managed by a third party and provide users with access to computing services such as analytics or networking via the internet.
Cloud Architecture:

### Cloud Architecture:

Cloud architecture is the way technology components combine to build a cloud, in which resources are pooled through virtualization technology and shared across a network.
AWS:

### AWS:

Amazon Web Services (AWS) is a subsidiary of Amazon providing on-demand cloud computing platforms and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis.
EC2/Beanstalk vs Heroku:

### EC2/Beanstalk vs Heroku:

Elastic Compute Cloud (EC2) is an Infrastructure as a Service product, and is Amazon’s flagship offering. Before we’re able to deploy an application on Elastic Compute Cloud, we have to develop server infrastructure that will suit our application.
Heroku is a Platform as a Service (PaaS) product based on AWS

### What is Amazon S3?
Amazon S3 is object storage built to store and retrieve any amount of data from anywhere. It’s a simple storage service that offers industry leading durability, availability, performance, security, and virtually unlimited scalability at very low costs.

 ### What can I do with Amazon S3?
Amazon S3 provides a simple web service interface that you can use to store and retrieve any amount of data, at any time, from anywhere. Using this service, you can easily build applications that make use of cloud native storage. Since Amazon S3 is highly scalable and you only pay for what you use, you can start small and grow your application as you wish, with no compromise on performance or reliability.
 ### What kind of data can I store in Amazon S3?
You can store virtually any kind of data in any format
 ### AWS Lambda Basics:
AWS Lambda is one of the most popular serverless computing services out there. It is also the most popular provider used with the Serverless Framework.
AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). Users of AWS Lambda create functions, self-contained applications written in one of the supported languages and runtimes, and upload them to AWS Lambda, which executes those functions in an efficient and flexible manner.
 ### How does AWS Lambda work?
Each Lambda function runs in its own container. When a function is created, Lambda packages it into a new container and then executes that container on a multi-tenant cluster of machines managed by AWS. Before the functions start running, each function’s container is allocated its necessary RAM and CPU capacity. Once the functions finish running, the RAM allocated at the beginning is multiplied by the amount of time the function spent running. The customers then get charged based on the allocated memory and the amount of run time the function took to complete.


### CDN
Content Delivery Network : “is a geographically distributed group of servers that work together to provide fast delivery of Internet content. A CDN allows for the fast transfer of data needed for loading Internet content including HTML pages, javascript files, stylesheets, images, and videos”.

 