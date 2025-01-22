# **Furniro E-Commerce Website**

Welcome to the **Furniro E-Commerce Website** project! This platform is a modern, headless e-commerce solution designed to provide users with a seamless shopping experience. Built using **Next.js** for the frontend and **Sanity CMS** for backend content management, Furniro integrates custom APIs for dynamic data retrieval and processing.

---

## **Table of Contents**
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Technical Architecture](#technical-architecture)
4. [Development Process](#development-process)
5. [Key Features](#key-features)
6. [Testing and Quality Assurance](#testing-and-quality-assurance)
7. [Performance Metrics](#performance-metrics)
8. [Conclusion](#conclusion)
9. [How to Run the Project](#how-to-run-the-project)
10. [License](#license)

---

## **1. Introduction**
This project was developed as part of the **Marketplace Builder Hackathon 2025**. The goal was to create a scalable, maintainable, and user-friendly e-commerce platform. This README provides an overview of the project's technical architecture, development process, and key features.

---

## **2. Project Overview**
Furniro is a feature-rich e-commerce platform that includes:
- Dynamic product listings.
- Shopping cart functionality.
- Secure checkout process.
- Responsive design for all devices.
- Content management powered by **Sanity CMS**.

---

## **3. Technical Architecture**
Furniro follows a **headless architecture**, separating the frontend and backend for improved scalability and flexibility.

### **Frontend**
- **Framework**: Next.js
- **Styling**: Tailwind CSS
- **State Management**: React Context API
- **Dynamic Routing**: Next.js API routes

### **Backend**
- **CMS**: Sanity CMS
- **APIs**: Custom-built APIs for product data, categories, and user interactions
- **Database**: Sanity CMS (NoSQL)

### **Tools and Libraries**
- **Testing**: React Testing Library, Postman, OWASP ZAP
- **Performance Optimization**: Lighthouse, TinyPNG
- **Deployment**: Vercel

---

## **4. Development Process**
The project was developed over seven days, with each day focusing on specific tasks:

### **Day 1: Project Setup and Planning**
- Initialized the Next.js project.
- Set up Sanity CMS for content management.
- Defined schemas for products, categories, and user data.
- Planned API integration.

### **Day 2: Schema Design and Data Modeling**
- Designed schemas for products, categories, and user data in Sanity CMS.
- Validated schema compatibility with API data structure.
- Prepared data migration scripts.

### **Day 3: API Integration and Data Migration**
- Reviewed API documentation and identified endpoints.
- Aligned the Sanity schema with API data.
- Migrated data using scripts and manual import.
- Integrated APIs into the Next.js frontend.

### **Day 4: Testing and Debugging**
- Verified API responses using Postman.
- Tested cart addition and checkout functionalities.
- Optimized images using TinyPNG.
- Conducted security assessments using OWASP ZAP.

### **Day 5: Backend Refinement and Performance Optimization**
- Minimized JavaScript execution time.
- Implemented caching strategies.
- Assessed performance via Lighthouse.

### **Day 6: Frontend Enhancements and User Experience**
- Added interactive elements and animations.
- Improved responsiveness across devices.

### **Day 7: Final Testing and Deployment**
- Conducted end-to-end testing.
- Deployed the website to Vercel.

---

## **5. Key Features**
- **Dynamic Product Listings**: Fetched and displayed using APIs.
- **Shopping Cart**: Allows users to add and manage products.
- **Checkout Functionality**: Secure and seamless payment processing.
- **Responsive Design**: Optimized for all devices.
- **Content Management**: Powered by Sanity CMS.

---

## **6. Testing and Quality Assurance**
- **Unit Testing**: React Testing Library.
- **API Testing**: Postman.
- **Security Testing**: OWASP ZAP.
- **Performance Testing**: Lighthouse.

---

## **7. Performance Metrics**
- **First Contentful Paint**: 1.6s
- **Largest Contentful Paint**: 2.5s
- **Speed Index**: 10.7s
- **Performance Score**: 65/100

---

## **8. Conclusion**
Furniro is a robust and scalable e-commerce platform that delivers a seamless shopping experience. By following best practices in API integration, data migration, and performance optimization, the project has achieved its goals and is ready for production deployment.

---

