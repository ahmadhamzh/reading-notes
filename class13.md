# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

- persistent local storage is one of the areas where native client applications have held an advantage over web applications .

- Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

   - Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.

   - Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL).

   - Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful.

- One of the DHTML Behaviors was called userData, and the userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. (Trusted domains, such as intranet sites, can store 10 times that amount. And hey, 640 KB ought to be enough for anybody.).

- HTML5 set out to provide a standardized API, implemented natively and consistently in multiple browsers, without having to rely on third-party plugins.

-  HTML5 Storage is Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

- “5 megabytes” is how much storage space each origin gets by default. This is surprisingly consistent across browsers, although it is phrased as no more than a suggestion in the HTML5 Storage specification.

-
   