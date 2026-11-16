# NM – Semester 7 Practical Lab Manual

## 1. About the Repository
This repository contains the complete, authoritative practical laboratory manual and documentation for the **NM – Semester 7 Practical Laboratory** curriculum. The repository provides comprehensive experiment documentation formatted specifically for academic laboratory records, practical examinations, and enterprise Java development reference.

Each practical experiment is isolated in its own dedicated directory containing an independently compiled, print-ready PDF manual. Additionally, a unified master lab manual compiling all 16 experiments in sequential order is provided in the repository root.

## 2. Purpose
The purpose of this repository is to:
- Provide accurate, standardized documentation for all 16 prescribed practical experiments.
- Supply verified, runnable Java Spring Boot 3.x source code examples with zero omissions.
- Document step-by-step algorithms, setup procedures, software specifications, and verified outputs.
- Offer print-ready, professional A4 PDF documents suitable for practical laboratory records and university practical examinations.

## 3. Technology Stack
The experiments in this lab manual are built using modern enterprise Java standards:
- **Programming Language:** Java 17 (LTS)
- **Framework:** Spring Boot 3.x
- **Build & Dependency Management:** Apache Maven 3.8+
- **Persistence Framework:** Spring Data JPA / Hibernate ORM (Jakarta Persistence API)
- **Database:** H2 In-Memory Relational Database (`jdbc:h2:mem:testdb`)
- **Aspect-Oriented Programming:** Spring AOP / AspectJ
- **API Architecture:** RESTful Web Services (JSON payloads over HTTP)
- **Client Testing Tools:** Postman, Modern Web Browsers, and cURL

## 4. Software Requirements
To replicate and execute the experiments locally, ensure the following software tools are installed:
1. **Java Development Kit (JDK 17):** Configured with `JAVA_HOME` environment variable.
2. **Apache Maven 3.8+:** For building and running Spring Boot applications via CLI.
3. **Integrated Development Environment (IDE):** IntelliJ IDEA, Eclipse, or Visual Studio Code.
4. **Spring Boot Dependencies:**
   - Spring Web (`spring-boot-starter-web`)
   - Spring Data JPA (`spring-boot-starter-data-jpa`)
   - H2 Database Engine (`com.h2database:h2`)
   - Spring AOP (`spring-boot-starter-aop`)
5. **API Testing Client:** Postman or cURL for dispatching HTTP GET, POST, PUT, and DELETE requests.

## 5. Experiment Index

