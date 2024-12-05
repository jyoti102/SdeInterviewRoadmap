### Servlet Questions:- 
1.  Servlet 
1.  Servlet Life Cycle 
1.  Load on startup 
1.  Session tracking in servlet 

---

### JSP Questions:- 
1.  JSP 
1.  Difference between JSP and Servlet 
1.  JSP Life Cycle 
1.  Scripting elements in JSP 
1.  JSP Implicit Objects 
1.  Page Directives 
1.  JSP:Action Tags 
1.  Forward vs Redirect 
1.  Include directive vs Include action tag. 
1.  request.getParameter() vs request.getAttribute() 
1.  request.getSession(false) vs request.getSession(true) 

---

#### Points to remember:- 
> request.getSession() will return a current session, if current session doesn’t exist it will create new one,
> request.getSession(true) will return a current session, if current session doesn’t exist it will create new one,
> request.getSession(false) will return current session, if current session doesn’t exist
> it will not create new one it return null.

---
### Restful Services:- 
1.  Difference between Rest and Soap.
1.  Steps to create restful service. 
1.  @Path, @GET, @POST, @PUT, @DELETE, @PathParam, @QueryParam, @FormParam @Consumes, @Produces, @Provider. 

### Difference between Rest and SOAP:- 
1.  SOAP is a protocol, Rest is an architectural style. 
1.  SOAP is simple object access protocol, Rest is representational state transfer
1.  SOAP can’t use Rest, but Rest can use SOAP because it can use any protocol like HTTP, SOAP etc. 
1.  SOAP permits xml data only, Rest permits Plain text, HTML, XML,JSON 
1.  SOAP uses interfaces to expose business logic, Rest uses URI and methods like (GET, PUT, POST, DELETE) 
1.  JAX-WS is the Java API for SOAP web services, JAX-RS is the Java API for Restful web services 

#### Points to remember:- 
> To do certain activities such as Filtering-Request/Response,
> Exception Handling, the JAX-RS has its own default implementation logic.
> However, it allows users to provider their own implementation as well.
> To provide our implementation we need to implement the appropriate classes by specifying them with @Provider annotation.
> JAX-RS will do a round of scanning to find the existence of any such user-defined implementation by searching for @Provider annotation. 

