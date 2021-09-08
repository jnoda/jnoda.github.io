---
title: Speexx - Core Services
lang: en
lang_ref: speexx-core-services
permalink: /en/projects/speexx-core-services/

date: 2020-03-04

---

__Speexx Core Services__ is a Spring Boot web application wrapping most of the business logic and main database access of the Speexx ecosystem, making it available as REST web services for other applications. The implementation of the logic still resides on a shared monolithic artifact, but this is the first step towards decoupling applications that needs access to this logic from the actual implementation.

This project opens the path to evolve a more modular ecosystem by applying a Strangler Fig pattern.
Additionally, allows exposing the business logic to external partners using an API Gateway without additional development cost.

## Details

### Frameworks and Technologies

- Java 8
- Maven
- Spring
    - Boot
    - Cloud
        - Config
    - Data
    - Framework
- EclipseLink
- JUnit 5
- Swagger
{: class="styled-list"}

### Tools and Services 

- IntelliJ IDEA
- Atlassian Suite
    - Jira
    - Confluence
    - Bitbucket (+ Pipelines)
- Git
{: class="styled-list styled-list-secondary"}

### Servers and Platforms

- Firebird
- Tomcat
- Linux (Ubuntu)
{: class="styled-list"}

### Industry Knowledge

- Agile Methodologies (SCRUM)
- Software Architecture
- Software Design
- REST APIs
- Test Driven Development
- DevOps
{: class="styled-list styled-list-secondary"}