
# Spring RequestMapping

`@RequestMapping`

- annotation is used withweb requests

- it will require a path or a route

 ## mapping an HTTP request to a method using some basic criteria:-
### @RequestMapping — the HTTP Method

this method has no default.so we need to define value .

### HTTP Headers in RequestMapping
1. headers Attribute 
 * specifying a header for the request or multiple headers in the form of a key and a value. 

2. RequestMapping Consumes and Produces 

* annotation  has the produces and consumes attributes.
* starting from Spring 3.1 we have produces and consumes attributes in our @RequestMapping .

### RequestMapping With Path Variables 
1. Single @PathVariable

If the name of the method parameter is the same of @PathVariable varible we can use it without value. 

 2. Multiple @PathVariable 
 need more values.
 3. @PathVariable With Regex

 you can use Regular expressions with the mapping. 


 ### RequestMapping With Request Parameters 

 we are sending  value of the  parameter using the @RequestParam(“id”) annotation.


## RequestMapping Corner Cases

- Multiple Paths Mapped to the Same Controller Method,
 you can use mapping with multiple requests to the same method. 

  in @RequestMapping the value attribute accepts multiple mappings. 

  - Multiple HTTP Request Methods to the Same Controller Method 

 - Multiple requests using different HTTP verbs can be mapped to the same controller method

 -  Fallback for All Requests 

 - Ambiguous Mapping Error 
 it occurs when Spring evaluates two or more request mappings to be the same for different controller methods.  

  Note: A request mapping is the same when it has the same HTTP method, URL, parameters, headers, and media type.

## Mapping Shortcuts 
in spring 4.3 

- @GetMapping
- @PostMapping
- @PutMapping
- @DeleteMapping
- @PatchMapping

# Accessing Data with JPA 

building an application that uses Spring Data JPA to store and retrieve data in a relational database 

it will stores Java Objects in a memory-based database.

requirements:
- editor or IDE
- JDK 1.8 or higher 
- gradle or maven 
- spring tool suite STS 
- intelij IDEA 
 
#  spring data repositories 

1. CrudRepository 
its methods:
- save(…) – save an Iterable of entities. Here, we can pass multiple objects to save them in a batch
- findOne(…) – get a single entity based on passed primary key value
- findAll() – get an Iterable of all available entities in database
- count() – return the count of total entities in a table
- delete(…) – delete an entity based on the passed object
- exists(…) – verify if an entity exists based on the passed primary key value

2. PagingAndSortingRepository
it methods:
- findAll(Pageable pageable) 
 which is the key to implementing Pagination.

 create a Pageable object with certain properties and we've to specify at least:

- Page size
- Current page number
- Sorting

note: 
it extends CrudRepository

3. JpaRepository 
its methods: 
- findAll() – get a List of all available entities in database
- findAll(…) – get a List of all available entities and sort  - them using the provided condition
- save(…) – save an Iterable of entities. Here, we can pass  - multiple objects to save them in a batch
- flush() – flush all pending task to the database
- saveAndFlush(…) – save the entity and flush changes immediately
- deleteInBatch(…) – delete an Iterable of entities. Here, we can pass multiple objects to delete them in a batch

note: it extends PagingAndSortingRepository which means it has all methods present in the CrudRepository as well.




