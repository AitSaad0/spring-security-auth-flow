# Spring Security Auth Flow — Practice Project #

## This project is a step-by-step implementation of manual authentication with Spring Boot and Spring Security, using:

### Custom User entity

### Custom password encoding

### Authentication flow from scratch

### JWT generation & validation (without external tutorials)

### Postman testing at every stage

### The goal is to understand exactly how Spring Security works internally by implementing each part manually.

# 🚀 Project Objectives
## ✔️ Implement authentication from scratch

Custom /register endpoint

Custom /login endpoint

Manual password hashing

Manual JWT creation using jjwt

Custom authentication filter

## ✔️ Understand the entire workflow

Username/password → AuthenticationManager

UserDetailsService

PasswordEncoder

JwtService

SecurityFilterChain

Request filtering

Role-based access

## ✔️ Practice with Postman

At every step:

test input

expected response

failure cases

## 🧱 Tech Stack

Spring Boot 3.5

Spring Security

JPA / Hibernate

H2 Database (in-memory for testing)

JWT (jjwt)

Lombok

Spring Validation

Postman (for testing)