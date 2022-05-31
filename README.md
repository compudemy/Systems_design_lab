# Systems_design_lab
We are going to design a system in lab session

# Overview
#### Crucial for DevOps implementation
#### The four design processes
#### A phase of the SDLC 

# 1. Definition 
Systems design is the process of defining elements of a system like modules, architecture, components and their interfaces and data for a system based on the specified requirements.


# 2. Systems design in SDLC
The systems development life cycle (SDLC) is a conceptual model used in project management that describes the stages involved in an information system development project, from an initial feasibility study through maintenance of the completed application. SDLC can apply to technical and non-technical systems.

Systems Design is a stage or component in any System Development Life Cycle (SDLC)

Most SDLC obey the following structure :
  * System development strategies
  * System specification
  * **System design**
  * Decision support
  * System verification and validation
  * System deployment, operations, and support

# 3. Systems design in DevOps 
Designing system in DevOps involves a number of technologies called in a precise order. 
The purpose is to build scalable, reliable and maintainable systems.
The technologies involved are : 
* **Docker** to containerize our systems
* **Kubernetes** for containers orchestration
* **Helm** for building charts or deployment templates
* **Argo CD, Jenkins** … to automate the deployments.


 In DevOps there is a need to move from the **Monolith Approach** to the **Micro Services Approach**. 
 - The Monolith approach considers the system with its sub systems to be part of a single resource supplier.
 In a monolithic design, application tiers can be described as:
part of the same unit
managed in a single repository
sharing existing resources (e.g. CPU and memory) 
developed in one programming language
released using a single binary
![image](monolith.png)

 - The Micro service approach isolates each functionality to make it stand as a service feeding on its own resources.
In a microservice design, application tiers are managed independently, as different units. Each unit has the following characteristics:
managed in a separate repository
own allocated resources (e.g. CPU and memory)
well-defined API (Application Programming Interface) for connection to other units 
implemented using the programming language of choice
released using its own binary
![image](microservice.png)


# 4. Systems design processes 

* Stakeholders expectations
* Requirements definition
* Logical decomposition 
* Design solution definition

![image](processes.png)






