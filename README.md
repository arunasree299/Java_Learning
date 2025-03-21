# Java_Learning

**Spring Framework:**
- Spring is a very popular Java framework for building web and enterprise applications.
- Spring is very popular for several reasons:
- dependency injection
    - Easy to use but powerful database transaction management capabilities
    - Good Integration with other Java frameworks like JPA/Hibernate ORM, Struts/JSF/etc. web frameworks
- Web MVC framework for building web applications
**Problem with using Spring Framework alone**
  Basically, Spring-based applications have a lot of configurations.
  
***For example:***
When we develop Spring MVC web application using Spring MVC then we need to configure:
Component scan, Dispatcher Servlet, View resolver, Web jars(for delivering static content) amongother things.
When we use Hibernate/JPA in the same Spring MVC application then we would need to configure a Data source, Entity manager factory/session factory, Transaction manager among other things.
When you use cache, message queue, NoSQL in the same Spring MVC application then we need to
configure:
Cache configuration
Message queue configuration
NoSQL database configuration



