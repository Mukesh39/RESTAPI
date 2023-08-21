# What is REST API's ?
A REST API, which stands for Representational State Transfer Application Programming Interface, is a set of rules and conventions for building and interacting with web services. It's a widely used architectural style for designing networked applications, especially in the context of web-based APIs. REST APIs enable different software applications to communicate and exchange data over the internet by following a set of principles that make interactions simple, scalable, and efficient.

Here are the key concepts that define a REST API:

Resources: In a REST API, everything is considered a resource. A resource can be a piece of data, an object, or even a service that the API exposes.
Uniform Interface: REST APIs have a consistent and uniform way of interacting with resources. They use standard HTTP methods, such as GET, POST, PUT, and DELETE, to perform specific actions on resources.
Stateless: Each request from a client to the server must contain all the information needed to understand and process the request. The server doesn't maintain any information about the client's state between requests.
Client-Server Architecture: REST APIs separate the client (user interface) and server (data storage and processing) components. This separation allows for better scalability and independence between the two.
Cacheable: Responses from a REST API can be cached to improve performance. Caching can be done at various levels, including the client side, intermediary servers, and even the API itself.
Layered System: REST APIs can be designed as a layered system, with each layer responsible for a specific functionality. This enhances modularity and allows for easier updates and modifications.
Representation: Data is exchanged between the client and server in various formats, such as JSON or XML. These formats define how the data is structured and presented.
To interact with a REST API, a client (which could be a web application, mobile app, or any software) sends HTTP requests to the server's API endpoints. Each endpoint corresponds to a specific resource or action, and the server responds with the appropriate data or status codes.

For example, let's consider a REST API for a blog platform:

To retrieve a list of all blog posts, the client sends an HTTP GET request to the /posts endpoint.
To retrieve a specific blog post, the client sends an HTTP GET request to the /posts/{post_id} endpoint.
To create a new blog post, the client sends an HTTP POST request to the /posts endpoint with the necessary data.
REST APIs are widely used because they are simple to understand, promote modularity, and can be consumed by a variety of clients across different platforms and programming languages. They're a fundamental component of modern web development, enabling applications to communicate and share data seamlessly over the internet.



#Resources to refer for This project 

* https://secrets-api.appbrewery.com
* https://axios-http.com/docs/post_example