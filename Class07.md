# Reading: **REST**



# **How I explained REST to my brother**


## **1.Who is Roy Fielding?**


### Roy Thomas Fielding (born 1965) is an American computer  scientist, one of the principal authors of the HTTP specification and the originator of the Representational State Transfer (REST) architectural style. He is an authority on computer network architecture and co-founded the Apache HTTP Server project .

![img1](https://miro.medium.com/max/638/0*GN2n0rtrVwEN5XlM).


## **2.Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?**

### For Example when it comes to developing good study habits, there is a method to all of the madness. The type of techniques habits that you’ve come to practice techniques may not work so well . However, you can certainly build on those practices to make your techniques habits more disciplined—because you’ll need to you’ll have more responsibility, but you’ll also have more independence. That’s why we need to be able to talk to all of the machines in the world.


## **3.What is the HTTP protocol that Fielding and his friends created?**


### The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypermedia information systems. HTTP clients generally use Transmission Control Protocol (TCP) connections to communicate with servers. HTTP utilizes specific request methods in order to perform various tasks.


## **4.What does a GET do?**



### The GET method means retrieve whatever information (in the form of an entity) is identified by the Request-URI. If the Request-URI refers to a data-producing process, it is the produced data which shall be returned as the entity in the response and not the source text of the process, unless that text happens to be the output of the process.

### The semantics of the GET method change to a "conditional GET" if the request message includes an If-Modified-Since, If-Unmodified-Since, If-Match, If-None-Match, or If-Range header field. A conditional GET method requests that the entity be transferred only under the circumstances described by the conditional header field(s). The conditional GET method is intended to reduce unnecessary network usage by allowing cached entities to be refreshed without requiring multiple requests or transferring data already held by the client.

## **5.What does a POST do?**
### The POST method is used to request that the origin server accept the entity enclosed in the request as a new subordinate of the resource identified by the Request-URI in the Request-Line. POST is designed to allow a uniform method to cover the following functions:

 * Annotation of existing resources;
 * Posting a message to a bulletin board, newsgroup, mailing list,
   or similar group of articles;
 * Providing a block of data, such as the result of submitting a
   form, to a data-handling process;
 * Extending a database through an append operation.

### The actual function performed by the POST method is determined by the server and is usually dependent on the Request-URI. The posted entity is subordinate to that URI in the same way that a file is subordinate to a directory containing it, a news article is subordinate to a newsgroup to which it is posted, or a record is subordinate to a database.

### The action performed by the POST method might not result in a resource that can be identified by a URI. In this case, either 200 (OK) or 204 (No Content) is the appropriate response status, depending on whether or not the response includes an entity that describes the result.


## **6.What does PUT do?**

### In general the HTTP PUT method replaces the resource at the current URL with the resource contained within the request. PUT is used to both create and update the state of a resource on the server.


## **7.What does PATCH**

###  is a set of changes to a computer program or its supporting data designed to update, fix, or improve it. This includes fixing security vulnerabilities and other bugs, with such patches usually being called bugfixes or bug fixes. 

![img](https://www.lifewire.com/thmb/axudpSIiCtcBl6W_NLD_ixhAo08=/2264x1326/filters:fill(auto,1)/laptop-bug-fix-lvcandy-istock-vectors-getty-images-56a6fa1b5f9b58b7d0e5ce40.jpg)



## Referenses:
* [How I explained REST to my brother](https://gist.github.com/brookr/5977550)


