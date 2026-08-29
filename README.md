# Personal Portfolio Website

A full-stack personal portfolio website built to showcase my skills, projects, and contact information.

## 🚀 Live Demo

Visit the live website: portfolio-production-d13f.up.railway.app

## 📌 Features

- Responsive personal portfolio website
- About Me section
- Skills section
- Contact form
- Contact messages stored in MySQL database
- Spring Boot backend integration
- Cloud database deployment
- Live deployment

## 🛠️ Technologies Used

### Frontend
- HTML
- CSS

### Backend
- Java
- Spring Boot
- Spring Data JPA

### Database
- MySQL
- Aiven Cloud Database

### Deployment
- Railway
- GitHub

## 🏗️ Project Architecture

User
↓
Portfolio Website
↓
Spring Boot Backend
↓
MySQL Database

## 📂 Project Structure

```text
portfolio
│
├── src/main/java/com/example/portfolio
│   ├── controller
│   │   └── ContactController.java
│   ├── model
│   │   └── Contact.java
│   ├── repository
│   │   └── ContactRepository.java
│   ├── HomeController.java
│   └── PortfolioApplication.java
│
├── src/main/resources
│   ├── templates
│   │   └── index.html
│   └── application.properties
│
├── Dockerfile
├── pom.xml
└── README.md
