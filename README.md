# CSE360_HW4_AnayShirolkar

This repository contains the implementation for Homework 4 of CSE360 by Anay Shirolkar. The project builds upon previous assignments, introducing advanced features like role-based access, reviews, messaging, trusted reviewers, and a discussion board system.

---

## 🌟 Features

- 🔐 User Authentication & Role Management
  - Student, Instructor, and Reviewer roles
  - Admin setup with invitation codes
- 💬 Discussion Forum
  - Students can post questions
  - Threaded replies to questions and answers
- ⭐ Review System
  - Users can review content (questions or answers)
  - Reviewer requests and approval system
- ✅ Trusted Reviewers
  - Students can mark reviewers as trusted
  - Trusted reviews appear with priority
- 📩 Messaging
  - Users can send messages to other users
- ⚙️ Admin Tools
  - Suspend user accounts
  - Reset user passwords

---

## 🛠 Technologies Used

- Java 17+
- JavaFX
- H2 SQL Embedded Database
- JDBC (Java Database Connectivity)

---

## 📁 Project Structure

- `/FoundationCode`
  - `User.java` – User model class
  - `StartCSE360.java`, `FirstPage.java`, `AdminSetupPage.java` – JavaFX Application Pages
- `/databasePart1`
  - `DatabaseHelper.java` – All SQL logic and schema migration
- `/HW2`
  - `Review.java`, `Question.java`, `Answer.java`, `Message.java` – Supporting data models

---

## 🔧 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/anayshirolkar/CSE360_HW4_AnayShirolkar.git
