
Part One: Solidify Terminology

In your own terms, define the following terms:

    What is HTTP?
    What is a URL?
    What is DNS?
    What is a query string?
    What are two HTTP verbs and how are they different?
    What is an HTTP request?
    What is an HTTP response?
    What is an HTTP header? Give a couple examples of request and response headers you have seen.
    What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?

1. Hypertext Transfer Protocol is an applicationn layer protocol for transmitting documents such as HTML. It helps with communication between web browsers and web servers. 

2. URL stands for Uniform Resource Locator and is the unique address of a given resource on the web.

3. DNS stands for Domain Name System and it translates the human readable domain names we all use to machine readable IP addresses made up of numbers.

4. A query string is a set of characters (parameter) that is part of the URL which is then sent to a query program that gathers that specific information from a database.

5. The HTTP GET method is used to read or retrieve a representation of a resource. These GET requests can only retrieve the information and not alter it. The HTTP POST method is used to create new resources.

6. An HTTP Request is made by a client, to a named host, which is located on a server. The request is to access a resource on the server.

7. An HTTP Response is made by a server to a client. The aim of the response is to provide the client with the resources it requested, or provide further info if it was unable to carry out the request.

8. An HTTP header is a field of an HTTP request or response that passes context and data about requests or responses. Part of the GET request headers is 'Accept-Language' which returns the language the request was made in. A response header would be something like 'Content-type' which would describe what type of files are included in the response. 

9. When you type in the website name in the URL bar and press enter, the browser goes to the DNS server and finds the real address (IP Address) of the server that website lives on. The browser then sends an HTTP request message to that server, asking it to send a copy of the website to the client. The messages and all other data sent between client and server is sent across the internet connection using TCP/IP. If the requests are approved by the server, the server sends a '200 OK' message which acknowledges access to the data and begins transferring different files such as HTML, CSS or JS in chunks called data packets. The browser then assembles the data packets it received and displays it as a complete website. 