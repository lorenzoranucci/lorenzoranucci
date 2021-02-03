+++
title = "About Lorenzo"
+++

## About Me

{{< figure class="avatar" src="/avatar.png" >}}

> The goal of the architect is to create a shape for the system that recognizes policy (business rules and procedures) as the most essential element of the system while making the details irrelevant to that policy. This allows decisions about those details to be delayed and deferred.

These words of Robert Martin are a guide for me. I'm not interested in being the best Go / Php / Java programmer or a Kubernetes guru or a skilled MySQL and Elasticsearch user or the one who knows every feature of Symfony and Spring - these are just details for me. 

I want to design systems that give maximum value to my business, that are able to scale, that are flexible to change using the right trade-offs.

[GitHub](https://github.com/lorenzoranucci) | [LinkedIn](https://www.linkedin.com/in/lorenzo-franco-ranucci-859416b2/)

---

## Experience

### Backend Software Engineer at [ProntoPro](https://prontopro.it)
#### Jun 2019 - Present

I work on new features of the product and on enhancing the backend system in general. Here are some relevant activities:

- Search Engine Result Page (SERP): gives consumers the ability to search and filter between ~ 1M professionals from ~ 1k of different types of jobs. It's a Go microservice, receiving data from a monolithic Php application via AMQP messages, storing them and making them searchable in Elasticsearch. It also calculates job prices using Elasticsearch aggregations.
- Authentication System: allows our clients to authenticate using the OAuth 2.0 + OpenID standards. It runs on a custom Go microservice for the Identity Provider part and on [ory/hydra](https://github.com/ory/hydra) for the OAuth 2.0 + OpenID flow orchestration.
- Online badge: stores and exposes the online status of the professionals. It's a Go microservice that receives professionals heartbeats sent by FE clients, stores them in Redis (until they expire) and exposes an online status for professionals with a not-expired heartbeat.
- Many features related to our core monolithic application. It runs Php 7.4 application with Symfony 4.4. Having huge tables and high availability requirements I had to manage database schema/data migrations without downtime and queries optimization (MySQL 5.7 and Doctrine).
- Enhancement of DevOps: CI/CD (using Drone), infrastructure (Kubernetes with Helm Charts), dev-environment (docker-compose).

ProntoPro is an amazing startup, full of very talented people from whom I learn a lot. Here I learned to work in an agile paced and remote oriented environment, to communicate in English on a daily basis, to measure between quality and velocity, to build stuff that scales and is reliable, to avoid breaking changes, to use KISS, SOLID, DDD, TDD, to have useful retrospectives to improve Cycle after Cycle, to follow solid coding standards and enforce them through CI and Code Reviews.

### Backend Software Engineer at Accenture
#### Oct 2018 - Apr 2019
I worked as a consultant for the Italian traffic police. I managed the technological modernization of a complex legacy system for the management of manual and automatic fines. Java with Swing framework and Oracle DB were the technology used.

### Software and Data Engineer at UmbriaDigitale
#### Nov 2014 - Oct 2018

As a Data Engineers I managed the transformation of relational and textual data in Linked Open Data. This includes the design of ETL processes, the choice of appropriate RDF ontologies, the build of a SPARQL database.

As a Software Engineers I developed web applications in Java and Php.

### Freelance Software Engineer
#### Nov 2014 - Oct 2018

Analysis, design, development, testing, delivery and maintenance of web and mobile applications.
Tech: Magento 2, Joomla, PHP 7, Java 7, Android, MySQL, HTML5, JavaScript, CSS

---
## Expectations

In the near future, I expect to find time to contribute to open source projects.

From my career, I expect to become a Staff Engineer in a remote-first company.

From my life, I expect to live with my family in my hometown, Montefiascone.

---

## Buzzwords related to my work:

`Clean coding principles` `Software architecture` `DDD` `SOLID principles` `Extreme Programming` `Go` `Php` `Java` `Docker` `Git` `GitHub` `MySql` `Elasticsearch` `Redis` `RabbitMQ` `Symfony` `Agile Practices` `Kubernetes` `Helm Charts` `Natural Language Processing` `Linked Open Data` `Code Reviews` `TDD`

---

## Contact

* Email: [lorenzofranco.ranucci@gmail.com](mailto:lorenzofranco.ranucci@gmail.com)
* Phone: [+39-3494191878](tel:+39-3494191878)
* Address: Via Carlo Alberto 53, Roma (RM), 00185