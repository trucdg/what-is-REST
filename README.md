# 🍌 What is REST?
## REpresentational State Transfer
<img width="674" alt="Screen Shot 2023-07-29 at 1 21 49 PM" src="https://github.com/trucdg/what-is-REST-/assets/91285203/7c2e91a0-8729-406c-9bcc-75ca15ba7dc7">

- REST, or REpresentational State Transfer, is a architectural style for providing standards between computer systems on the web, making it easier for systems to comminucate with each other
- REST-compliant systems (RESTful systems), are characterize by how they are `stateless` and `separate the concerns of client and server`.

## Separation of Client and Server:
- In the REST architectural style, the implementation of the client and the implementation of the server can be done independently without knowing about the other. This means that the code on the client side can be changed at any time without affecting the operation of the server, and the code on the server side can be changed without affecting the operation of the client.
- As long as each side knows what format of messages to send to the other, they can be kept `modular` and `separate`.
- By separating the client and server concerns, we improve the flexibility of the interface across platforms and improve scalability by simplifying the server components. Additionally, the separation allows each component the ability to evolve independently
- By using REST interface, different clients hit **the same REST endpoints**, perform the same actions, and receive the same responses.

## Statelessness
- RESTful system are **stateless**, meaning that the server doesn't need to know about the state of the client and vice versa. In this way, both the server and the client can understand any message received, even without seeing previous messages.

# Communication between Client and Server
Let's explore how the communication between the client and server actually happens when we are implementing a RESTful interface.

In the REST architecture, clients send requests to retrieve or modify resources, and server responses to these requests.

### Making Requests:
REST requires that a client make a request to the server in order to retrieve or modify data on the server. A request generally consist of:
- an HTTP verb, which defined what kind of operation to perform
- a header, which allows the client to pass aling information about the request
- a path to a resource
- an optional message body containing data

### HTTP Verbs
There are 4 basic HTTP verbs we use in requests to interact with resources in a REST system:
1. GET - retrieve a specific resource (by id)
2. POST - create a new resource
3. PUT - update a specific resource (by id)
4. DELETE - remove a specific resource

### Resources:
- [What is REST?](https://www.codecademy.com/article/what-is-rest)













