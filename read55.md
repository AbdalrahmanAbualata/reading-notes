# Spring Security Architecture
## Authentication and Access Control
### Authentication
Authentication in spring is some functionalities to manage access.
We use `AuthenticationManager` for three things:
1. Give access
2. deny access
3. returning back unexpected requests
## Customizing Authentication Managers
We use `AuthenticationManagerBuilder` to customize Authentication Managers as they enable us to set up many details in order to configure the manager.
## Web Security
Spring Security is a powerful and highly customizable authentication and access-control framework. It is the de-facto standard for securing Spring-based applications. Spring Security is a framework that focuses on providing both authentication and authorization to Java applications.
## Filter Chians
### What is a filter spring boot?
A filter is an object used to intercept the HTTP requests and responses of your application. By using a filter, we can perform two operations at two instances − Before sending the request to the controller. Before sending a response to the client.
## Method Security
Spring method security allows us to support/add authorization supports at the method level. On a high level, we can configure which roles are allowed to access what method within the same service class. Let’s take an example of CustomerService class.
Method-level security is implemented by placing the `@PreAuthorize` annotation on controller methods.