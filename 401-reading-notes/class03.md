# Express REST API

### Review, Research, and Discussion

* Name 3 real world use cases where you’d want to change the request with custom middleware?

  * authentication
  * post & put methode to get the body
  * error handelling

* True or false: The route handler is middleware?

false : the rout it self isn't a amiddleware but some times use a middleware to get som data from the request.

* In what ways can a middleware function end the process and send data to the browser?

in case there is an error in the request and we thrwon N ERROR to response with .

* At what point in the request lifecycle can you “inject” middleware? 

after the request been send from the client and before it reach the route in the server .


 
Middleware | Middleware is software that enables one or more kinds of communication or connectivity between two or more applications.
-|-
Request Object |  the main entry point for an application to issue a request to the Library .
Response Object | The Response interface of the Fetch API represents the response to a request.
Application Middleware |  it's a middleware that you use on global lvl to be apply on all the applecation
Routing Middleware | it's a middelware that you use it only with the request that belong to specific route
Test Driven Development | a software development practice that focuses on creating unit test cases before developing the actual code.
Behavioral Testing | Behavioral tests measure behavioral competencies.

### Skim read

  * Which 3 things had you heard about previously and now have better clarity on?

     * TDD
     * middaleware
     * router Paths

  * Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

     * TDD
     * middaleware
     * router Paths


  * What are you most excited about trying to implement or see how it works?
    
    * all the same

    ----
     ### refrences : 

    [Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

    [Using Express Routing](https://expressjs.com/en/guide/routing.html)

    [Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)




