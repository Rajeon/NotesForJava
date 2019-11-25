CORS 
CROSS ORIGIN RESOURCE SHARING
 Cross-origin resource sharing is a mechanism that allows JavaScript on a web page to make AJAX requests to another domain, different from the domain from where it originated.
 CORS capability works by adding some specific HTTP headers that tell the browser that downloaded webpage should be allowed to make web requests to given/all domains. Also, you can add information to instruct browser to allow only certain HTTP methods (GET/PUT/POST/DELETE etc) on those domain URLs.
 
 Application Program Interface=(API)
 Java application programming interface (API) is a list of all classes that are part of the Java development kit (JDK). It includes all Java packages, classes, and interfaces, along with their methods, fields, and constructors. These prewritten classes provide a tremendous amount of functionality to a programmer.

POSTMAN:
 Postman is a powerful HTTP client for testing web services. Created by Abhinav Asthana, a programmer and designer based in Bangalore, India, Postman makes it easy to test, develop and document APIs by allowing users to quickly put together both simple and complex HTTP requests
 POSTMAN COMMANDS:
 POST - HTTP POST requests supply additional data from the client (browser) to the server in the message body.
 GET - GET requests include all required data in the URL.
 PUT - The PUT method requests that the enclosed entity be stored under the supplied Request-URI.
 DELETE - The DELETE method requests that the origin server delete the resource identified by the Request-URI. 
 
 Mockito:
 Mockito is a mocking framework, JAVA-based library that is used for effective unit testing of JAVA applications. Mockito is used to mock interfaces so that a dummy functionality can be added to a mock interface that can be used in unit testing. Mockito facilitates creating mock objects seamlessly. It uses Java Reflection in order to create mock objects for a given interface. Mock objects are nothing but proxy for actual implementations.
 
 Karma & Jasmine:
 A tool called Karma is a JavaScript test runner created by the AngularJS team. Jasmine is the testing framework that we talked about in the getting started with unit testing for AngularJS post, and Karma provides helpful tools that make it easier to us to call our Jasmine tests whilst we are writing code.
 
 Difference between CommandLineRunner & CommandLine
    CommandLineRunner is an interface used to indicate that a bean should run when it is contained within a SpringApplication
    CommandLine is a program that takes commands in and operate through your computer system to run.
    @bean annotation is used to represent any class or method as logical unit of reusable code in an application
    
    Enums in Java:
    Enumerations serve the purpose of representing a group of named constants in a programming language.


Microservices:
Microservices are a form of service-oriented architecture style (one of the most important skills for Java developers) wherein applications are built as a collection of different smaller services rather than one whole app.

Microservices are a software development technique—a variant of the service-oriented architecture (SOA) architectural style that structures an application as a collection of loosely coupled services. In a microservices architecture, services are fine-grained and the protocols are lightweight.

Microservices, when used effectively, pay off
Used effectively, microservice architectures allow you to scale your application as the number of developers working on your application increases. ... That means keep tracking each time a new service is added to your system or a new connection between microservices is made

Why spring boot is used for Microservices?
Spring Boot enables building production-ready applications quickly and provides non-functional features: Embedded servers which are easy to deploy with the containers. It helps in monitoring the multiples components. It helps in configuring the components externally.

A microservice is a small, loosely coupled distributed service. Microservice Architectures evolved as a solution to the scalability and innovation challenges with Monolith architectures (Monolith applications are typically huge – more 100, 000 line of code). It allows you to take a large application and decompose or break into easily manageable small components with narrowly defined responsibilities.


Reasons to use microservices:
For a large application, it is difficult to understand the complexity and make code changes fast and correctly, sometimes it becomes hard to manage the code.
Applications need extensive manual testing to ensure the impact of changes.
For small change, the whole application needs to be built and deployed.
The heavy application slows down start-up time.


