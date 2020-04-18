---
title: Actor Systems with Akka.net
theme: serif
highlight-theme: github
background-image: 
---

## Actor Systems with Akka.net 💫

![dsa](images/company-logo.png)

![akka.net logo](https://getakka.net/Images/akkalogo.png)

[Alberto Gregorio](https://albertogregorio.com)

2020-04-18

---

# Actor Model

What is an Actor?
History of the actor model

----

### Actors are..

- everything 🦄 (Everything is an actor)
- lightweight
- stateful

----

### Actors can..

- receive messages 
 - process sequentially
- change internal state
- send new messages
- span children

----

### Location transparency

- Actor References instead of direct communication
- Communication only via messages (that can be routed)
- Dead letter concept
- Actors can be located in the same machine or in a different country

---

# Akka.net

- repository stats

----

- Actor Model
- Lightweight event-driven processes (1M+ actors per GB)
- Message-based Communication
- 

----

Simple and high-level abstractions for concurrency and parallelism

----

### Let it crash

- Supervisor hierarchy
- Self restoring
- Persistency/Journaling

----

## Where does Akka.net comes from

- Scala (JVM)
- Akka 
  - add stats

----

## Basic Actors

- Untyped
- Typed

----

### States

- Become/Unbecome (stack state)


----

## Routers

----

## Remote

- Akka.Remote

-----

## Overview of other capabilities

- Akka.Cluster
- Akka.Persistence
- Akka.Streams

----

## Akka.net Pros

- Resilient
- Scalable
- Very performant

----

## Akka.net Cons

- Not so easy to get started
- Yet another abstraction
- Complex distributed logic is still complex

----

### Alternatives: Distributed Computing

[Microsoft Orleans](https://dotnet.github.io/orleans/)

![ms orleans](https://raw.githubusercontent.com/dotnet/orleans/gh-pages/assets/logo_full.png)

----

### Alternatives: Serverless

[Azure Functions](https://azure.microsoft.com/de-de/services/functions/)

![ms functions](https://blog.palfinger.ag/wp-content/uploads/2018/10/0_SboqG9ze_J63PJ2i-696x310.png")

----

### Where to find more info

- [Akka.net (docs, howto)](http://getakka.net)
- [GitHub repo](https://github.com/akkadotnet/akka.net)
- [Petabridge (bootcamps)](http://akka.net)
- [Lightbend/Typesafe (original Akka devs)](https://www.lightbend.com/akka-platform)
