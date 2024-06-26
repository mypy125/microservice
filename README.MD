# Taco Cloud Restaurant Project (Microservices Architecture)

## Project Description

**Taco Cloud Restaurant** is a web application for ordering food. Users can browse the menu, select dishes, place orders, and pay online. Administrators can manage the menu, add new dishes, manage orders, and handle user accounts.

**Location:** Yerevan  
**Date:** 04/2024

**Developer:**  
Web Development in Java  
**Name:** Gagikovich Gor Mkhitaryan

**Project URL:** [https://github.com/mypy125/Taco-Cloud-service](https://github.com/mypy125/Taco-Cloud-service)

## Inspiration

I researched and analyzed many trending products relevant to our market. I decided to create an application that helps people order food without leaving their homes. The name "Taco Cloud" was inspired by Craig Walls' book "Spring in Action," where the examples involved creating a taco-cloud. Initially, the book helped me, but then I added more functionality, more services, and evolved it into what it is now, dividing it into microservices.

## Technology Stack

- **Spring Boot** for application setup and configuration
- **Spring Web** and **Spring WebFlux** for web component development
- **PostgreSQL** for the database
- **Spring Data JPA** for database interaction
- **Hibernate** as ORM (Object-Relational Mapping)
- **Spring Security** for ensuring security
- **JJWT Library** for token encryption 
- **Spring Cloud** for microservices infrastructure
- **Spring AOP** for aspect-oriented programming
- **Eureka Server** for service discovery

## Application Benefits

- Convenient and easy online food ordering
- Wide selection of restaurants and dishes
- Secure transactions and user data processing
- Flexible microservices architecture for scalability and development

## Functional Features

- Search for restaurants and dishes
- View menu and place orders
- Payment and order management
- User authentication and security
- Account and favorites management

## Microservices and Entities

The application is divided into microservices, each with its own database containing only the necessary tables for its operation. This ensures a more modular and scalable architecture.

### Authentication and User Management

- **Entities:** User, Role, ContactInformation
- **Description:** Manages user authentication and profiles.
- **Technologies:** Spring Boot, Spring Security, Spring Data JPA, Hibernate, Spring Cloud

### Location and Categories

- **Entities:** Address, Category
- **Description:** Handles location information and food categories.
- **Technologies:** Spring Boot, Spring Data JPA, Hibernate, Spring Cloud

### Products and Ingredients

- **Entities:** Food, IngredientCategory, IngredientItem
- **Description:** Manages the menu, food items, and their ingredients.
- **Technologies:** Spring Boot, Spring Web, Spring Data JPA, Hibernate, Spring Cloud

### Order Processing and Cart Management

- **Entities:** Cart, CartItem, Order, OrderItem
- **Description:** Handles order placement, cart management, and order tracking.
- **Technologies:** Spring Boot, Spring Web, Spring Data JPA, Hibernate, Spring Cloud, Spring AOP

### Restaurant Management

- **Entities:** Restaurant
- **Description:** Manages restaurant information and operations.
- **Technologies:** Spring Boot, Spring Data JPA, Hibernate, Spring Cloud

### Service Discovery

- **Description:** Provides service discovery for all microservices.
- **Technologies:** Eureka Server, Spring Cloud

In the future, each microservice will be enhanced and expanded as needed, ensuring the application remains modular and scalable.
