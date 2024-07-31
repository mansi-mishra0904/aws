# AWS

## What is a failover cluster?
In computing, a failover cluster refers to a group of independent servers that work together to maintain high availability of applications and services. If one of the servers fails, another node in the cluster can take over its workload with little or no downtime. This process is known as failover.

## What is in-memory DB vs DB?
An in-memory database keeps all data in the main memory or RAM of a computer. A traditional database retrieves data from disk drives. In-memory databases are faster than traditional databases because they require fewer CPU instructions. They also eliminate the time it takes to access data from a disk.

## What is AWS Fargate for?
AWS Fargate is a technology that you can use with Amazon ECS to run containers without having to manage servers or clusters of Amazon EC2 instances. With AWS Fargate, you no longer have to provision, configure, or scale clusters of virtual machines to run containers.

## Service models

### SaaS
SaaS is also known as "on-demand software". It is a software in which the applications are hosted by a cloud service provider. Users can access these applications with the help of an internet connection and web browser.

### Characteristics of SaaS
- Managed from a central location
- Hosted on a remote server
- Accessible over the internet

  Ex: pizza comes to home

### PaaS
PaaS cloud computing platform is created for the programmer to develop, test, run, and manage the applications.

### Characteristics of PaaS
- Accessible to various users via the same development application.
- Integrates with web services and databases.
- Builds on virtualization technology, so resources can easily be scaled up or down as per the organization's need.
- Provides an ability to "Auto-scale".

Ex: you went hotel and order pizza

### IaaS
IaaS is also known as Hardware as a Service (HaaS). It is a computing infrastructure managed over the internet. The main advantage of using IaaS is that it helps users to avoid the cost and complexity of purchasing and managing the physical servers.

- Resources are available as a service
- Services are highly scalable
- Dynamic and flexible
- GUI and API-based access
- Automated administrative tasks
- Ex: you make pizza for you

<img src="https://github.com/user-attachments/assets/a63f35a6-b830-4a84-b176-44d680a95c82" width="400" height="300">

### Scaling in Cloud Computing

**Scaling Up (Vertical Scaling):**
- **Definition:** Increasing the capacity of a single server by adding more resources (CPU, RAM, storage).
- **Pros:** Simple to implement, no need to rearchitect applications.
- **Cons:** Physical limits, often requires downtime.
- **Use Case:** Enhancing performance of a single server.

**Scaling Down (Vertical Scaling Down):**
- **Definition:** Reducing the resources of a single server.
- **Pros:** Cost savings, resource optimization.
- **Cons:** Potential performance impact.
- **Use Case:** Saving costs during low demand periods.

**Scaling Out (Horizontal Scaling):**
- **Definition:** Adding more servers or instances to handle increased load.
- **Pros:** Flexibility, redundancy, improved fault tolerance.
- **Cons:** Increased complexity, data consistency challenges.
- **Use Case:** Web applications, microservices needing high availability.

**Scaling In (Horizontal Scaling Down):**
- **Definition:** Reducing the number of servers or instances.
- **Pros:** Cost savings, efficient resource use.
- **Cons:** Load rebalancing needed, potential service interruptions.
- **Use Case:** After a traffic spike when demand decreases.

**Key Tools:**
- **Load Balancers:** Distribute traffic in horizontally scaled setups.
- **Auto-Scaling:** Automatically adjust resources based on demand.
- **Monitoring:** Essential for triggering scaling actions.

**Regions are large geographical areas (often spanning parts of or entire countries).
Availability Zones are individual data centers within a region.**

# Types of Instances 
1. General Purpose Instance: For applications that require a balance of performance and cost. Where you need a prompt response, cost effectiveness, less processing.
2. Compute Instances: for the applications that require a lot of CPU processing.
3. Memory INstances: For applications that requie a lot of RAM
4. Storage Instances: for applications that are huge in size
5. GPU Instances: If we need graphics for processing
