
# HTTP  STATUS CODES

## Protocole

  The protocol that makes internet connectivity possible is the http hypertext transfer protocol, which is of two different types.

  HTTP-Hyper Text Transfer Protocol (http://www.google.com) (when not logged into gmail account)
 
  Secure HTTPS-Hyoer Text Transfer Protocol (https://www.google.com)(when signed in)

  What is the difference?
  
   ==> http:// is only used before a web address as a front end request, its connection is simple data transfer. But if https:// is used to encrypt passwords and data in one of the encryption techniques (mainly 128 bits).

## HTTP status codes

The HTTP status codes are completely different from the basic explanation above, but they are related. The blog doesn't need to worry about HTTPS as it will be for websites that use encryption and are banking related. Anyway, now coming to the blog, if a web page address is typed in the address bar, then the browser will automatically add http now on most browsers, this http part is hidden. will search for the title (title optimization).

 An HTTP status code is a code that is sent to the user about the current state of the website (the blog is a subdomain, it is also a website).
 
 ## STATUS CODE DEFNITIONS
 
 >- **1xx-Informational codes**

>- **2xx-Request successful codes**

>- **3xx-Request Redirect codes**

>- **4xx-Request Incomplete**

>- **5xx-Server Errors**

These are the status codes which are used.

#### 1. successful request

- ***200 OK*** – The request was successful.

- ***201 Created*** - The request was successful and new content was created based on this request.

- ***202 Accepted*** – The request was successfully received, but may not be processed immediately.

- ***203 Unauthorized Information*** – The request was successful, but the information sent to the client regarding the response came from a third-party server.

- ***204 No Content*** – ​​The request was successful but no data was returned. 

- ***205 Reset Content*** – ​​The server requests to reset submitted information, such as form data.


#### 2. Redirects


- ***300 Multiple Choices***- Response indicating requested content has been moved or more options match the request.

- ***301 Moved Permanently*** - The requested document has been moved permanently and the response contains the URI of this new location. Important to use when modifying the domain name or URL of an existing document.

- ***302 Found*** – The requested document has been temporarily moved to another location. The new location URI is returned with the response. 303 and 307 are more specific versions of this type and implemented since HTTP/1.1.

- ***303 See Other (HTTP/1.1)*** – The requested document was found and responded with a URI where the document can currently be found.
 
- ***304 Unmodified*** – The requested document has not changed since it was last requested. The client loads the document from the cache.

- ***305 Using a proxy*** – The requested document can only be accessed through a specific proxy.

- ***307 Temporary Redirect (HTTP/1.1)*** – The requested document could be temporarily found at a different URI, provided in the response. This is a purer version of what 302 usually means.

- ***206 Partial content*** – ​​Successful request response for only part of the document.


#### 3. Client Errors

- ***400 Bad Request*** – The server did not understand the request.

- ***401 Unauthorized*** - The client must be authorized before accessing, usually through some kind of login.

- ***403 Forbidden*** – Client does not have access to the requested document. If it appears on a document that should be, it could be a permissions issue.

- ***404 Not Found*** - The requested document was not found at the specified URL and no new location was specified for the document. It doesn't mean that the document is definitely missing from the given URL.

- ***405 Method Not Allowed*** – The request method is not allowed for the specified document.

- ***406 Not Acceptable*** – The requested document could not be sent in a way understood by the client.

- ***407 Proxy Authentication Required*** – The client must be authorized by the proxy before it can send the requested document.

- ***408 Request Timeout*** – The request time exceeds the time the server is configured to wait for the request.

- ***409 Conflict*** – The requested document could not be sent due to a conflict in the request.

- ***410 Gone*** - Same as 404, except it means that the document has permanently disappeared from the URL and no new location is specified.

- ***411 Request Length*** – The request was denied because the body length must be specified by the client.

- ***412 Precondition Failed*** – At least one condition of the request failed.

- ***413 Request Entity Too Large***– The request is larger than the server can handle. A common example of this is if a file is submitted through a published form and is larger than the server settings allow for a message.

- ***414 Request URI Too Long*** – URL is longer than the server can handle. The URL causing this error usually contains thousands of characters, so this is rarely a problem.

- ***415 Unsupported Media Type*** – Indicates that the format of at least part of the request is not supported.

- ***416 Requested Range Not Satisfiable***– The request could not be met. Can happen if the client requests a part of the document that doesn't exist.

- ***417 Expectation Failed*** - The server was unable to respond to requests sent in the "Expect" header field.


#### 4. Server Errors

- ***500 Internal Server Error*** - General error message means something went wrong, but more specific information could not be sent.

- ***501 Not Implemented*** – The server does not support what is needed to make the request.

- ***502 Bad Gateway*** – The server acting as the gateway or proxy received an invalid response from the upstream server.

- ***503 Service Unavailable*** - The server is currently unavailable due to high load, maintenance, or other temporary situation.

- ***504 Gateway Timeout***– The server acting as the gateway or proxy did not receive a response for the time the server was configured to wait for a response. 

- ***505 HTTP Version Not Supported*** – The server does not support the HTTP protocol used by the client for the request.
