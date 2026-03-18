# 🧠 Online Quiz System (Exam Portal)

A dynamic **Java Web Application** that conducts quizzes using **Session Tracking**, built with **JSP, Servlets, and HttpSession**.

---

## 🚀 Overview

This project simulates a **real-time exam portal** where:

* Students log in
* Questions are displayed one-by-one
* Answers are tracked using session
* Final result is calculated automatically

---

## ✨ Features

✅ Student Login System
✅ Dynamic Question Navigation (No multiple JSP files)
✅ Session-based Answer Tracking
✅ Score Calculation
✅ Final Result Page
✅ Clean & Simple UI

---

## 🛠️ Tech Stack

* ☕ Java (JDK 17+)
* 🌐 JSP (Java Server Pages)
* 🔄 Servlets
* 📦 HttpSession (Session Tracking)
* ⚙️ Maven
* 🐱 Apache Tomcat

---

## 📂 Project Structure

```id="hx1jpo"
QUIZ
│
├── pom.xml
│
└── src
   └── main
      ├── java
      │   └── com.quiz
      │       └── QuizServlet.java
      │
      └── webapp
          ├── login.jsp
          ├── quiz.jsp
          ├── result.jsp
          │
          └── WEB-INF
              └── web.xml
```

---

## ⚙️ How It Works

```id="cs3r9g"
Login Page
   ↓
QuizServlet initializes session
   ↓
Question displayed dynamically
   ↓
User submits answer
   ↓
Session stores score + progress
   ↓
Next question appears
   ↓
Final result calculated
```

---

## 🧩 Key Concepts Used

* 📌 HttpSession for tracking user progress
* 📌 Request Parameters for answers
* 📌 Dynamic Question Rendering
* 📌 Form Handling with Radio Buttons

---

## 📸 Screens

### 🔐 Login Page

Enter student name to start quiz

### ❓ Quiz Page

* One question at a time
* Multiple choice answers

### 🏁 Result Page

* Total score displayed
* Performance summary

---

## 📊 Example Questions

* What is Java?
* Which is not a programming language?
* What does JVM stand for?
* Which company developed Java?

---

## 🔥 Future Enhancements

🚀 Timer-based quiz
🚀 Negative marking
🚀 Admin panel for adding questions
🚀 Database integration (store results)
🚀 Leaderboard system

---

## 🧑‍💻 Author

**Anurag Singh**

---

## ⭐ Support

If you like this project, don’t forget to ⭐ the repository!

---
