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

text

This README is structured, visually clean, and includes all the important details from your project report. You can directly copy and paste this into your GitHub repository as `README.md`.
make it little short and more professinal aklso tell me i want the add the images in the  folder and a wor ddocument containing the project report in teh project in git hub
Here's a concise and professional version of your README.md:

markdown
# 🧭 Smart Navigation System

A C++ console-based route planning application demonstrating core Data Structures & Algorithms concepts with graph-based navigation and urban traffic simulation.

## 👥 Team
- **M. Hunain Riasat** - FA24-BSE-083 *(Team Lead)*
- Zain Aftab - FA24-BSE-155
- Muhammad Shaheer - FA24-BSE-089  
- Muhammad Ahsan - FA24-BSE-071

**Course:** Data Structures & Algorithms Lab | **Semester:** 3rd | **Date:** December 2024

## 📊 Core Features
- **📍 Location & Road Management** - Add, view, delete, and search urban locations
- **🛣️ Dijkstra's Algorithm** - Shortest path calculation with O(V²) complexity
- **🚦 Traffic Simulation** - Three states: Normal, Heavy, Blocked
- **📊 Route History** - Linked list-based tracking system
- **💰 Cost Estimation** - Travel time and fuel cost calculation
- **🗺️ ASCII Map Display** - Visual route representation

## 🏗️ Technical Implementation
### Data Structures
- **Graph (Adjacency List)** - Road network representation
- **Arrays with Structures** - Fixed-capacity location storage
- **Singly Linked List** - Dynamic route history
- **Stack** - Manual route building (LIFO)

### Algorithms
- Dijkstra's Shortest Path - O(V²) time, O(V) space
- Linear Search - O(n) time
- Selection Sort - O(n²) time, O(1) space

## 🚀 Quick Start
1. **Clone repository:**
   ```bash
   git clone https://github.com/yourusername/smart-navigation-system.git
Open in CodeBlocks/VSCode

Compile and run main.cpp

Follow console menu for navigation

📁 Project Structure
text
smart-navigation-system/
├── src/
│   └── main.cpp              # Complete C++ implementation
├── docs/
│   ├── project-report.docx   # Detailed documentation
│   └── project-presentation.pdf
├── images/                   # Screenshots and diagrams
│   ├── menu.png
│   ├── route-output.png
│   └── map-display.png
├── README.md
└── LICENSE
📈 Sample Output
https://images/menu.png
https://images/route-output.png
https://images/map-display.png

🔮 Future Scope
A* Algorithm implementation

Priority queue optimization

File-based data persistence

GUI interface development

Real-time traffic integration

📚 Academic References
Weiss, M. A. - Data Structures and Algorithm Analysis in C++

Cormen et al. - Introduction to Algorithms

GeeksforGeeks - DSA Tutorials

CP Algorithms - Dijkstra's Algorithm Implementation

📞 Contact
M. Hunain Riasat - hunainriasat@gmail.com

Data Structures & Algorithms Lab Project | © 2024 All Rights Reserved
