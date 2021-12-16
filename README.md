# Anypoint Platform Development Fundamentals 

Porpuse of this course:

* Build an application network using <a src="#api_led">API-led connectivity</a> and Anypoint Platform 
    * Usage of Anypoint Platform 
        * As a central repository for the discovery and reuse of assets 
        * To build apps to consume assets and connect systems
        * To take an API through its complete development lifecycle

    * Use of Anypoint Studio
        * Connect to databases, files, web services, SaaS apps, JMS queues, & more
        * Transform data using DataWeave, the transformation language
        * Add application logic and handle errors
        * Structure applications to facilitate development and deployment
        * Handle batch data processing 

---
<h2 id="api_led">API Led-connectivity</h2>

![](https://www.mulesoft.com/sites/default/files/Better%2520way%2520for%2520managing%2520IT%2520Project.JPG)

- It is a new operating model that emphasizes on consumption and production  
- Can have ease of *consumption* and *development*
- It enables the connections for multiple applications with same APIs,
- Produce <a src="https://en.wikipedia.org/wiki/Composability">composable</a> (system design principle, whic provides components that can be selected and assembled in variouscombinations to satisfyspecific user requirements) APIs.
- A web app retrieves information from already created APIs
- Are accesible and discoverable using a web platform and testing them without writting any code, which is <a src="#anypoint_platform">Anypoint Platform</a>

### Those benefits of API-Led connectivity is achieve like a network using nodes to connect services

![](https://blogs.mulesoft.com/wp-content/uploads/2017/07/api-led-architecture.png)


### RESTful web Services as APIs' standard protocol
**Web service** is a method of communication that allows two software systems to exchange data over the internet
- <a src="https://en.wikipedia.org/wiki/Representational_state_transfer">REST - Representational State Transfer</a>, which refers to the fundamentals structures of a software system that uses  <a src="https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods">HTTP methods</a> to access resources and the use of <a src="https://en.wikipedia.org/wiki/JSON">JSON-JavaScript Object Noation</a> and <a src="https://en.wikipedia.org/wiki/XML">XML-Extensible Markup Language</a>to transmit data.

- Are data and resources (assets) represented by <a src="https://en.wikipedia.org/wiki/Uniform_Resource_Identifier"> an URI-Uniform Resource Identificator</a>.

- Resources are accessed or changed using fixed set of operations such as <a src="https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods">HTTP methods</a>. 
![](https://www.oreilly.com/library/view/mastering-python-for/9781788992510/assets/36067bfe-7767-42c3-9d83-1dfe4f7538b4.png)

### Calling APIs using ARC-Advanced REST Client
- When using it, will be use to retrieve data using <a src="https://developer.mozilla.org/es/docs/Web/HTTP/Status">HTTP Status codes</a>:
![](https://miro.medium.com/max/920/1*w_iicbG7L3xEQTArjHUS6g.jpeg)
![](https://install.advancedrestclient.com/images/themes.png)

- <a src="https://install.advancedrestclient.com/install">ARC</a> can be use to make 2 types of calls:
    - Secured: call to an API implementation
    - Unsecured: call to an API proxy

---
<h2 id="anypoint_platform">Anypoint Platform</h2>
