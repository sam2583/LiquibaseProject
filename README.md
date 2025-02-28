#  Spring Boot + Liquibase Integration

This project demonstrates how to integrate **Liquibase** with **Spring Boot** for database version control.

##  Why Use Liquibase?
Liquibase helps manage database changes in a structured and versioned way. It allows for easy rollbacks, multiple environments, and collaboration in teams.

---

## 🚀 Getting Started

### ** Add Liquibase Dependency**
In your **`pom.xml`**, add the following dependency:

```xml

<dependency>
    <groupId>org.liquibase</groupId>
    <artifactId>liquibase-core</artifactId>
    <version>x.x.x</version> <!-- Use the latest version -->
</dependency>

```
 ### ** changeLog files init **
 ```xml

<?xml version="1.0" encoding="UTF-8"?>
<databaseChangeLog
    xmlns="http://www.liquibase.org/xml/ns/dbchangelog"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:schemaLocation="http://www.liquibase.org/xml/ns/dbchangelog
        http://www.liquibase.org/xml/ns/dbchangelog/dbchangelog-4.8.xsd">

</databaseChangeLog>

```
