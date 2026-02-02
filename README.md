# 📚 Smart Study Session Timer (Pomodoro-Lite)

A console-based productivity tool built in **Java** that implements a Pomodoro-style study timer to help users stay focused and productive during study sessions.

---

## 🎯 Overview

The **Smart Study Session Timer** helps users manage their study time by dividing work into focused study sessions followed by short breaks. This project demonstrates practical Java concepts such as multithreading, scheduling tasks, and console-based user interaction.

It is designed for students and beginners who want to learn Java while building a real-world productivity tool.

---

## ✨ Features

- Configurable study and break durations  
- Live countdown timer with visual progress indicator  
- Automatic transition between study and break sessions  
- Pause and resume functionality  
- Session tracking and summary statistics  
- Clean, menu-driven console interface  

---

## 🛠️ Technical Concepts Demonstrated

### Concurrency & Threading

- ScheduledExecutorService for timed tasks  
- Multiple thread coordination  
- Thread-safe state handling  
- Graceful shutdown of executor services  

### Design Principles

- Single Responsibility Principle  
- Encapsulation using inner classes  
- Proper resource and lifecycle management  

---

## 📋 Requirements

- Java 8 or higher  
- Any Java IDE (IntelliJ IDEA recommended)  
- No external libraries required  

---

## 🚀 Getting Started

### Installation

- Clone or download the repository  
- Open the project in a Java IDE  
- Place `SmartStudyTimer.java` inside the source folder  

### Running the Application

- Run the `main` method from your IDE  
- The application starts in the console  

---

## 📖 Usage

When the application starts, a menu is displayed with options to configure sessions, start or pause timers, view summaries, and exit the program.

---

## 🧭 Application Menu

1. Configure Session  
2. Start Session  
3. Pause Session  
4. Stop Session  
5. View Session Summary  
6. Exit  

---

## 💡 How It Works

- The user configures study and break durations  
- A scheduled executor manages countdown timing  
- The program switches automatically between study and break phases  
- Session data is recorded and displayed in summaries  
- The application runs until the user exits  

---

## 🏗️ Project Structure

SmartStudyTimer.java  
- main – Application entry point  
- run – Main application loop  
- configureSession – Session setup  
- startSession – Study session logic  
- startBreak – Break session logic  
- pauseSession – Pause functionality  
- stopSession – Stop functionality  
- displayProgress – Live timer output  
- displaySummary – Session statistics  
- shutdown – Resource cleanup  
- SessionRecord – Inner class for session data  

---

## 🎓 Learning Outcomes

This project helps in understanding:

- Java concurrency and scheduling  
- Thread coordination and synchronization  
- Timer-based application logic  
- Console UI design  
- State management in multi-threaded programs  

---

## 🛠️ Technologies Used

- Java  
- Console-based User Interface  
- Java Concurrency Utilities  

---

## 👤 Author

Aayush Panchal  

If you found this project helpful, consider giving it a ⭐ on GitHub.
