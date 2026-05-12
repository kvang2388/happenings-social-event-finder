Happenings – Social Event Finder

A full-stack social event finder application that allows users to create events, browse listings, and receive personalized recommendations based on user behavior and preferences.

Live System Overview

Happenings is a production-style web application built with a Java Spring Boot backend, MySQL database, and a JavaScript frontend. It demonstrates full-stack development, authentication, REST API design, and database-driven recommendation logic.

Key Features
Authentication System

Secure user registration and login
JWT-based session authentication
Password encryption using BCrypt

Event Management

Create, view, and manage events
Events stored in a relational database
Events include title, description, date/time, and category

Recommendation System

Category-based recommendation engine
Uses saved user events to personalize results
Fallback system for users with no history

Full-Stack Integration

REST APIs connect frontend and backend
Real-time data updates using fetch API
No mock or static data in production flow

System Architecture

Backend: Java Spring Boot (REST APIs)
Frontend: HTML, CSS, JavaScript
Database: MySQL (relational design)
ORM: Hibernate / JPA
Deployment: Render (Docker-based deployment)

Database Structure

Users (authentication and profile data)
Events (event details and ownership)
Categories (event classification)
Saved_Events (user preference tracking)

My Role

Full integration and testing lead
Built event and recommendation APIs
Ensured database integrity and relationships
Tested full user workflow end-to-end
Resolved API and null-handling issues in production flow

User Flow

Login → Browse Events → Create Event → Save Event → View Recommendations

Tech Stack

Java, Spring Boot, MySQL, Hibernate/JPA, REST APIs, JWT, BCrypt, HTML, CSS, JavaScript, Git, Render

Screenshots (Add These)

Add images in /docs/screenshots/:

Login page
Event creation page
Event feed
Recommendations page
Project Purpose

This project demonstrates real-world full-stack development skills including backend API design, frontend integration, database modeling, authentication systems, and production deployment.
