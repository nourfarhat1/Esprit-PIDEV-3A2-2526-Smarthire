# SmartHire - Intelligent Recruitment Management System

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Topics & Keywords](#topics--keywords)
- [Tech Stack](#tech-stack)
- [Architecture & Module Integration](#architecture--module-integration)
- [Core Features](#core-features)
- [Project Structure](#project-structure)
- [Installation & Setup](#installation--setup)
- [Database Configuration](#database-configuration)
- [Running the Application](#running-the-application)
- [Dependencies](#dependencies)
- [Contributors](#contributors)

---

## 🎯 Project Overview

**SmartHire** is a comprehensive **recruitment management system** developed as a school project for Esprit's 3A2 class (2025-2026). The application provides an integrated platform combining a **desktop GUI (JavaFX)** and **backend services** to streamline the entire hiring process.

The system enables HR professionals and recruiters to manage job postings, candidate applications, interviews, and communications efficiently. It leverages modern technologies including **Google Calendar API integration**, **email/SMS notifications**, **document processing**, and **QR code generation** for seamless recruitment workflow automation.

---

## 📚 Topics & Keywords

### Primary Topics
- **Recruitment Management**
- **Human Resources (HR)**
- **Desktop Application**
- **Backend Services**
- **Process Automation**

### Keywords
- JavaFX GUI
- Java Desktop Application
- Google Calendar Integration
- Email & SMS Notifications
- Document Processing
- QR Code Generation
- Webcam Capture
- MySQL Database
- Google APIs
- Twilio Integration
- SendGrid Integration
- Interview Scheduling
- Candidate Management

---

## 🛠 Tech Stack

### **Backend & Core Framework**
- **Java 25** - Primary programming language
- **Maven** - Build and dependency management (pom.xml)

### **Desktop UI**
- **JavaFX 21.0.6** - Modern cross-platform GUI framework
  - `javafx-controls` - UI controls and components
  - `javafx-fxml` - XML-based UI markup
  - `javafx-swing` - Swing interoperability
- **FormsFX 11.6.0** - Advanced form builder for JavaFX

### **External APIs & Services**
- **Google Calendar API v3** - Interview scheduling and calendar management
- **Google API Client 2.0.0** - Google services integration
- **Google OAuth Client Jetty 1.34.1** - OAuth authentication
- **Twilio SDK 9.14.0** - SMS notifications
- **SendGrid Java 4.10.2** - Email notifications
- **Google Zxing 3.5.3** - QR code generation and recognition

### **Hardware & Multimedia**
- **Webcam Capture 0.3.12** - Candidate photo capture during interviews
- **Tika 2.9.1** - Document parsing and content extraction

### **Database & Connectivity**
- **MySQL Connector/J 8.3.0** - MySQL database driver
- **Oracle JDBC (ojdbc8) 19.3.0.0** - Oracle database support (optional)

### **HTTP & JSON Processing**
- **OkHttp3 4.12.0** - HTTP client for API calls
- **Apache HttpClient 4.5.13** - Alternative HTTP client
- **Gson 2.10.1** - JSON serialization/deserialization
- **JSON.org 20231013** - JSON parsing

### **Email**
- **Jakarta Mail 2.0.1** - JavaMail API for email handling

### **Testing**
- **JUnit 5 (Jupiter) 5.12.1** - Unit testing framework

---

## 🏗 Architecture & Module Integration

### **Application Architecture**
