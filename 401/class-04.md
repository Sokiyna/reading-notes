### Data Modeling
Data modeling (data modelling) is the process of creating a data model for the data to be stored in a database. ... Data modeling helps in the visual representation of data and enforces business rules, regulatory compliances, and government policies on the data.


### What is Data Modelling?
Data modeling (data modelling) is the process of creating a data model for the data to be stored in a database. This data model is a conceptual representation of Data objects, the associations between different data objects, and the rules. Data modeling helps in the visual representation of data and enforces business rules, regulatory compliances, and government policies on the data. Data Models ensure consistency in naming conventions, default values, semantics, security while ensuring quality of the data.

### Why use Data Model?

The primary goal of using data model are:

Ensures that all data objects required by the database are accurately represented. Omission of data will lead to creation of faulty reports and produce incorrect results.
A data model helps design the database at the conceptual, physical and logical levels.
Data Model structure helps to define the relational tables, primary and foreign keys and stored procedures.
It provides a clear picture of the base data and can be used by database developers to create a physical database.
It is also helpful to identify missing and redundant data.
Though the initial creation of data model is labor and time consuming, in the long run, it makes your IT infrastructure upgrade and maintenance cheaper and faster.

#### In what case would you need to use beforeEach() or afterEach() in a test suite?

If you have some work you need to do repeatedly for many tests, you can use beforeEach and afterEach.

#### What is one downside of Test Driven Development?

Tests got to be maintained when requirements change

#### What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?

a class defines a type which can be instantiated at runtime, whereas a prototype is itself an object instance.

#### Why REST?

highly scalable, simple, and easy to modify and extend.

# Document the following Vocabulary Terms
**functional programming** is a programming paradigm where programs are constructed by applying and composing functions. When a pure function is called with some given arguments, it will always return the same result, and cannot be affected by any mutable state or other side effects.
**object-oriented programming (OOP)** Object-oriented programming (OOP) is a fundamental programming paradigm used by nearly every developer at some point in their career.
**class**is Classes are a template for creating objects. They encapsulate data with code to work on that data. Classes in JS are built on prototypes but also have some syntax and semantics that are not shared with ES5 class-like semantics.
**super**is keyword is used to access and call functions on an object’s parent. super.prop super[expr].
**this** refer current class instance object.
**Test Driven Development (TDD)** is a process of modifying the code in order to pass a test designed previously. includes refactoring a code i.e. changing/adding some amount of code to the existing code without affecting the behavior of the code.
**Jest** is a JavaScript testing framework designed to ensure correctness of any JavaScript codebase
**Continuous Integration (CI)** is workflow strategy, development features with modular code in more manageable increments.
**REST** is a software architectural style which uses a subset of HTTP. It is commonly used to create interactive applications that use Web services. A Web service that follows these guidelines is called RESTful.
**Data Model** is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities. For instance, a data model may specify that the data element representing a car be composed of a number of other elements which, in turn, represent the color and size of the car and define its owner. 
# Preview
## Which 3 things had you heard about previously and now have better clarity on?
* beforeEach() and afterEach()
* REST
* Object Oriented Programming
## Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
* see the result of what we want to do before start.
* MData model
* TDD and CI/CD
## What are you most excited about trying to implement or see how it works?
modeling data using non-relational database.
# nosql vs sql
> SQL databases are primarily called as Relational Databases (RDBMS).
> SQL databases are table based databases whereas NoSQL databases are document based, key-value pairs, graph databases or wide-column stores. 
> SQL databases have predefined schema whereas NoSQL databases have dynamic schema for unstructured data.
> For scalability: In most typical situations, SQL databases are vertically scalable.
## SQL Database Examples
*  MySQL Community Edition.
* MS-SQL Server Express Edition.
* Oracle Express Edition
## NoSQL Database Examples
* MongoDB.
* CouchDB.
* Redis.
# nosql modeling techniques
NoSQL databases are compared by various non-functional criteria, such as scalability, performance, and consistency. This aspect of NoSQL is well-studied both in practice and theory because specific non-functional properties are often the main justification for NoSQL usage and fundamental results on distributed systems like the CAP theorem apply well to NoSQL systems. 
##  New evolution of data models began:
* Key-Value storage is a very simplistic, but very powerful model. Many techniques that are described below are perfectly applicable to this model.
* One of the most significant shortcomings of the Key-Value model is a poor applicability to cases that require processing of key ranges. Ordered Key-Value model overcomes this limitation and significantly improves aggregation capabilities.
* Finally, Graph data models can be considered as a side branch of evolution that origins from the Ordered Key-Value models.
## General Notes on NoSQL Data Modeling


> NoSQL data modeling often starts from the application-specific queries as opposed to relational modeling
> NoSQL data modeling often requires a deeper understanding of data structures and algorithms than relational database modeling does. 
> Data duplication and denormalization are first-class citizens.


## Terms
 
functional programming: is a way of thinking about software construction by creating pure functions.

object-oriented programming (OOP): is a computer programming model that organizes software design around data, or objects, rather than functions and logic.

class: is a blueprint for creating objects.

super: the parent class of the derived one.

this: pointer to the current object you are using.

Test Driven Development (TDD): is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases.

Jest: is a JavaScript testing framework maintained by Facebook, Inc.

Continuous Integration (CI): is a software development practice in which developers merge their changes to the main branch many times per day.
