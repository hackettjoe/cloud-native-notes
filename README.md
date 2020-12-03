# My cloud-native-notes
> Notes about cloud-native topics

## Table of Contents

- [Microservices](#Microservices)

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
- 
