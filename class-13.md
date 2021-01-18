# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS
- Persistent local storage is one of the areas where native client applications have held an advantage over web applications.
- The operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state.
- Web applications have had none of these luxuries, but cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data.
- Cookies three potentially dealbreaking downsides:
  1. Cookies are included with every **HTTP request**, thereby slowing down your web application by needlessly transmitting the same data over and over.
  2. Cookies are included with every **HTTP request**, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL).
  3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful.
- But to implement web applications we need a lot of storage space on the client that persists beyond a page refresh and isn’t transmitted to the server.

# A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5
- In the beginning, there was only Internet Explorer.
- Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, **Internet Explorer**. 
- Microsoft invented DHTML Behaviors and userData as a behavior.
- ***userData*** allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.
- In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “***Flash cookies***.”
- The feature in *Flash* is properly known as Local Shared Objects.
- Brad Neuberg developed an early prototype of a Flash-to-JavaScript bridge called AMASS (AJAX Massive Storage System).
- Brad rewrote AMASS and integrated it into the popular Dojo Toolkit under the moniker dojox.storage.
- Flash gives each domain 100 KB of storage “for free.”
- In 2007, Google launched ***Gears***, which is an open source browser plugin aimed at providing additional capabilities in browsers. 
- Gears provides an API to an embedded SQL database based on SQLite.
- The problem that HTML5 set out to solve is that all of the services that provided are either specific to a single browser, or reliant on a third-party plugin and they all expose radically different interfaces, have different storage limitations, and present different user experiences.
- Web Storage was at one time part of the HTML5 specification proper.
- Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.”
- HTML5 is a way for web pages to store named key/value pairs locally, within the client web browser.
- HTML5 Storage is based on named key/value pairs.
- The named key is a string and the data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.

# TRACKING CHANGES TO THE HTML5 STORAGE AREA
- The storage event is fired on the window object *whenever setItem()*, *removeItem()*, or *clear()* is called and actually changes something.
- The storage event is supported everywhere the localStorage object is supported, which includes Internet Explorer 8.
- “5 megabytes” is how much storage space each origin gets by default.
- “QUOTA_EXCEEDED_ERR” is the exception that will get thrown if you exceed your storage quota of 5 megabytes.
- “SQL” is more of a marketing term than a hard-and-fast standard. (Some would say the same of “HTML5,” but never mind that.) 
- The Indexed Database API exposes what’s called an ***object store***.
