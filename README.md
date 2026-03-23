# 🐾 BrisaPets

A web application built with Mendix for managing pet care services, including pet registration, scheduling, and client management.

---

## 🚀 About the Project

**BrisaPets** is a web application designed to support pet care businesses (such as grooming and pet sitting) by simplifying daily operations.

The platform allows clients to register their pets and book services, while administrators can manage schedules, services, and customer data.

---

## ✨ Features

* 🐶 Pet registration
* 👤 Customer and pet association
* 📅 Service scheduling
* 🛁 Service management (name, price, duration)
* 🖼️ Pet image upload
* 📋 Appointment overview
* 🔐 Role-based access control

---

## 🧠 System Design

### Main Entities

* **Customer (Account)**
* **Pet**
* **Appointment**
* **Service**

### Relationships

* One customer can have multiple pets
* One pet can have multiple appointments
* Each appointment is linked to:

  * One pet
  * One service
  * One customer

---

## 🛠️ Technologies Used

* Mendix (Low-Code Platform)
* Domain Modeling
* Microflows
* Atlas UI

---

## ⚙️ How to Run the Project

1. Install Mendix Studio Pro
2. Open the project (.mpr file)
3. Click **Run Locally**

---

## 📂 Project Structure

* **Pages** → User interface
* **Domain Model** → Data structure
* **Microflows** → Application logic

---

## 🎯 Purpose

This project was developed to:

* Practice low-code development
* Improve data modeling skills
* Build complete applications using Mendix
* Create a professional portfolio project

---

## 👩‍💻 Author

Marcelle Silva Araujo

---

## 📌 Project Status

🚧 In progress
