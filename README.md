Name: Alif Tanoto
Class: B4CC
Student ID: 2702364950

**What is web application architecture?** 
Let’s start from the very beginning and talk a little about some basic things you need to know about web application architecture. Web application architecture is the foundational framework that shapes the design and development of a web application. It consists of procedures and best practices that determine how various elements of the application — such as the frontend, backend, and database — work together to provide the necessary functionality.

In simpler terms, it’s like a layout that assures smooth interaction between the visible elements users interact with, the server-side logic, and data storage. The goal is to build a seamless, scalable system that meets the application’s functional requirements while also concentrating on performance, security, and ease of maintenance.

**DNS (Domain Name System)**
DNS is a critical component that matches domain names with corresponding IP addresses. It ensures that user requests are routed to the correct server. DNS isn’t created from scratch: third-party services are used when it comes to this aspect of the architecture.

**Load balancer**
The load balancer helps distribute incoming user requests across multiple servers, ensuring that no single server becomes overwhelmed. By spreading the traffic evenly, it prevents overloads and ensures consistent performance. Load balancers help create multiple instances of the same service so all servers handle requests identically. Usually, ready-to-use solutions from cloud providers are used. 

**Web app servers**
These servers are responsible for processing user requests and sending the necessary responses back to the browser. To do this, web app servers communicate with various back-end components such as databases, job queues, and caching servers. These components are the base of the web architecture. 

**Database**
Databases store, retrieve, organize, and update data used by the application. The web app server directly interacts with the database to manage this data, performing operations like creating or updating records.