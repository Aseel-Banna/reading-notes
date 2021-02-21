# RESET 
- Roy Fielding is one who helped write the first web servers and he did a lot of researches to explain why the server do this journey.
- He and his friends found the HTTP.
- His name is on the specification for the protocol that is used to get pages from servers to your browser.
- Webs are using HTTP protocol.
- ***http***, which is the first word in an url, tells the browser what protocol to use.
- You can think of it like GPS coordinates for knowledge and information.
- The whole world wide web is built on an architectural style called **REST**.
- REST provides a definition of a “resource”, which is what those things point to.
- A web page is a “representation” of a resource.
- URLs tell the browser that there's a concept somewhere. 
- We need some way of having one machine tell another machine about a resource that might be on yet another machine.
- Redirect: when the client ask for something and the server tell the client to get that thing from other servers.
- URL is used to tell machine where are things.
- The reason of sucking machine is that machines don't have a universal noun.
- Some verbs are almost universal like GET, PUT, and DELETE.
- HTTP is all about applying verbs on nouns.
- Web pages are designed to be understood by people.
- Machines basically just need the data. 
- Each of the systems would retrieve information from each other using a simple HTTP GET.
- If one system needs to add something to another system, it would use an HTTP POST.
- If a system wants to replace something in another system, it uses an HTTP PUT.


# SuperAgent
- SuperAgent is light-weight progressive ajax API crafted for flexibility, readability, and a low learning curve after being frustrated with many of the existing request APIs. It also works with Node.js!
- A request can be initiated by invoking the appropriate method on the request ***object***, then ***calling .then()*** (or ***.end()*** or ***await***) to send the request. 
- In web browsers absolute URLs work only if the server implements CORS.
- The Node client supports making requests to Unix Domain Sockets.
- The ***.query()*** method accepts objects, which when used with the **GET** method will form a query-string.
- It can also used for HEAD requests.
- SuperAgent will automatically serialize JSON and forms.
