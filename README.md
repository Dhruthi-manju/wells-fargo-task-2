# Wells Fargo Software Engineering Virtual Experience Program – Task 2

## Overview

This project is part of the Wells Fargo Software Engineering Virtual Experience Program on Forage. The objective of this task was to implement a relational data model using Spring Boot and JPA based on the system requirements provided in Task 1.

## Technologies Used

* Java
* Spring Boot
* Jakarta Persistence (JPA)
* Maven
* Git & GitHub

## Data Model

The system is designed to manage financial advisors and their clients. The following entities were implemented:

### Advisor

Represents a financial advisor who manages multiple clients.

### Client

Represents a client associated with a financial advisor and linked to a portfolio.

### Portfolio

Represents a client's investment portfolio containing multiple securities.

### Security

Represents an investment asset within a portfolio, including details such as:

* Name
* Category
* Purchase Date
* Purchase Price
* Quantity

## Entity Relationships

* One Advisor → Many Clients
* One Client → One Portfolio
* One Portfolio → Many Securities

## Key Features

* JPA Entity Mapping using `@Entity`
* Auto-generated primary keys using `@GeneratedValue`
* Column mapping using `@Column`
* Relationship mapping using:

  * `@OneToMany`
  * `@ManyToOne`
  * `@OneToOne`
* Constructors, Getters, and Setters implemented for all entities

## Learning Outcomes

Through this task, I gained practical experience in:

* Designing and implementing ERD-based data models
* Mapping database relationships using JPA
* Working with Spring Boot entity classes
* Using Git and GitHub for version control
* Forking, cloning, committing, and pushing changes to a remote repository

## Author

Dhruthi Manju
