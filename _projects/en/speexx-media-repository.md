---
title: Speexx - Media Repository
lang: en
lang_ref: speexx-media-repository
permalink: /en/projects/speexx-media-repository/

date: 2019-02-06

---

The __Media Repository__ is a Spring Boot microservice responsible for receiving and serving media files (audios and videos) recorded by both students and trainers. Upon reception, it also transcodes the media files from WEBM format to MP4 and vice versa, so the media files are compatible with most modern web browsers.

Since transcoding is a CPU and memory-intensive process, the application keeps a global queue ensuring that only one task is running at any given time.

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
- REST APIs
- Test Driven Development
- DevOps
{: class="styled-list styled-list-secondary"}