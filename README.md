# My cloud-native-notes
> Notes about cloud-native topics

## Table of Contents

- [Microservices](#Microservices)
- [Monoliths](#Monoliths)

---

## Microservices
- Microservices are independently deployable services modeled around a business domain. A microservice architecture is based on multiple collaborating microservices.
- microservices expose the business capabilities that they encapsulate via one or more network endpoints
- They also encapsulate data storage and retrieval, exposing data, via well-defined interfaces

Independent Deployability
- is the idea that we can make a change to a microservice and deploy it into a production environment without having to utilize any other services (this is actually how you
manage deployments in your system)
- To guarantee independent deployability, we need to ensure our services are loosely coupled—in other words, we need to be able to change one service without having to change anything else

Modeled Around a Business Domain
- having a 3-tier architecture isn't a bad choice, however it's typically optimized around a group of people/familiarity
- moving forward software architecture changes and are now grouped around multiple skilled teams to reduce silos

Owning data
- microservices should NOT share a database
- design a service that asks for data outside of its own purview; this gives the service the ability to decide what is shared and what is hidden
- Having stable interfaces between services is essential if we want independent deployability

Advantages of Microservices
- it does open up new models and deployments for improving scale and robustness of systems
- segregating services by a business domain brings developers ease-of-use when solving software issues, who owns what, etc.
- enhances flexibility
- technology agnostic - as long as your services can communicate with each other via a network

Size
- is an interesting topic but how do you measure a microservice it terms of its size? Lines of code? Application stack?
- a microservice is just that, it's micro in nature
- should be as small as possible yet provide as much functionality as possible
- it's really about two things: 1) how many microservices can you handle?, and 2) define microservice boundaries

---

## Monoliths






























