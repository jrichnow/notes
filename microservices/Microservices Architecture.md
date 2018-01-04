# Microservice Architecture [[1](#1)]

* "A microservice should be _small_ and _simple_ enough that anybody in the organization be able to modify or rewrite it in a trivial amount of time."

* "Speed and Safety at Scale"
  - tension between speed and safety
  - scale introduces additional tension and need of coordination across teams --> slows down progress

* The **Microservice Design Canvas** [[3](#3)][[4](#4)]
  - captures the essential service attributes to guide development of the service as well as consuming apps
  - high level description of a service in terms of 
    + Consumer Tasks
    + Interface (queries, commands, event subscription/publication)
    + Qualities
    + Logic/Rules
    + Data
    + Dependencies

## Organisation

* "Microservice Architecture is a software architecture style and the corresponding organizational culture that do exactly that: prioritize minimization of required coordination." [[2](#2)]
  - Coordination Elimination as core value of microservice architecture  
    1. Technology Heterogeneity – removes need to coordinate programming languages, frameworks, libraries and technology platforms across multiple teams.
    2. Partitioned Scalability and Independent Deployments – basically remove the need to coordinate deployments and operation of various parts of the system across teams.
    3. Composability and Replaceability remove the need to coordinate life-cycle management of parts of the larger system, across various teams.

## Resources

* <a name="1">[1] [Microservice Architecture - Aligning Principles, Practices, and Culture](http://shop.oreilly.com/product/0636920050308.do)
* <a name="2">[2] [Microservices Are All About Avoiding Coordination Cost](http://www.freshblurbs.com/blog/2016/09/27/microservices-coordination-removal.html)
* <a name="3">[3] [The Microservice Design Canvas](http://www.apiacademy.co/the-microservice-design-canvas/)
* <a name="3">[4] [Streamlined Microservice Design in Practice](https://dzone.com/articles/streamlined-microservice-design-in-practice)
