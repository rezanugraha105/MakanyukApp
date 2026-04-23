<h1 align="center">🍽️ Makan Yuk</h1>

<p align="center">
  A full-stack web application for discovering, reviewing, and locating food destinations with interactive map visualization.
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#architecture-&-repositories">Repositories</a> •
  <a href="#installation-&-setup">Installation</a> •
  <a href="#author">Author</a>
</p>

---

## 📌 Overview
**Makan Yuk** is a comprehensive food review platform built to help users easily find restaurant locations and share their culinary experiences. Developed as an Undergraduate Thesis Project, this application features a custom-built RESTful API and a responsive user interface integrated with interactive maps.

> **Note:** This project is built using a decoupled architecture, separating the client-side (Frontend) and server-side (Backend) into different repositories.

---

## ✨ Features
* **Interactive Map Visualization:** Pinpoint restaurant locations precisely using Leaflet.js mapping integration.
* **Comprehensive Food Reviews:** Users can read, write, and explore detailed food and restaurant reviews (CRUD operations).
* **Responsive User Interface:** A seamless and intuitive experience across desktop and mobile devices built with pure HTML, CSS, and JavaScript.
* **Robust RESTful API:** Secure and fast backend logic engineered with Hapi.js and PostgreSQL.

---

## 🛠️ Tech Stack

### Frontend 
* **HTML5 & CSS3** - Core structure and styling.
* **Vanilla JavaScript (ES6+)** - Dynamic DOM manipulation and API integration.
* **Leaflet.js** - Open-source JavaScript library for mobile-friendly interactive maps.
* **Node.js** - For package management and local development environment.

### Backend 
* **Node.js** - JavaScript runtime environment.
* **Hapi.js** - Rich framework for building robust applications and services.
* **PostgreSQL** - Powerful, open-source object-relational database system.

---

## 🔗 Architecture & Repositories

This application is divided into two separate repositories. You can explore the source code for each part here:

| Component | Repository Link | Description |
| :--- | :--- | :--- |
| **Frontend** | [makanyuk-frontend](https://github.com/rezanugraha105/makanyuk-frontend) | Client-side application featuring Leaflet maps and UI. |
| **Backend** | [makanyuk-backend](https://github.com/rezanugraha105/makanyuk-backend) | Server-side application, REST API, and database config. |

---

## 🚀 Installation & Setup

To run this project locally, you will need to set up both the backend and frontend.

### 1. Backend Setup
First, clone and start the backend server so the frontend has an API to communicate with.
```bash
# Clone the backend repository
git clone [https://github.com/rezanugraha105/makanyuk-backend.git](https://github.com/rezanugraha105/makanyuk-backend.git)

# Navigate into the directory
cd makanyuk-backend

# Install dependencies
npm install

# Setup your PostgreSQL database and update the configuration/env files.

# Run the server
npm run start

**### 2. Frontend Setup**
# Clone the frontend repository
git clone [https://github.com/rezanugraha105/makanyuk-frontend.git](https://github.com/rezanugraha105/makanyuk-frontend.git)

# Navigate into the directory
cd makanyuk-frontend

# Install any development dependencies (if applicable)
npm install

# Run the development server or open the index.html file
npm run dev
