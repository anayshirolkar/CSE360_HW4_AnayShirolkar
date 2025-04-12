CSE360_HW4_AnayShirolkar
This repository contains the implementation for Homework 4 of CSE360 by Anay Shirolkar. The project builds on previous homework submissions, adding enhanced functionality such as staff roles, review systems, messaging features, trusted reviewers, and question-answer discussion threads.

🌟 Features

User Authentication & Role Management

Student and Instructor roles

Reviewer role with approval workflow

Discussion System

Students can ask questions

Users can reply to questions and answers

Review System

Review content and rate it

Request to become a reviewer

Trusted Reviewer System

Students can add trusted reviewers

Reviews from trusted reviewers are prioritized

Messaging

Users can send and receive messages

Admin Tools

Suspend user accounts

Reset passwords

Database

Uses H2 SQL database

Handles migrations, table creation, and persistence

📁 Project Structure

/FoundationCode

User.java — user model with attributes and methods

AdminSetupPage.java, FirstPage.java — JavaFX application UI

/databasePart1

DatabaseHelper.java — handles all database operations

/HW2

Review.java, Message.java, Question.java, Answer.java, etc. — models used in the system

README.md

🔧 How to Run

Clone the repository: git clone https://github.com/anayshirolkar/CSE360_HW4_AnayShirolkar.git

Open in an IDE (e.g. IntelliJ or Eclipse)

Ensure JavaFX is set up and linked

Run StartCSE360.java

🛠 Requirements

Java 17+

JavaFX SDK

H2 Database (embedded)

📦 Dependencies

java.sql.*

javafx.base

javafx.controls

javafx.fxml

java.util.*

📌 Notes

Invitation codes are required to register new users

Reviewer role is only granted after instructor approval

Trusted reviewers can be prioritized per user