| Experiment | Title | PDF Manual | Folder |
|:---:|:---|:---:|:---:|
| **EX_01** | Inversion of Control (IoC) and Bean Management in Spring Boot | [View PDF](./EX_01_Inversion_of_Control_and_Bean_Management/EX_01_Inversion_of_Control_and_Bean_Management.pdf) | [Folder](./EX_01_Inversion_of_Control_and_Bean_Management/) |
| **EX_02** | Creating a Basic REST Controller with Multiple Endpoints | [View PDF](./EX_02_Basic_REST_Controller_and_Endpoints/EX_02_Basic_REST_Controller_and_Endpoints.pdf) | [Folder](./EX_02_Basic_REST_Controller_and_Endpoints/) |
| **EX_03** | Dependency Injection Using Constructor Injection in Spring Boot | [View PDF](./EX_03_Dependency_Injection_via_Constructor/EX_03_Dependency_Injection_via_Constructor.pdf) | [Folder](./EX_03_Dependency_Injection_via_Constructor/) |
| **EX_04** | Pagination and Sorting with Spring Data JPA and H2 Database | [View PDF](./EX_04_Pagination_and_Sorting_with_Spring_Data_JPA/EX_04_Pagination_and_Sorting_with_Spring_Data_JPA.pdf) | [Folder](./EX_04_Pagination_and_Sorting_with_Spring_Data_JPA/) |
| **EX_05** | Derived Query Methods in Spring Data JPA | [View PDF](./EX_05_Derived_Query_Methods_in_Spring_Data_JPA/EX_05_Derived_Query_Methods_in_Spring_Data_JPA.pdf) | [Folder](./EX_05_Derived_Query_Methods_in_Spring_Data_JPA/) |
| **EX_06** | Updating Existing Records Using Spring Data JPA and H2 | [View PDF](./EX_06_Updating_Records_in_Spring_Data_JPA/EX_06_Updating_Records_in_Spring_Data_JPA.pdf) | [Folder](./EX_06_Updating_Records_in_Spring_Data_JPA/) |
| **EX_07** | Custom Repository Implementation Using EntityManager and JPQL | [View PDF](./EX_07_Custom_Repository_Implementation_with_EntityManager/EX_07_Custom_Repository_Implementation_with_EntityManager.pdf) | [Folder](./EX_07_Custom_Repository_Implementation_with_EntityManager/) |
| **EX_08** | Complete CRUD Operations Using Spring Data JPA | [View PDF](./EX_08_Complete_CRUD_Operations_with_Spring_Data_JPA/EX_08_Complete_CRUD_Operations_with_Spring_Data_JPA.pdf) | [Folder](./EX_08_Complete_CRUD_Operations_with_Spring_Data_JPA/) |
| **EX_09** | Ticket Booking and Cancellation System with Spring Data JPA | [View PDF](./EX_09_Ticket_Booking_and_Cancellation_System/EX_09_Ticket_Booking_and_Cancellation_System.pdf) | [Folder](./EX_09_Ticket_Booking_and_Cancellation_System/) |
| **EX_10** | Aspect-Oriented Programming (AOP) with Spring Boot Advices | [View PDF](./EX_10_Aspect_Oriented_Programming_with_Spring_AOP/EX_10_Aspect_Oriented_Programming_with_Spring_AOP.pdf) | [Folder](./EX_10_Aspect_Oriented_Programming_with_Spring_AOP/) |
| **EX_11** | RESTful API for Coach Management with Spring Data JPA | [View PDF](./EX_11_RESTful_API_for_Coach_Management/EX_11_RESTful_API_for_Coach_Management.pdf) | [Folder](./EX_11_RESTful_API_for_Coach_Management/) |
| **EX_12** | RESTful API for Train Management System with Spring Data JPA | [View PDF](./EX_12_RESTful_API_for_Train_Management/EX_12_RESTful_API_for_Train_Management.pdf) | [Folder](./EX_12_RESTful_API_for_Train_Management/) |
| **EX_13** | RESTful API for Railway Ticket Reservation System with Spring Data JPA | [View PDF](./EX_13_RESTful_API_for_Railway_Ticket_Reservation/EX_13_RESTful_API_for_Railway_Ticket_Reservation.pdf) | [Folder](./EX_13_RESTful_API_for_Railway_Ticket_Reservation/) |
| **EX_14** | RESTful API for Guesstimate Records Management with Spring Data JPA | [View PDF](./EX_14_RESTful_API_for_Guesstimate_Records/EX_14_RESTful_API_for_Guesstimate_Records.pdf) | [Folder](./EX_14_RESTful_API_for_Guesstimate_Records/) |
| **EX_15** | RESTful API for Movie Catalog Management with Sorting and JPA | [View PDF](./EX_15_RESTful_API_for_Movie_Catalog_with_Sorting/EX_15_RESTful_API_for_Movie_Catalog_with_Sorting.pdf) | [Folder](./EX_15_RESTful_API_for_Movie_Catalog_with_Sorting/) |
| **EX_16** | Telecom SIM Card Activation and Management Service | [View PDF](./EX_16_Telecom_SIM_Card_Activation_and_Management/EX_16_Telecom_SIM_Card_Activation_and_Management.pdf) | [Folder](./EX_16_Telecom_SIM_Card_Activation_and_Management/) |

Master Manual: **[NM_SEM7_Complete_Lab_Manual.pdf](./NM_SEM7_Complete_Lab_Manual.pdf)** (contains all 16 experiments with embedded bookmarks).

## 6. How to Use the PDFs
Every experiment document in this manual follows a uniform, academic practical-record structure designed for clarity and easy study:
1. **Experiment Number and Title:** Prominently placed at the top of each document.
2. **Problem Statement:** Concise explanation of the experiment objectives and functionality.
3. **Software Requirements:** Exactly five software tools and dependencies required.
4. **Algorithm:** Exactly 10 numbered, two-line execution steps reflecting actual program logic.
5. **Procedure:** Maximum five practical steps for creating, configuring, and verifying the application.
6. **Program:** Complete, runnable Java source code with print-friendly syntax highlighting.
7. **Output:** Expected REST API responses, HTTP status codes, JSON bodies, or console outputs.
8. **Result:** Exactly two concise concluding lines verifying experiment completion.

