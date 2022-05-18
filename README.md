
# **Use of SOA to improve performance and scalability**

## **Overview**

By exposing services using standard network protocols (like SOAP, JSON, ActiveMQ or Apache Thrift) to send requests or access data, SOA prevents developers from having to perform integration from scratch. Instead, they can use patterns called enterprise service buses (ESBs), which perform the integration between a centralized component and backend systems and then make them available as service interfaces. This also allows developers to reuse existing functions instead of recreating them.

## **Benefits over monolithic approach**

- **Faster time to market and greater flexibility:**
    The  reusability of services makes it much easier and faster to assemble applications, instead of developers starting from scratch each time as would be the case with monolithic applications.

- **Use legacy infrastructure in new markets:**
    SOA makes it easier for developers to take the functionality of one platform or environment and scale and extend it to new ones.

- **Easy maintenance:**
    Because all services are self-contained and independent, they can be modified and updated as needed without affecting other services.

- **Scalability:**
    Since SOA permits services to run across multiple services, platforms, and programming languages, scalability is greatly increased. And SOA uses a standardized communication protocol, allowing enterprises to decrease interaction between clients and services. Lowering this level of interaction allows apps to be scaled with less pressure and inconvenience.
  
- **Greater reliability:**
     Since it’s easier to debug smaller services than large code, SOA generates apps that are more reliable.

## **SOA roles:**

1. **Service provider:**
    A service provider creates web services and provides them to a service registry. The service provider is responsible for the terms of use of the service.

2. **Service broker or service registry:**
    A service broker or service registry is responsible for providing information about the service to a requester. A broker may be public or private.

3. **Service requester or service consumer**
    A service requester finds a service in a service broker or service registry and then will connect with the service provider to receive the service.

## **Service-oriented architecture vs. microservices**

The concept of services introduced by service-oriented architecture has become what is now a central component of modern cloud computing and virtualization in things like middleware and microservices.

Because of their similarities, SOA and microservices architecture are often confused. The main characteristic that can help differentiate between them is their scope: SOA is an enterprise-wide approach to architecture, while microservices is an implementation strategy within application development teams.

They also communicate to their respective components differently, with SOA using an ESB while microservices can communicate with each other statelessly, through language-agnostic APIs. The language-agnostic aspect of APIs in microservices also allows dev teams to choose what tools they want to work with. In these ways, microservices can be more tolerant and flexible.

SOA is also sometimes confused with Software-as-a-service. SaaS is a form of cloud computing that delivers a cloud application—and all its underlying IT infrastructure and platforms—to users. Web services in SOA may be delivered by service providers as SaaS applications. Typically, a cloud service provider (like AWS, Azure, or IBM Cloud) manages the cloud environment on which the SaaS application is hosted.

Users interact with the software through a web browser on their computer or mobile devices. They may use APIs like REST or SOAP to connect the software to other functions.

## References

- [Service-oriented architecture - Wikipedia](https://en.wikipedia.org/wiki/Service-oriented_architecture)

- [Service Oriented Architectures with Web Services - YouTube](https://www.youtube.com/watch?v=PZfYM48Gnj8&list=PL_uaeekrhGzK2FapcTxvuuXOwCPSZvFn3)
