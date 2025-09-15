# 💇‍♀️ Blsmy API Documentation

This repository contains the documentation for the **Blsmy API**, which provides various endpoints for managing user authentication, salon information, user profiles, bookings, and addresses.  
The API is designed to be a comprehensive solution for applications requiring salon management and user interaction.

---

## 🌐 Live API Documentation
👉 [**Click here**](https://abdelrhman-arfat.github.io/blsmy-docs/) to access the interactive API documentation.

---

## 📌 API Endpoints

### 🔑 Authentication
- `POST /user/register`: Register a new user account.  
- `POST /user/login`: Log in to an existing user account.

### 💇‍♂️ Salons
- `GET /salons`: Retrieve a list of all salons.  
- `GET /salons/services`: Get all services offered by salons.  
- `GET /salons/doctors`: Retrieve a list of all doctors associated with salons.  
- `GET /salons/categories`: Get all salon categories.

### 🏠 Salon Addresses
- `GET /salons/addresses`: Retrieve addresses for salons.

### 📋 Specific Salon Details
- `GET /salons/{id}/staff`: Get staff details for a specific salon.  
- `GET /salons/{id}/services`: Get services offered by a specific salon.  
- `GET /salons/{id}`: Get data for a specific salon.  

### 👤 User Profile
- `GET /user/profile`: Retrieve the authenticated user's profile information.  
- `POST /user/update`: Update the authenticated user's profile information.

### 📅 User Bookings
- `GET /user/bookings`: Retrieve all bookings for the authenticated user.  
- `POST /user/bookings`: Create a new booking for the authenticated user.

### 🏡 User Addresses
- `GET /user/addresses`: Retrieve all addresses associated with the authenticated user.  
- `POST /user/addresses`: Add a new address for the authenticated user.

### 💌 Messages
- `POST /contact/submit`: Send a contact message.

---

## ⚙️ Technologies Used

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-original.svg" width="40" alt="Laravel"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="50" alt="PHP"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" width="50" alt="MySQL"/>
  <img src="https://img.shields.io/badge/API-RESTful-green?style=for-the-badge" alt="REST API"/>
  <img src="https://img.shields.io/badge/Auth-Sanctum-blue?style=for-the-badge" alt="Sanctum"/>
</p>

---
