---
title: Speexx - Emails System
lang: en
lang_ref: speexx-emails-system
permalink: /en/projects/speexx-emails-system/

date: 2018-08-29

---

The __Emails System__ is composed of three Spring Boot microservices as shown in the following diagram:

** INCLUDE A DIAGRAM HERE **

- __API:__ REST API that allows other services to create emails and retrieve information about them. Also provides endpoints to inform about delivery errors, bounces, etc.
- __Crons__: Responsible for the actual delivery of emails messages using a SMTP server (Haraka) and to update their status. Emails are sent on a schedule, taking into account email priorities and limits to minimize the risk of spamming. This microservice is also responsible for the cleanup of expired emails, both from database and disk storage.
- __Monitor__: Web application providing real time statistical information about emails (incomming, outgoing, queued, errors, etc). It also allows searching for specific emails using a dynamic filtering user interface.

## Details

### Frameworks and Technologies

- Java 8
- Maven
- Spring
    - Boot
    - Cloud
        - Config
        - OpenFeign
    - Data
    - Framework
    - Security
- EclipseLink
- HTML/HTML5
- CSS/CSS3
- JavaScript
- JUnit 5
- Liquibase
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
- Web Applications
- REST APIs
- Test Driven Development
- DevOps
{: class="styled-list styled-list-secondary"}