The PDFs are formatted in standard A4 portrait layout with running headers and page numbers, optimized for printing or handwriting practical laboratory records.

## 7. Project Setup
To run any experiment from this manual:
1. Open [Spring Initializr](https://start.spring.io).
2. Configure project settings:
   - **Project:** Maven
   - **Language:** Java
   - **Spring Boot:** 3.x
   - **Java Version:** 17
   - **Packaging:** Jar
3. Select dependencies as listed in the experiment's Software Requirements section:
   - For Experiments 01 to 03: `Spring Web`
   - For Experiments 04 to 09, 11 to 16: `Spring Web`, `Spring Data JPA`, `H2 Database`
   - For Experiment 10: `Spring Web`, `Spring AOP`
4. For JPA experiments, add the following configuration to `src/main/resources/application.properties`:
   ```properties
   spring.datasource.url=jdbc:h2:mem:testdb
   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.show-sql=true
   ```
5. Copy the Java source code from the experiment PDF into `src/main/java/com/example/demo/DemoApplication.java`.
6. Execute the project using Maven or your IDE:
   ```bash
   mvn spring-boot:run
   ```
7. Verify endpoints using a browser or Postman as described in the Output section.

All original experiment implementations, algorithms, entity mappings, and endpoints have been faithfully preserved and enhanced with academic documentation.

## 8. Repository Structure
```
NM-SEM-7/
├── README.md
├── NM_SEM7_Complete_Lab_Manual.pdf
├── EX_01_Inversion_of_Control_and_Bean_Management/
│   └── EX_01_Inversion_of_Control_and_Bean_Management.pdf
├── EX_02_Basic_REST_Controller_and_Endpoints/
│   └── EX_02_Basic_REST_Controller_and_Endpoints.pdf
├── EX_03_Dependency_Injection_via_Constructor/
│   └── EX_03_Dependency_Injection_via_Constructor.pdf
├── EX_04_Pagination_and_Sorting_with_Spring_Data_JPA/
│   └── EX_04_Pagination_and_Sorting_with_Spring_Data_JPA.pdf
├── EX_05_Derived_Query_Methods_in_Spring_Data_JPA/
│   └── EX_05_Derived_Query_Methods_in_Spring_Data_JPA.pdf
├── EX_06_Updating_Records_in_Spring_Data_JPA/
│   └── EX_06_Updating_Records_in_Spring_Data_JPA.pdf
├── EX_07_Custom_Repository_Implementation_with_EntityManager/
│   └── EX_07_Custom_Repository_Implementation_with_EntityManager.pdf
├── EX_08_Complete_CRUD_Operations_with_Spring_Data_JPA/
│   └── EX_08_Complete_CRUD_Operations_with_Spring_Data_JPA.pdf
├── EX_09_Ticket_Booking_and_Cancellation_System/
│   └── EX_09_Ticket_Booking_and_Cancellation_System.pdf
├── EX_10_Aspect_Oriented_Programming_with_Spring_AOP/
│   └── EX_10_Aspect_Oriented_Programming_with_Spring_AOP.pdf
├── EX_11_RESTful_API_for_Coach_Management/
│   └── EX_11_RESTful_API_for_Coach_Management.pdf
├── EX_12_RESTful_API_for_Train_Management/
│   └── EX_12_RESTful_API_for_Train_Management.pdf
├── EX_13_RESTful_API_for_Railway_Ticket_Reservation/
│   └── EX_13_RESTful_API_for_Railway_Ticket_Reservation.pdf
├── EX_14_RESTful_API_for_Guesstimate_Records/
│   └── EX_14_RESTful_API_for_Guesstimate_Records.pdf
├── EX_15_RESTful_API_for_Movie_Catalog_with_Sorting/
│   └── EX_15_RESTful_API_for_Movie_Catalog_with_Sorting.pdf
└── EX_16_Telecom_SIM_Card_Activation_and_Management/
    └── EX_16_Telecom_SIM_Card_Activation_and_Management.pdf
```
