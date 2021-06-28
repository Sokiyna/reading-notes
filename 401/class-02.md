### Express
What’s the difference between PUT and PATCH?

The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.

### Provide links to 3 services or tools that allow you to “mock” an API for development like json-server

Postman
Stoplight
Mocky.io
Killgrave
### Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?

apiDocjs: Inline Documentation for RESTful web APIs. It creates a documentation from API annotations in your source code. It includes a default template which uses handlebars, Bootstrap, RequireJS and jQuery for the output of the generated apidata.js and apiproject.js as a html-page; Swagger Inspector: Test and Document Your APIs With Ease. It is a free cloud-based API testing and documentation tool to simplify the validation of any API and generate its corresponding OpenAPI documentation. apiDocjs and Swagger Inspector can be primarily classified as “API” tools.

### Compare and contrast SOAP and ReST

SOAP stands for Simple Object Access Protocol whereas REST stands for Representational State * Transfer.
SOAP is a protocol whereas REST is an architectural pattern.
SOAP uses service interfaces to expose its functionality to client applications while REST uses Uniform Service locators to access to the components on the hardware device.
SOAP needs more bandwidth for its usage whereas REST doesn’t need much bandwidth.
SOAP only works with XML formats whereas REST work with plain text, XML, HTML and JSON.
SOAP cannot make use of REST whereas REST can make use of SOAP.
Document the following Vocabulary Terms

##### Web Server: is computer software and underlying hardware that accepts requests via HTTP, the network protocol created to distribute web pages, or its secure variant HTTPS.

#### Express: is a back end web application framework for Node.js, released as free and open-source software under the MIT License. It is designed for building web applications and APIs. It has been called the de facto standard server framework for Node.js

#### Routing: refers to how an application’s endpoints (URIs) respond to client requests.

#### WRRC: web request/response cycle traces how a user’s request flows through the app.


#### Preview 
Which 3 things had you heard about previously and now have better clarity on?
Refined my knowledge of REST and how it all works
POSTMAN is a very useful tool to see API promise so that we can further handle on our code
Importence of Express and how useful it is/makes building and handling routes significantly easier
Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
I am hoping to learn about what exactly SWAGGER and APIDoc.js are. I did some reading but still did not understand the difference or exactly what they do
We havent worked with SOAP just yet and would like to see how it works in action
I see that SOAP is used for enterprise businesses. I thought Google, Twitter, Youtube would all use SOAP if that was the case.. and REST used for smaller businesses websites that do not need person to person real-time communication
What are you most excited about trying to implement or see how it works?
I want to see how SOAP works and examples of when to use either SOAP or REST
I am excited to see how usernames:passwords are used and websites are altered to every unique individual’s saved storage, preferences, etc.
Really interested how real-time person to person communication is developed

### About npm

npm is the world's largest software registry. Open source developers from every continent use npm to share and borrow packages, and many organizations use npm to manage private development as well.

npm consists of three distinct components:

the website
the Command Line Interface (CLI)
the registry
Use the website to discover packages, set up profiles, and manage other aspects of your npm experience. For example, you can set up organizations to manage access to public or private packages.

The CLI runs from a terminal, and is how most developers interact with npm.

The registry is a large public database of JavaScript software and the meta-information surrounding it.

### TDD Definition

“Test-driven development” refers to a style of programming in which three activities are tightly interwoven: coding, testing (in the form of writing unit tests) and design (in the form of refactoring).

It can be succinctly described by the following set of rules:

write a “single” unit test describing an aspect of the program
run the test, which should fail because the program lacks that feature
write “just enough” code, the simplest possible, to make the test pass
“refactor” the code until it conforms to the simplicity criteria
repeat, “accumulating” unit tests over time

### Express/Node introduction


Node (or more formally Node.js) is an open-source, cross-platform runtime environment that allows developers to create all kinds of server-side tools and applications in JavaScript. The runtime is intended for use outside of a browser context (i.e. running directly on a computer or server OS). As such, the environment omits browser-specific JavaScript APIs and adds support for more traditional OS APIs including HTTP and file system libraries.

From a web server development perspective Node has a number of benefits:

Great performance! Node was designed to optimize throughput and scalability in web applications and is a good solution for many common web-development problems (e.g. real-time web applications).
Code is written in "plain old JavaScript", which means that less time is spent dealing with "context shift" between languages when you're writing both client-side and server-side code.
JavaScript is a relatively new programming language and benefits from improvements in language design when compared to other traditional web-server languages (e.g. Python, PHP, etc.) Many other new and popular languages compile/convert into JavaScript so you can also use TypeScript, CoffeeScript, ClojureScript, Scala, LiveScript, etc.
The node package manager (NPM) provides access to hundreds of thousands of reusable packages. It also has best-in-class dependency resolution and can also be used to automate most of the build toolchain.
Node.js is portable. It is available on Microsoft Windows, macOS, Linux, Solaris, FreeBSD, OpenBSD, WebOS, and NonStop OS. Furthermore, it is well-supported by many web hosting providers, that often provide specific infrastructure and documentation for hosting Node sites.
It has a very active third party ecosystem and developer community, with lots of people who are willing to help.
You can use Node.js to create a simple web server using the Node HTTP package.

### What is CI/CD?

CI/CD is a method to frequently deliver apps to customers by introducing automation into the stages of app development. The main concepts attributed to CI/CD are continuous integration, continuous delivery, and continuous deployment. CI/CD is a solution to the problems integrating new code can cause for development and operations teams (AKA "integration hell").

Specifically, CI/CD introduces ongoing automation and continuous monitoring throughout the lifecycle of apps, from integration and testing phases to delivery and deployment. Taken together, these connected practices are often referred to as a "CI/CD pipeline" and are supported by development and operations teams working together in an agile way with either a DevOps or Site reliability engineering (SRE) approach.
