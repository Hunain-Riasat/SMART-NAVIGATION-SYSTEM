# 🧭 Smart Navigation System – Console-Based Route Planning

A comprehensive **Data Structures & Algorithms (DSA)** project implementing a console-based navigation system in C++ with graph algorithms, shortest path finding, and urban route simulation.

---

## 👨‍💻 **Presented By:**
- **M. Hunain Riasat** — FA24-BSE-083  
- **Zain Aftab** — FA24-BSE-155  
- **Muhammad Shaheer** — FA24-BSE-089  
- **Muhammad Ahsan** — FA24-BSE-071  

**Course:** Data Structures & Algorithms Lab  
**Semester:** 3rd Semester  
**Date:** December 2024  

---

## 📋 Table of Contents
- [Abstract](#abstract)
- [Features](#-features)
- [Data Structures Used](#-data-structures-used)
- [Algorithms Implemented](#-algorithms-implemented)
- [System Architecture](#-system-architecture)
- [How to Run](#-how-to-run)
- [Project Structure](#-project-structure)
- [Sample Output](#-sample-output)
- [Future Enhancements](#-future-enhancements)
- [References](#-references)
- [Contact](#-contact)

---

## 📌 Abstract
The **Smart Navigation System** is a console-based application developed in C++ that provides route planning and navigation services for urban areas. The system implements multiple data structures including arrays, linked lists, stacks, and graphs, along with algorithms such as **Dijkstra's shortest path**, linear search, and selection sort. The application manages locations, roads, traffic conditions, and provides features like route history tracking, cost estimation, and visual map representation.

**Keywords:** Navigation System, Dijkstra Algorithm, Graph Data Structure, Route Planning, C++ Programming

---

## 🚀 Features
- ✅ **Location Management** (Add, View, Delete, Search)
- ✅ **Road Management** with traffic simulation (Normal, Heavy, Blocked)
- ✅ **Shortest Path Calculation** using Dijkstra’s Algorithm
- ✅ **Manual Route Builder** using Stack
- ✅ **Route History Tracking** using Linked List
- ✅ **Travel Cost & Time Estimation**
- ✅ **ASCII-based Visual Map Display**
- ✅ **Input Validation & Memory Management**

---

## 🏗️ Data Structures Used
- **Arrays with Structures** – Store locations with fixed capacity
- **Graph (Adjacency List)** – Represents road networks
- **Stack** – For manual route building (LIFO)
- **Singly Linked List** – Dynamic storage of route history

---

## ⚙️ Algorithms Implemented
- **Dijkstra's Shortest Path** – `O(V²)` time, `O(V)` space
- **Linear Search** – `O(n)` time
- **Selection Sort** – `O(n²)` time, `O(1)` space

---

## 🧩 System Architecture
Main Menu
↓
Location Management → Road Management
↓ ↓
Location Array Graph (Adjacency List)
↘ ↙
Route Calculator (Dijkstra)
↓
Route History (Linked List)

text

**Tech Stack:**  
- **Language:** C++ (C++11 Standard)  
- **Compiler:** GNU GCC (MinGW)  
- **IDE:** CodeBlocks  
- **Libraries:** iostream, vector, algorithm, iomanip  
- **Platform:** Windows Console  

---

## 🖥️ How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/smart-navigation-system.git
Open in CodeBlocks or any C++ IDE

Compile and run the main.cpp file

Follow the console menu for navigation

📂 Project Structure
text
Smart_Navigation_System/
├── main.cpp                 # Complete source code
├── README.md                # Project documentation
├── media/                   # Screenshots and output images
└── Smart_Navigation_System_Project_Report.pdf
⚠️ Note: The entire project is implemented in a single C++ file (main.cpp) with modular functions for clarity and maintainability.

📸 Sample Output
https://media/image1.png
https://media/image2.png
https://media/image3.png

🔮 Future Enhancements
Implementation of A Algorithm*

Priority Queue Optimization for Dijkstra

File Handling for data persistence

GUI-based Interface

Real-time Traffic Simulation

📚 References
Mark Allen Weiss – Data Structures and Algorithm Analysis in C++

Cormen et al. – Introduction to Algorithms

GeeksforGeeks – DSA Tutorials

CP Algorithms – Dijkstra's Algorithm

📞 Contact
For queries or collaboration, feel free to reach out:

M. Hunain Riasat – hunainriasat@gmail.com

Zain Aftab – zain.aftab@example.com

Muhammad Shaheer – shaheer@example.com

Muhammad Ahsan – ahsan@example.com

Submitted for Data Structures & Algorithms Lab
© 2025 – All Rights Reserved
