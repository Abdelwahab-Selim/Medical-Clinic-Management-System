# Medical-Clinic-Management-System

A desktop-based Medical Clinic Management System developed using Java Swing and SQL Server.

## Overview

The system is designed to manage core clinic operations through a user-friendly desktop application. It provides functionality for managing patients, doctors, and other clinic-related operations.

The project was developed using Object-Oriented Programming principles and several software design patterns to improve code organization, maintainability, and scalability.

## Technologies

* Java
* Java Swing
* SQL Server
* JDBC
* NetBeans
* Object-Oriented Programming

## Design Patterns

The project demonstrates the use of several design patterns:

* Singleton– Used to manage shared database-related resources.
* Factory – Used for object creation.
* Builder – Used for constructing complex objects.
* Prototype – Used for object cloning.
* Adapter – Used to make incompatible interfaces work together.
* Proxy – Used to implement access control and restrict operations based on user roles.

## Main Features

* Patient management
* Doctor management
* Database integration
* User access control
* Role-based permissions
* Desktop graphical user interface
* SQL Server database management

## Architecture

The application follows an object-oriented structure where the user interface, business logic, and database operations are separated into appropriate components.

## Access Control

The system supports different user roles with different permissions.

For example:

Admin – Full access to the system.
* Receptionist– Access to permitted clinic operations.

Access control is implemented using the Proxy Design Pattern.

## Database

The application uses Microsoft SQL Server as its database and communicates with it through JDBC.

> Note: Database credentials and sensitive configuration values should not be included in the repository.

## Project Purpose

This project was developed to practice and demonstrate:

* Object-Oriented Programming
* Java application development
* Database integration
* SQL
* Software design patterns
* Access control
* GUI development
