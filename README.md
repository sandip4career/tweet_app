# 🐦 Tweet App – Full-Stack Social Media Platform

A full-stack social media web application built with Python, Django, Bootstrap 5, and SQLite. The platform allows users to register, securely log in, publish tweets with optional image attachments, manage their posts with full CRUD capabilities, and explore content through a clean, responsive interface.

---

## 🚀 Features

* **User Authentication:** Secure user registration, login, logout, and session handling using Django's built-in authentication system.
* **Tweet Management:** Complete CRUD operations (Create, Read, Update, Delete) for posts.
* **Media Handling:** Image upload support with input validation and Django media storage configuration.
* **Access Control:** Restricted permissions ensuring users can only edit or delete their own posts.
* **Responsive UI:** Mobile-first layout styled with Bootstrap 5.
* **Database & ORM:** Relational data modeling and queries powered by SQLite and Django ORM.
* **Architecture:** Structured according to Django's Model-View-Template (MVT) pattern.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **Python** | Core programming language |
| **Django** | Backend web framework |
| **Bootstrap 5** | Responsive frontend UI framework |
| **HTML5 & CSS3** | Page structure and custom styling |
| **SQLite** | Development database |
| **Django ORM** | Object-Relational Mapping / Database operations |
| **Git & GitHub** | Version control and source code management |

---

## 🔄 Application Workflow

1. **Authentication:** Visitors register for an account or authenticate via login.
2. **Post Creation:** Logged-in users compose tweets and optionally attach images.
3. **Data Persistence:** Posts are validated and persisted to SQLite via Django models.
4. **Feed & Management:** Users view a feed of published tweets and can modify or delete only the posts they authored.
5. **Security Enforcement:** Protected views check authentication states and user
