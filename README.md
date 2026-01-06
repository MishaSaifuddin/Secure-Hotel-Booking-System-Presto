# -Secure-Hotel-Booking-System-Presto-
cryptographic password hashing (SHA-256)

# 🔐 Secure Hotel Booking System (Presto)

A secure, user-friendly hotel booking web application that implements **cryptographic password hashing (SHA-256)** and follows **OWASP Secure Software Development Lifecycle (SSDLC)** principles.  
This project demonstrates practical application of **web security, cryptography, and secure system design** in a real-world booking platform.

---

## 📌 Project Overview

The **Presto Hotel Booking System** was developed to address common weaknesses in traditional hotel reservation platforms, including:
- Weak authentication mechanisms
- Poor user experience
- Inefficient administrative workflows
- Inadequate protection of sensitive user data

This system integrates **secure password hashing**, **input validation**, and **secure development practices** to ensure confidentiality, integrity, and reliability.

---

## 🎯 Objectives

- Design an **intuitive and user-friendly booking interface**
- Implement **secure authentication using SHA-256 hashing**
- Protect sensitive user data following **OWASP security guidelines**
- Apply **Secure SDLC** throughout planning, development, testing, and deployment
- Evaluate security effectiveness against industry-standard systems

---

## 🔒 Security Features

- **SHA-256 Password Hashing**
  - Prevents plaintext password storage
  - Ensures resistance to pre-image and collision attacks
- **reCAPTCHA Integration**
  - Protects against automated attacks and bots
- **Secure Authentication Workflow**
  - Hashed password verification during login
- **Input Validation**
  - Reduces risks of SQL Injection and XSS
- **OWASP Secure Coding Practices**
  - Applied during development and testing phases

---

## 🏗️ System Architecture & Workflow

1. **User Registration**
   - Account creation with hashed password storage (SHA-256)
2. **User Authentication**
   - Secure login with reCAPTCHA verification
3. **Booking Management**
   - Users can create and view bookings
4. **Admin Dashboard**
   - View, modify, and manage booking records
5. **Data Storage**
   - MySQL database for structured and reliable data management

---

## 🧪 Secure Software Development Lifecycle (SSDLC)

This project follows a **security-first SDLC approach**:

### 🔹 Planning
- Security requirements gathered alongside functional requirements
- Threats such as SQL Injection and XSS considered early

### 🔹 Development
- Secure-by-design principles
- OWASP secure coding standards
- Static code review during development

### 🔹 Build
- Secure compilation and environment validation

### 🔹 Testing
- Security testing integrated into development:
  - SAST
  - DAST
  - IAST
- Automated testing with continuous integration concepts

### 🔹 Monitoring
- Post-deployment monitoring and vulnerability scanning

---

## 📊 Results & Implementation

- Fully functional booking system with secure authentication
- Successful implementation of SHA-256 hashing for passwords
- Admin dashboard for real-time booking management
- Improved data security without degrading user experience

---

## 🔍 Comparative Security Analysis

| Platform | Security Approach |
|--------|------------------|
| Eatigo | SHA-1 hashing, email confirmation |
| AirAsia | OTP-based verification, social login |
| GSC | Two-Factor Authentication (OTP) |
| **Presto (This Project)** | **SHA-256 hashing + OWASP Secure SDLC** |

The project aligns with industry practices used by platforms like **Booking.com, Expedia, and Airbnb**.

---

## ⚠️ Limitations & Improvements

- SHA-256 is fast but not adaptive against brute-force attacks
- Future improvements:
  - Implement **bcrypt or Argon2**
  - Add **Multi-Factor Authentication (MFA)**
  - Continuous security monitoring
  - Regular penetration testing

---

## 🚀 Technologies Used

- **Backend:** PHP
- **Database:** MySQL
- **Security:** SHA-256, reCAPTCHA
- **Development Environment:** XAMPP
- **Standards:** OWASP Secure Coding Practices

---

## 📚 Key Learning Outcomes

- Practical implementation of cryptographic hashing
- Secure authentication system design
- OWASP-based secure web development
- Threat modeling and security testing
- Real-world application of cybersecurity principles

---

## 🧠 Why This Project Matters

This project demonstrates the ability to:
- Design **secure web applications**
- Apply **cryptography in production systems**
- Follow **industry security standards**
- Balance **security, performance, and usability**

It reflects skills expected in **Software Engineering, Cybersecurity, and Backend Development roles**.

---

## 📄 Academic Context

Developed as part of:
**Cryptography – Implementation of Hashing Function**  
Faculty of Computer Science & Information Technology  
Universiti Tun Hussein Onn Malaysia (UTHM)

---

## 👤 Author

**[Your Name]**  
Computer Science (Information Security)  
Interested in Secure Systems, Web Security & Digital Forensics  

📫 *Add your LinkedIn / Email here*
