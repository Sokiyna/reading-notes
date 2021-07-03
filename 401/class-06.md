## Modern Token Authentication in Node with Express

Token authentication is the hottest way to authenticate users to your web applications nowadays. There’s a lot of interest in token authentication because it can be faster than traditional session-based authentication in some scenarios, and also allows you some additional flexibility. In this post, I’m going to teach you all about token authentication: what it is, how it works, why you should use it, and how you can use it in your Node applications. Let’s get to it!

### What Is Token Authentication?

Token authentication is a way to authenticate users into an application using a temporary token (typically a JSON Web Token) instead of actual credentials.
The way this works in the context of web authentication is like so:
A user wants to log into a website
A user supplies their email address and password to the website (their credentials)
The website generates a token for the user
The user’s browser stores the token
When the user makes subsequent requests to the website, their token will be sent along with their request
The website will validate the token and use it to figure out who the user is
The benefit of this approach is that tokens contain embedded information about the user, so the website can receive the token and discover who the user is and what permissions they have without necessarily needing to talk to a central database. This means you may not need to maintain a session store.

### What are JSON Web Tokens?

Before we talk about JSON Web Tokens, let’s clarify some terms:
Authentication is the process of verifying a user’s identity.
A token is an object that can be used to authenticate a user to a server. Tokens contain embedded user data that is used to identify and authenticate the user.
JSON Web Tokens (JWTs) are an open standard (learn more about JWTs here) (Links to an external site.) that define a secure way to transmit information between parties using a JSON object. JWTs are always cryptographically signed (sometimes encrypted) and can be signed using a secret key (symmetrical) or a public/private key pair (asymmetrical).
JWTs are the most popular type of tokens and are often what people mean when they refer to “token authentication” in general.

### Review, Research, and Discussion

##### Explain what a “Singleton” is (in Computer Science terms)

A Singleton is an object which can only be instantiated one time. Repeated calls to its constructor return the same instance and in this way one can ensure that they don’t accidentally create, say, two Users in a single User application.

##### Singleton Pattern in JavaScript

The Singleton Pattern limits the number of instances of a particular object to just one. This single instance is called the singleton.


### Term

Router Middleware => Router level middleware can be defined in the same way as application-level middleware

Dynamic Module Loading => The dynamic module loader library allows code to retrieve Node modules from a web server, install them locally and serve them up as though they’d been manually deployed to the running server.
Singleton Pattern => The Singleton Pattern limits the number of instances of a particular object to just one. This single instance is called the singleton.

Mock Testing => Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones. … Such a service can be replaced with a mock object.

### Preview

Which 3 things had you heard about previously and now have better clarity on?

bcrypt
auth
express router
Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
testing
linked list
What are you most excited about trying to implement or see how it works?
bcrypt
auth



