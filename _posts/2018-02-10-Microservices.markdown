---
layout: post
title: Microservices
date: 2018-02-10 15:46
comments: true
external-url: https://medium.com/@shilpaAB/microservices-b2171d28a0d1
categories: Technology
---

![microservice](/assets/microservices.png)


There has been a great deal of talk about Microservice these days. So how exactly is it different from the traditional/monolith architectural design? How is is different from SOA or the Service Oriented Architecture? Here is how I found answers to these questions.

Microservices in simple words is a way of decentralizing an application into smaller, well defined chunks, each performing an important task independently. Also, there needs to be a way these can talk to one another and solve the problem. A good example is the Microservice architecture built by Netflix.

We can assertively say that microservices are quite similar to SOA. We can imagine microservices to be a small portion of a much bigger entity called the SOA. Microservices can be deployed independently whereas SOA is deployed as a single monolith. SOA is majorly focused on re-use of services unlike microservices which is all about decoupling.

![SOA](/assets/SOA.png)

There are quite a few perks that come with the Miroservices:

<b>1. Exploring advantages of a variety of data stores. </b> A monolith architecture is restricted to choose a single database/datastore. This prevents the application from leveraging the advantages of other datastores simultaneously. However, each microservice can connect to its own datastore. It can also have its own platform.

<b>2. Enables partial deployments and Agility. </b>Generally, waiting time is a major overhead when deploying products in production is under question. This is because the development time for each feature varies widely. Microservice preserves modularity and offers the benefit of deploying each feature separately. This hence suits Agile development environment.

<b>3. Decentralized Infrastructure. High Availability. </b>Traditional architecture has a dependency on a single database. This causes a ‘single point of failure’. A single corruption/bug is enough to bring the whole application down. Decentralization ensures infrastructure failure remains confined to a single entity without affecting the entire application. Downtime is also significantly reduced.

## Challenges:

Designing an architecture with completely independent services along with language agnostic APIs to communicate between the services can be complex.
Organization embracing the change is a challenge. Provisioning of Infrastructure, seamless communication between application and devops team, Rapid Application decan prove to be tough.
Testing a microservice application is much more cumbersome compared to a traditional application.
Multiple replication of data/redundancy can lead to low consistency.

## References and further reading:
 - [microservices.io](http://microservices.io/)
 - [Youtube - Microservices by Martin Fowler](https://www.youtube.com/watch?time_continue=1&v=wgdBVIX9ifA)

 This article can also be found on Medium - [Microservices by Shilpa](https://medium.com/@shilpaAB/microservices-b2171d28a0d1)