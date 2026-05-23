# 📝 Quiz Management System

A console-based **Quiz Management System** built in **C++** using Object-Oriented Programming (OOP) concepts. Students can take subject-wise quizzes, view their results, and have scores saved automatically to a file.

---

## 📌 Features

- 🔐 **Login System** — Secure access with username and password
- 📚 **Multiple Subjects** — Choose from C++, Java, or HTML quizzes
- 🔀 **Randomized Questions** — Questions are asked in random order each time
- 📊 **Result Display** — Shows marks, percentage, and pass/fail status
- 💾 **Result Saving** — Automatically saves results to `result.txt`
- 🔁 **Continue Option** — Take multiple quizzes in one session

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **C++** | Core programming language |
| **OOP** | Classes, Inheritance, Polymorphism |
| **File Handling** | Saving results to .txt file |
| **Abstract Classes** | Base Quiz class with pure virtual function |
| **Windows.h / conio.h** | Console UI utilities |

---

## 🧱 OOP Concepts Used

| Concept | Where Used |
|---|---|
| **Encapsulation** | `Student` class with private members |
| **Abstraction** | Abstract `Quiz` base class |
| **Inheritance** | `CPPQuiz`, `JavaQuiz`, `HTMLQuiz` extend `Quiz` |
| **Polymorphism** | `AskQuestions()` overridden in each derived class |

---


## 💻 Usage

### Login Credentials
```
Username: User
Password: Password
```

### Steps
1. **Login** with credentials
2. Enter your **Name** and **Roll Number**
3. Select a **subject**:
   - `1` → C++ Quiz
   - `2` → Java Quiz
   - `3` → HTML Quiz
4. Answer **5 MCQ questions**
5. View your **result** on screen
6. Result automatically **saved to** `result.txt`
7. Press `Y` to take another quiz or any key to exit

---

## 📋 Quiz Subjects & Topics

| Subject | Topics Covered |
|---|---|
| **C++** | Operators, I/O, Comments |
| **Java** | Features, Modifiers, JVM/JDK/JRE, History |
| **HTML** | Tags, Headings, Web Standards |

---

## 📄 Sample Result Output (result.txt)

```
STUDENT NAME: Ali Hassan
ROLL NO: 101
SUBJECT: C++
MARKS: 4 OUT OF 5
PERCENTAGE: 80%
CONGRATS YOU HAVE PASSED
----------------------------------------


## 📄 License

This project is open source and available under the [MIT License](LICENSE).
