# 🔐 Authentication & Verification System

Hi there 👋

This is a secure backend application built using **Spring Boot** that
handles user authentication with **JWT** and **email OTP verification**.

The goal of this project is to simulate how real-world applications
manage **secure login systems**, **user verification**, and **stateless
authentication**.

------------------------------------------------------------------------

## ✨ Features

-   🔑 User Registration with Email Verification (OTP)
-   🔐 Secure Login using JWT Authentication
-   📩 Email Service Integration (SMTP - Gmail)
-   ⏳ OTP Expiry Handling (15 minutes)
-   🔁 Resend Verification Code
-   🛡️ Protected APIs using JWT Token
-   ⚡ Stateless Authentication (Spring Security)

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   ☕ Java\
-   🌱 Spring Boot\
-   🔐 Spring Security\
-   🗄️ PostgreSQL (Supabase)\
-   📧 Java Mail Sender\
-   🔑 JWT (JSON Web Token)\
-   🧪 Postman (API Testing)

------------------------------------------------------------------------

## 🔄 How It Works

1.  📝 User signs up with email & password\
2.  📩 System sends OTP to email\
3.  ✅ User verifies account using OTP\
4.  🔐 User logs in → receives JWT token\
5.  🚀 Token is used to access secured APIs

------------------------------------------------------------------------

## 🚀 API Endpoints

### 🔓 Public APIs

-   `POST /auth/signup` → Register user\
-   `POST /auth/login` → Login & get JWT\
-   `POST /auth/verify` → Verify OTP\
-   `POST /auth/resend` → Resend OTP

------------------------------------------------------------------------

## ▶️ Getting Started

1.  Clone the repository\
    git clone https://github.com/your-username/your-repo-name.git

2.  Configure database (PostgreSQL / Supabase)

3.  Add email credentials in `application.properties`

4.  Run the application\
    ./mvnw spring-boot:run

5.  Test APIs using Postman 🚀

------------------------------------------------------------------------

## 💡 Why This Project?

This project demonstrates:

-   Real-world authentication flow\
-   Secure API design\
-   JWT implementation\
-   Email verification system

It's a strong backend project to showcase **Spring Security + JWT
skills**.

------------------------------------------------------------------------

## ❤️ Final Note

Built with the intention to learn and implement **production-level
authentication concepts** in a simple and clean way.
