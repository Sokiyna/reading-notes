Event Driven Applications
Review, Research, and Discussion
Why is access control important?

Access controls limit access to information and information processing systems.
Describe an application that would need access control.

Login credentials (such as usernames and passwords). PINs and one-time passwords (OTPs). Virtual private network (VPN) access to internal networks.

What is a role used for?

define who can access what and do what.
Why is role based access control more scalable than discretionary or mandatory access control?

Use encryption to store secrets within .git repositories.
Use environment variables.
Use "Secrets as a service" solutions.


Vocabulary Terms
Authorization :
is the process of verifying what they have access to.
Role Based Access Control :
is a security paradigm whereby users are granted access to resources based on their role.
Capabilities :
What can authorized user do in.
Event-Driven Programming in Node.js


Node.js uses events heavily and it is also one of the reasons why Node.js is pretty fast compared to other similar technologies.

As soon as Node starts its server, it simply initiates its variables, declares functions and then simply waits for the event to occur.

In an event-driven application, there is generally a main loop that listens for events, and then triggers a callback function when one of those events is detected.



Although events look quite similar to callbacks, the difference lies in the fact that callback functions are called when an asynchronous function returns its result, whereas event handling works on the observer pattern.

The functions that listen to events act as Observers.

Following is the syntax to bind an event handler with an event :

// Bind event and event handler as follows eventEmitter.on('eventName', eventHandler);

We can fire an event programmatically as follows :
// Fire an event eventEmitter.emit('eventName');