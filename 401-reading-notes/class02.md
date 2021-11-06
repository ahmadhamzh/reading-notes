# Review, Research, and Discussion


* ## **What’s the difference between PUT and PATCH?**
 *the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.*

* ## **services that allow you to “mock” an API for development:**

-  Postman  : 
>https://[mock-id].mock.pstmn.io/[request-path]

- Mocky : 
>  https://run.mocky.io/v3/[unique id]

- Mockable :
>https://[user-id].mockable.io/[request path]

* ## **Compare and contrast Swagger and APIDoc.js** 

**Popularity:** By comparing stats,  swagger-ui is more popular then apidocjs.

Consistency: If we already using swagger for our Dotnetcore service, then implementing swagger tool will consist more from Info and UI prospective.

**Implementation complexity:** apidocjs and swagger both required documentation content on implemented method as customize comment data. In addition they allow to write documentation data in separate resource file as .js and .json. If we already have swagger.json created by DotnetCore we can reuse more than 80% specification.

 **Maintenance:** For apidocjs will have to modify documentation for each affected method/endpoints if service changed. In swagger we can limit changes. But by implementing apidocjs we can isolate the layer.

**Other benefits:** Because swagger use plain .json that could be parsed through programing language, thus we can get advantage of various other 3rd parties in order to create http client and more. 

**Future:** Due to popularity of swagger, apidocjs provide information about apidoc-swagger converter so we can switch apidoc to swagger anytime.

* ## Which HTTP status codes should be sent with each type of (un)successful API call

Informational responses (100–199)
Successful responses (200–299)
Redirection messages (300–399)
Client error responses (400–499)
Server error responses (500–599)

* ## Compare and contrast SOAP and REST

SOAP (Simple Object Access Protocol) is a standards-based web services access protocol that has been around for a long time.

REST (Representational State Transfer) is another standard, made in response to SOAP’s shortcomings.

**Soap Advantages**

• Language, platform, and transport independent (REST requires use of HTTP).

•  Works well in distributed enterprise environments (REST assumes direct point-to-point communication).

• Standardized.

• Provides significant pre-build extensibility in the form of the WS* standards.

• Built-in error handling.

• Automation when used with certain language products.

REST Advantages

• No expensive tools require to interact with the web service.

• Smaller learning curve.

• Efficient (SOAP uses XML for all messages, REST can use smaller message formats).

• Fast (no extensive processing required).

• Closer to other web technologies in design philosophy.

---
# Express/Node introduction

## **Node.js**

### Introducing Node

* Node (or more formally Node.js) is an open-source, cross-platform runtime environment that allows developers to create all kinds of server-side tools and applications in JavaScript. The runtime is intended for use outside of a browser context (i.e. running directly on a computer or server OS).

* From a web server development perspective Node has a number of benefits :

   * Great performance! Node was designed to optimize throughput and scalability in web applications and is a good solution for many common web-development problems (e.g. real-time web applications).

   * Code is written in "plain old JavaScript", which means that less time is spent dealing with "context shift" between languages when you're writing both client-side and server-side code.

   * Code is written in "plain old JavaScript", which means that less time is spent dealing with "context shift" between languages when you're writing both client-side and server-side code.

   * The node package manager (NPM) provides access to hundreds of thousands of reusable packages. It also has best-in-class dependency resolution and can also be used to automate most of the build toolchain.

   * Node.js is portable. It is available on Microsoft Windows, macOS, Linux, Solaris, FreeBSD, OpenBSD, WebOS, and NonStop OS. Furthermore, it is well-supported by many web hosting providers.

   * It has a very active third party ecosystem and developer community, with lots of people who are willing to help.

### **Introducing Express**

* Express is the most popular Node web framework, and is the underlying library for a number of other popular Node web frameworks. It provides mechanisms to:

  * Write handlers for requests with different HTTP verbs at different URL paths (routes).

  * Integrate with "view" rendering engines in order to generate responses by inserting data into templates.

  * Set common web application settings like the port to use for connecting, and the location of templates that are used for rendering the response.

  * Add additional request processing "middleware" at any point within the request handling pipeline.
  ---
  to see more about how to creat node application and codeing see this [Link](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction#introducing_express).
  ----
  ----

  ## **npm** 

* npm is the world's largest software registry. Open source developers from every continent use npm to share and borrow packages, and many organizations use npm to manage private development as well.

npm consists of three distinct components:

the website - 
 the Command Line Interface (CLI) - 
 the registry

* Use npm to . . .

  * Adapt packages of code for your apps, or incorporate packages as they are.

  * Download standalone tools you can use right away.

  * Run packages without downloading using npx.

  * Share code with any npm user, anywhere.

  * Restrict code to specific developers.

  * Create organizations to coordinate package maintenance, coding, and developers.

  * Form virtual teams by using organizations.

  * Manage multiple versions of code and code dependencies.

  * Update applications easily when underlying code is updated.

  * Discover multiple ways to solve the same puzzle.

  * Find other developers who are working on similar problems and projects.
---
 to learn mpre about npm and CLI visit this [link](https://docs.npmjs.com/about-npm)
 ---
 ---

 ### **TDD**

 * **Definition** : “Test-driven development” refers to a style of programming in which three activities are tightly interwoven: coding, testing (in the form of writing unit tests) and design (in the form of refactoring).

 * It can be succinctly described by the following set of rules : 

   * write a “single” unit test describing an aspect of the program.

   * run the test, which should fail because the program lacks that feature.

   * write “just enough” code, the simplest possible, to make the test pass.

   * “refactor” the code until it conforms to the simplicity criteria.

   * repeat, “accumulating” unit tests over time

* **Expected Benefits**

   * many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort.

  * the same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases.

  * although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling.

---
 to learn mpre about npm and CLI visit this [link](https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1))
 ---
---

