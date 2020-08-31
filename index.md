---

layout: col-sidebar
title: OWASP Cloud-Native Security Project
tags: cloud-native
level: 2
type: documentation
pitch: A top-level project to unite all that is Cloud-Native security

---

## What is Cloud-Native?

According to the [Linux Foundation][linux]:
> “Cloud native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. Containers, service meshes, microservices, immutable infrastructure, and declarative APIs exemplify this approach.”

Although there is no consensus of its definition, we can outline that Cloud Native is a development and deployment methodology, in which applications are built as microservices and orchestrated as containers to take advantage of the cloud computing model. The term Cloud can be confusing as some may assume the strict necessity to deploy this type of software in a Cloud Provider, but as a matter of fact, the **where** question is not the most relevant, although many organizations will aim to do so.  If the applications are designed as loosely coupled systems, optimized for scalability and performance, and managed through container orchestration, they are cloud-native. 

[linux]: https://github.com/cncf/foundation/blob/master/charter.md#1-mission-of-the-cloud-native-computing-foundation

## The OWASP Cloud-Native Security Projects
### Purpose
Since the idea of Cloud-Native is relatively new, there are not enough knowledge sources about its security aspects. The size and width of this topic just make the knowledge gap even greater. This project will try to bridge that gap by aggregating new and existing initiatives, under the same Cloud-Native Security roof.
### Roadmap
#### CloudSheep (work in progress - estimated beta release: Q4 2020)
> “I'm not totally useless. I can be used as a bad example.”
>
> -- Victor Hugo

CloudSheep is an intentionally vulnerable Cloud-Native application. By making a deliberately insecure app, we can demo frequent errors and show security mistakes that are commonly seen in the industry.

With real Cloud-Native architecture, different roles, and many endpoints, CloudSheep is a good example of what-not-to-do when it comes to securing your Cloud-Native application. It will be the perfect platform for educating software developers and security professionals about the challanges of Infrastructure as Code (IaC) and the pitfalls of Cloud-Native architecture.
#### Cloud-Native Security FAQ (work in progress - estimated beta release: Q4 2020)
Trying to close the huge knowledge gap, one question at a time.
#### Cloud-Native Security Top 10 (work in progress - estimated beta release: Q1 2021)
A flagship project that will result in a very clear awareness document about the Top 10 Cloud-Native Security Vulnerabilties that must be addressed first.

## Licensing
**The OWASP CN Security Project documents are free to use!**

The OWASP CN Security Project is licensed under the [Creative Commons Attribution-ShareAlike 3.0 license][license], so you can copy, distribute and transmit the work, and you can adapt it, and use it commercially, but all provided that you attribute the work and if you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one.

[license]: https://creativecommons.org/licenses/by-sa/3.0/