Benefits of microservices:
Small Modules –
Application is broken into smaller modules which are easy for developers to code and maintain.
Easier Process Adaption –
By using microservices, new Technology & Process Adaption becomes easier. You can try new technologies with the newer microservices that we use.
Independent scaling –
Each microservice can scale independently via X-axis scaling (cloning with more CPU or memory) and Z-axis scaling (sharding), based upon their needs.
Unaffected –
Large applications remain largely unaffected by the failure of a single module.
DURS –
Each service can be independently DURS (deployed, updated, replaced, and scaled).


Restrictions of microservices:
Configuration Management –
As it becomes granular the headache comes for configuring the services and monitoring those. You need to maintain configurations for hundreds of components across environments.
Debugging –
Tracking down the service failure is painstaking job. You might need to look into multiple services across different components. Centralized Logging and Dashboards are essential to make it easy to debug problems.
Automation – Because there are a number of smaller components instead of a monolith, you need to automate everything – Builds, Deployment, Monitoring etc.
Testing –
Needs a greater effort for end to end testing as it needs all the dependent services to be up and running.


Microservice frameworks for java:
There are several microservices frameworks that you can use for developing for Java. Some of these are:

Spring Boot –
This is probably the best Java microservices framework that works on top of languages for Inversion of Control, Aspect Oriented Programming, and others.
Dropwizard –
Dropwizard pulls together stable, mature libraries from the Java ecosystem into a simple, light-weight package that lets you focus on getting things done.
Restlet –
Restlet Framework helps Java developers build better web APIs that follow the REST architecture style.
Spark –
A micro-framework for creating web applications in Kotlin and Java 8 with minimal effort.

Lambda Functions:
Java lambda expressions are Java's first step into functional programming. A Java lambda expression is thus a function which can be created without belonging to any class. A Java lambda expression can be passed around as if it was an object and executed on demand.


UML: 
Unified Modeling Language (UML) is a general purpose modelling language. The main aim of UML is to define a standard way to visualize the way a system has been designed. ... UML is not a programming language, it is rather a visual language. We use UML diagrams to portray the behavior and structure of a system

UML is not a programming language, it is rather a visual language. We use UML diagrams to portray the behavior and structure of a system. UML helps software engineers, businessmen and system architects with modelling, design and analysis. The Object Management Group (OMG) adopted Unified Modelling Language as a standard in 1997. Its been managed by OMG ever since. International Organization for Standardization (ISO) published UML as an approved standard in 2005. UML has been revised over the years and is reviewed periodically

Lambda Parameters:
Since Java lambda expressions are effectively just methods, lambda expressions can take parameters just like methods. The (oldState, newState) part of the lambda expression shown earlier specifies the parameters the lambda expression takes. These parameters have to match the parameters of the method on the single method interface. In this case, these parameters have to match the parameters of the onStateChange() method of the StateChangeListener interface

Matching Lambdas to Interfaces:
A single method interface is also sometimes referred to as a functional interface. Matching a Java lambda expression against a functional interface is divided into these steps:

Does the interface have only one abstract (unimplemented) method?
Does the parameters of the lambda expression match the parameters of the single method?
Does the return type of the lambda expression match the return type of the single method?
If the answer is yes to these three questions, then the given lambda expression is matched successfully against the interface.

Interfaces With Default and Static Methods
From Java 8 a Java interface can contain both default methods and static methods. Both default methods and static methods have an implementation defined directly in the interface declaration. This means, that a Java lambda expression can implement interfaces with more than one method - as long as the interface only has a single unimplemented (AKA abstract) method.

In other words, an interface is still a functional interface even if it contains default and static methods, as long as the interface only contains a single unimplemented (abstract) method. Here is a video version of this little section

With lambda expressions the type can often be inferred from the surrounding code. For instance, the interface type of the parameter can be inferred from the method declaration of the addStateListener() method (the single method on the StateChangeListener interface). This is called type inference. The compiler infers the type of a parameter by looking elsewhere for the type - in this case the method definition. Here is the example from the beginning of this text, showing that the StateChangeListener interface is not mentioned in the lambda expression

React:
The main point about React is the ability to define more abstract components out of a model (props) and a state. In this simple contact example, a natural refactoring to do is to define a component to render the contacts. ... The React.js definitions are complex ones, which are hard to translate “as is” in Java
