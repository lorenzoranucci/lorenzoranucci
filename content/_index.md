+++
title = "About Lorenzo"
+++

## About Me

{{< figure class="avatar" src="/avatar.jpeg" >}}

Building software solutions for me is not only a job but above all a **passion** and **great fun**.

Solving problems has always been very challenging for me. I am the kind of person who spoils moments among friends by
proposing and asking riddles!

Although this work is already very stimulating in itself, I believe it is essential that what I build has a practical,
useful, noble, and ethical **purpose**; this is what drives my job search and pushes me to invest all my energy in my
daily work.

[GitHub](https://github.com/lorenzoranucci) | [LinkedIn](https://www.linkedin.com/in/lorenzo-franco-ranucci-859416b2/)

## Experience

### [ProntoPro](https://prontopro.it)

#### _Jun 2019 - Now_

At **ProntoPro** I am having the most rewarding and training experience of my now decade-long career.
I think telling about my experience in ProntoPro expresses in the best possible way what I am as a professional.

Here I'm proud to work on a product that has the **purpose of helping hundreds of thousands of
people** allowing, on the one hand, professionals to find jobs and, on the other hand, customers to solve a
wide variety of problems, from repairing a pipe to organizing a wedding!

I've learned from very experienced and talented colleagues how to build a product by focusing on Backend software
design, but also by observing, learning, and contributing from end to end on different topics in various business
departments and functions.

#### Context

ProntoPro is a professional services marketplace and a company of about 100 people, including
about 40 engineers.

ProntoPro in numbers:

- thousands of job requests per day from customers.
- Tens of thousands of quotes per day from professionals.
- Thousands of logins per day.
- Millions of registered users.
- Thousands of active users.
- Terabytes of data.

Teams are dynamically assigned on a 6-week periodic basis according to
the [ShapeUp](https://basecamp.com/shapeup) workflow;
3 to 8 cross-functional teams are generally composed per cycle.

We use DevOps and cloud-native philosophy and approach: software is tested, integrated, built, and released
continuously, frequently (
several times a week) and automatically. We use **Drone** for CI/CD, build **Docker images**, specify
infrastructure as a code with
**Helm** charts that are deployed to **Kubernetes** in staging and production environments that are as similar as
possible.
Applications are monitored through **Prometheus**, **Grafana**, and **Sentry**.

The Backend software system consists of a discontinued Php monolith and a dozen **Go and Php microservices** under
development and expansion.
The strategy is to build microservices with dedicated databases according to the **12-Factor** principle and
**event-driven architecture**.

The visualization part is completely isolated in Frontend services, whose data is provided by the Backend API.

Machine learning applications are developed by Data Science and Data Engineering with support from Backend.

#### Duties

As a software engineer, my daily work consists of several activities, which are frequently and continuously iterated:

- I work side by side with cross-functional figures on features' ideation and requirements specification, using
  tools such as **Example Mapping** and **Gherkin**. At this stage, we also try to analyze at a high level whether the
  effort required by the project meets the time expectations of the business management and eventually how to outline an MVP
  and how to deconstruct a large project into sequential iterations. Here the principles of the **Agile Manifesto** are
  my main guide.
- I collaborate with other engineers on how to define fast implementation iterations that provide working, reliable, 
  maintainable and scalable software as output. Here we use **feature flags** and **Asana** as tools.
- I implement the software in collaboration with other colleagues. Here **pair/mob programming** practices, **code
  reviews**, and **TDD** are critical to ensure high quality and fast feedback loops that guarantee a satisfactory time to market.

As a member of the Backend Core team and as a Backend Engineer with the greatest seniority, I am responsible for:

- leading the technical recruiting steps for Backend roles.
- Driving the Backend technical evolution defining vision, strategies, and tactics.
- Mentoring for the technical growth of colleagues.
- Conducting technical-themed talks.
- Ensuring the best development experience by gathering feedback from my colleagues with biweekly 1:1s.

As a member of the Architecture team, I am responsible for:

- managing relationships with other engineering functions.
- Driving the Engineering evolution by defining vision, strategies, tactics, and roadmap.

#### Timeline

- **Principal Backend Software Engineer** | _May 2022 - Present_
    - Main achievements:
        - Contributed to building a new Matching Algorithm to join customers and professionals based on
          past behaviors using
          machine learning, bringing a significant impact on the company's revenues.
        - Built the first feature in the company that reliably implements an Event-driven architecture based on Kafka
          and the outbox pattern.
- **Senior Backend Software Engineer** | _Apr 2021 - May 2022_
    - Joined the Backend Core and Architecture teams.
    - Main achievements:
        - Built the first microservice to use CQRS, domain modeling (DDD), and event-driven architecture based on
          RabbitMQ.
- **Backend Software Engineer** | _Jun 2019 - Apr 2021_
    - Main achievements:
        - Search Engine Result Page (SERP): gives consumers the ability to search and filter between ~ 1M professionals
          from ~1k of different kinds of jobs in six countries. It's a Go microservice, receiving data from a monolithic
          Php application via RabbitMQ messages, storing them and making them searchable in Elasticsearch. It also
          calculates job prices using Elasticsearch aggregations.
        - Authentication System: this allows our clients to authenticate using the OAuth 2.0 + OpenID standards. It runs
          on a custom Go microservice for the Identity Provider part and on [ory/hydra](https://github.com/ory/hydra)
          for the OAuth 2.0 and OpenID flow orchestration.
        - Online badge: stores and exposes the online status of the professionals. It's a Go microservice that receives
          professionals' heartbeats sent by FE clients, stores them in Redis (until they expire), and exposes an online
          status for professionals.

### Backend Software Engineer at Accenture

#### _Oct 2018 - Apr 2019_

I worked as a consultant for the Italian traffic police. I managed the technological modernization of a complex legacy
system for the management of manual and automatic fines. Java with Swing framework and Oracle DB were the technology
used.

### Software and Data Engineer at UmbriaDigitale

#### _Nov 2014 - Oct 2018_

As a Data Engineer, I managed the transformation of relational and textual data in Linked Open Data. This includes the
design of ETL processes, the choice of appropriate RDF ontologies, and the build of a SPARQL database.

As a Software Engineer, I developed web applications in Java and Php.

### Freelance Software Engineer

#### _Sep 2013 - Oct 2018_

Engineering of web and mobile applications.
Technologies: Magento 2, Joomla, PHP 7, Java 7, Android, MySQL, HTML, JavaScript, CSS.


---

## Contact

* Email: [lorenzofranco.ranucci@gmail.com](mailto:lorenzofranco.ranucci@gmail.com)
* Phone: [+393494191878](tel:+393494191878)
* Address: Via Carlo Alberto 53, Roma (RM), 00185
* Date of birth: 11-08-1991
