<div align="center">
  <h1>🛍️ SecondHand E-Commerce API</h1>
  <p><i>A robust and scalable backend engine for second-hand marketplaces.</i></p>

  ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
  ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
  ![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)
  ![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white)
</div>

<br>

## 📖 Project Overview
> **SecondHand E-Commerce API** is a comprehensive backend service built to power a modern thrift store or second-hand marketplace. It serves as the core engine for processing transactions, managing a detailed product catalog, and handling user interactions. 

The architecture strictly separates business logic and data access layers, ensuring scalability, ease of maintenance, and high performance for e-commerce workflows.

---

## ✨ Key Features & Capabilities

### 🔐 User Authentication & Authorization
* **Role-Based Access Control:** Secure boundaries between standard user accounts and administrative privileges.
* **Identity Management:** Dedicated endpoints for robust user registration, secure login validation, and profile management.

### 📦 Advanced Catalog Management
* **Full CRUD Operations:** Complete lifecycle management for marketplace products.
* **Deep Categorization System:** 
  * **Categories & Brands:** Filter items by origin, brand specific FAQs, and general categories.
  * **Textile Properties:** Granular filtering by material traits, including physical dimensions (height, length) and textile specifications.
* **Targeted Search:** Dynamic querying capabilities for pinpointing specific inventory by brand or material.

### 🛒 Order Processing System
* **End-to-End Tracking:** Seamlessly captures transaction data, including timestamping and product mapping.
* **Dynamic Calculations:** Automated processing of item quantities and total cost aggregations.

### 💬 Customer Engagement 
* **Feedback Loop:** Integrated system allowing customers to leave numerical ratings, review headers, and detailed text commentaries tied directly to specific products.

---

## 🛠️ Technical Architecture

| Component | Technology / Implementation |
| :--- | :--- |
| **Core Language** | Java |
| **Framework** | Spring Boot |
| **Data Persistence**| Spring Data JPA / Hibernate |
| **Build Automation**| Gradle |
| **Architecture** | Service-Oriented (Controller ↔ Service ↔ Repository) |
