# Task Management System – ASP.NET Core Web API

A Task Management System Web API built with ASP.NET Core 8, Entity Framework Core (Code First), and SQL Server.
The project implements JWT-based authentication and role-based authorization, following modern backend development best practices.

This application demonstrates a secure, scalable, and maintainable API architecture with clean separation of concerns.

# Features
Authentication & Authorization

User registration and login

JWT (JSON Web Token) based authentication

Role-based authorization (Admin, User)

Secure access to protected endpoints

# Role Management

Admin-only endpoints

Shared access for Admin & User roles

Public endpoints accessible without authentication

# Security

Password hashing

Stateless authentication

Token-based authorization using Bearer tokens

# API Endpoints

POST /api/Auth/register

POST /api/Auth/login

GET /api/Auth/admin-only

GET /api/Auth/user-admin-only

GET /api/Auth/public

POST /api/Auth/logout

POST /api/Auth/refresh

# Tech Stack

Backend: ASP.NET Core 8 Web API

ORM: Entity Framework Core (Code First)

Database: SQL Server

Authentication: JWT Bearer Tokens

API Documentation: Swagger / OpenAPI

# Project Structure

Controllers – Handle HTTP requests

Models – Entity definitions (User, Role, UserRole)

DTOs – Request/response data transfer objects

Services – JWT token generation

Data – Database context and configuration

# Setup Instructions

Clone the repository

Update the SQL Server connection string in appsettings.json

Run migrations:

Add-Migration InitialCreate
Update-Database


Run the project

Use Swagger UI to test the APIs

# Future Enhancements

Task CRUD operations

Persistent refresh tokens

BCrypt password hashing

Unit testing

Angular frontend integration

# Author

Muhammad Abubakar Latif
ASP.NET Developer | Backend Engineer
