# Ajax

## Overview
In this app we will use the jQuery AJAX method to make requests to server-side APIs. Up to this point, the work we’ve done is entirely client-side, that is, our programs are limited to code that is executed, and data that is generated, within the browser. When we manipulate the DOM, using either vanilla JavaScript or jQuery, we are leveraging the DOM API. An API, or Application Programming Interface, is a set of protocols that allow us to hook into the functionality of another application and use it within our own. The DOM API is an example of a _client_-side API. There are numerous client-side web APIs available to us for extending the functionality of the browser. One such API is XMLHttpRequest. This API allows us to communicate with _server_-side APIs. Companies and organizations that collect and store data often make that data available to web developers to use in their applications. A server-side API is one or more URLs, or endpoints, where we can make requests for data stored on a third-party server.

When we make a request to a server-side API, we have no control over how long the response will take to resolve. This can create issues for us when dynamically generating HTML in the DOM as our JavaScript may execute before we’ve received the data we need to render elements. The acronym AJAX is short for “asynchronous JavaScript and XML”. AJAX is the integration of several technologies to address the asynchronicity of the client-server request-response pattern. XML, short for “extensible markup language”, is a specification for encoding documents similar to HTML. It was the standard format for data exchange for many years, but has been largely replaced by JSON, though we still refer to this approach as AJAX. The fetch API was recently introduced to simplify use of the XMLHttpRequest object without the need for a third-party library, such as jQuery.

## Tools
* JSON
* Ajax
* HTTP GET requests
* Server-side APIs
