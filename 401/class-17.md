# Cloud Servers

## Review, Research, and Discussion

Describe the Web-Request-Response-Cycle

it is the cycle that represents how each process will done when we using the internet. when hit http link, this request will go to the server and maybe to database also or other servers, finally will return a reesponse to the client.
Explain what a “server” is, as it relates to the WRRC

it is a place or code that can’t see it as a client, this code treat client requests by organize and store data, then will send a response to that client as he needed.
What does it mean to “deploy” an application?

a process to make our codes run online, not locally. then you can use this application everywhere. also it is a hosting process for our codes and applications in online servers.

## Terms

#### Server : it is a code that exisiting in a computer, this code deals with the user interface or client requests to do some actions based on these requests. mainly organizing and storing data and make some extra things and processes.

#### Pub/Sub : publisher - subscriber. represents how events work, by publishing the event by someone, then everyone listned to this event as a subscriber will run this event for it when it’s published. in other words Pub/Sub is a flexible, reliable, real-time messaging service for independent applications to publish and subscribe to asynchronous events.

#### WRRC : web request-response cycle. represents how every web service or process done when a client does some action in the user interface.

## Virtual Machines

virtual machine : consists of hardware and software, software is a controller(operating system) of the hardware parts.

virtual machine manager (Hypervisor) : it is a type of software that allows us t run an operating system within another operating system.

examples : virtual box and vm ware.

why we using virtaul machines ?

run more than one operating system togethor(on same computer)
for test an application
for running old application.

## Virtualization and Cloud Computing

Virtualization allows us to better utilize the resources we have available in out machine.
Virtualization is when many Virtualization Machines are controlled and operate inside one single machine. This gives us the following advantages:

Fewer machines.
Lower capital investment.
Centralized management.
Lower operation cost.

Cloud Computing is when someone is using a computer that is in another location.

## AWS EC2

It’s a service provided by Amazon. The term AWS EC2 stands for “Amazon Elastic Compute Cloud”. it is a web service that provides secure, resizable compute capacity in the cloud.
Amazon claims It is designed to make web-scale cloud computing easier for developers and it’s simple web service interface allows you to obtain and configure capacity with minimal friction. Also, It provides you with complete control of your computing resources and lets you run on Amazon’s proven computing environment.

## EC2 For Humans

EC2 is a service, where clients can rent a like server (not physical machine) or in other words virtual machine, that is independent form other virtual machines that are on aws server.

Throw amazon site you can create an instance , where you can choose the type of operating system, memory size, number of CPUs, storage capacity and more.

This virtual machine can be used for storing data, web application, machine learning and more.

There are different settings that fit each usage, related to access and privacy.

## Elastic Beanstalk

Elastic Beanstalk is a service that deploys, manages and scales web apps and services on behave of the developer.

Elastic Beanstalk uses managed containers like:

java.net
PHP
Node.js
Python
Ruby
docker
It also works on familiar servers such as :

apache HTTP
apache tomcat
engin x
passenger
IIS
Elastic Beanstalk leverages familiar AWS services such as :

Amazon EC2
Amazon S3
Amazon simple notification service
Amazon elastic load balancing
Amazon auto scaling
To start with Elastic Beanstalk you can use, AWS management console, the command line interface or the API. choose your platform and amazon EC2 instance type, then select additional resources to use such as Amazon relational database service, then upload yor code.

Elastic Beanstalk will handle Load Balancing, Provisioning, Auto Scaling and Application Health Monitoring.

