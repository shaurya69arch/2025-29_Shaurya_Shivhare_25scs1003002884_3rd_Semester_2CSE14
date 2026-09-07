# Thiranex C++ Programming Internship

<p align="center">
  <img src="https://www.thiranex.in/assets/thiranex-free-internship-with-certificate-logo-BA0qRWA4.png" alt="Thiranex Internship" width="420">
</p>

<p align="center">
  <b>Internship Documentation & Project Portfolio</b><br>
  C++ Programming Internship at Thiranex
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Internship-Thiranex-173B63?style=for-the-badge" alt="Thiranex">
  <img src="https://img.shields.io/badge/Domain-C%2B%2B%20Programming-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++ Programming">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Completed">
</p>

---

## 📌 About This Repository

This repository contains the **academic documentation, source code repositories, and supporting deliverables** for the evaluation and submission of my **C++ Programming Internship at Thiranex**.

The internship followed an intensive, project-driven methodology involving four progressively structured software development projects in C++. The work encompassed core programming concepts, Object-Oriented Programming (OOP), Data Structures & Algorithms (DSA), file stream persistence (I/O), memory management, Standard Template Library (STL), modular design, testing, debugging, and Git/GitHub version control.

This repository serves as a **centralized portfolio record of my internship work, project repositories, and academic submission**.

---

## 👨‍💻 Intern Details

| Detail | Information |
|---|---|
| **Name** | Shaurya Shivhare |
| **Roll / Enrollment No.** | 25scs1003002884 |
| **Academic Batch** | 2025 – 2029 |
| **Semester & Section** | 3rd Semester — 2CSE14 |
| **Organization** | Thiranex |
| **Job Designation** | Intern – C++ Programming |
| **Domain** | C++ Programming / Software Development |
| **Internship Duration** | 17 August 2026 – 16 September 2026 |
| **Mode** | Remote / Project-Based |
| **Status** | Completed |
| **Internship ID** | THX-AUG1726-265 |
| **GitHub Profile** | [CodeWizard-1234](https://github.com/CodeWizard-1234) |

---

# 🚀 Projects Completed

## 1. 🗄️ Student Record Management System — StudentVault

A comprehensive student information management system designed in C++ for securely storing, managing, and querying student academic records, course details, grades, and personal profiles with persistent storage.

### Key Features
- Student profile creation, updating, and record deletion (CRUD)
- Roll number and enrollment indexing for rapid lookup
- Academic grade entry, GPA calculation, and transcript reporting
- Multi-criteria search and filter operations (by roll number, name, batch)
- Persistent file storage using C++ file streams (`fstream`)
- Robust input validation and boundary condition handling
- Clean modular Object-Oriented design

**Tech Stack:** `C++17` `Object-Oriented Programming (OOP)` `File I/O (fstream)` `STL Containers` `Data Structures` `Git` `GitHub`

**GitHub Repository:** [https://github.com/CodeWizard-1234/studentvault](https://github.com/CodeWizard-1234/studentvault)

---

## 2. 🏦 Bank Management System

A robust console-based banking application simulating real-world financial workflows, account management, fund transfers, and ledger history with transaction security.

### Key Features
- Account creation for multiple account types (Savings, Current)
- Cash deposit, withdrawal, and real-time balance inquiry
- Account-to-account direct fund transfers
- Account authentication and basic PIN security
- Complete transaction statement logging and audit trails
- Data persistence via structured file handling
- Defensive programming with validation for overdrafts and negative balances

**Tech Stack:** `C++` `OOP (Encapsulation, Inheritance, Polymorphism)` `File Streams` `STL (vectors, maps)` `Algorithms` `Git` `GitHub`

**GitHub Repository:** [https://github.com/CodeWizard-1234/bank-management-system](https://github.com/CodeWizard-1234/bank-management-system)

---

## 3. 📚 Library Management System

An automated library inventory and circulation system built to streamline book cataloging, member borrowing, return workflows, and late fee calculations.

### Key Features
- Complete book catalog management (Add, edit, remove, view books)
- Book issue and return operations with availability status tracking
- Student/member borrowing record management
- Overdue tracking and fine calculation logic
- Fast search by Book ID, title, and author
- Persistent data storage for inventory and transactions

**Tech Stack:** `C++` `Object-Oriented Design` `Standard Template Library (STL)` `File Handling` `Search Algorithms` `Git` `GitHub`

**GitHub Repository:** [https://github.com/CodeWizard-1234/library-management-system-](https://github.com/CodeWizard-1234/library-management-system-)

---

## 4. 🎮 Tic-Tac-Toe Game

An interactive, turn-based console game featuring dual-mode gameplay (Two Players & Player vs Computer AI) built with clean game-loop architecture and state validation.

### Key Features
- Interactive 3x3 game board rendering in the terminal
- Two-player local mode and Single-player vs Computer mode
- Real-time move validation and grid boundary checks
- Algorithmic win, loss, and draw condition detection
- Turn tracking, score keeper, and replay capability
- Clean and intuitive CLI user experience

**Tech Stack:** `C++` `Game Loop Logic` `Matrix Algorithms` `Control Flow` `Terminal UI` `Git` `GitHub`

**GitHub Repository:** [https://github.com/CodeWizard-1234/tic-tac-toe](https://github.com/CodeWizard-1234/tic-tac-toe)

---

# 🧩 Overall Technology Stack

### Programming Languages
`C++ (C++11 / C++14 / C++17 / C++20)` · `C`

### Core Concepts & Paradigms
`Object-Oriented Programming (OOP)` · `Data Structures & Algorithms (DSA)` · `Standard Template Library (STL)` · `File I/O & Serialization` · `Memory Management & Pointers` · `Exception Handling`

### STL Components
`std::vector` · `std::string` · `std::map` · `std::unordered_map` · `std::list` · `std::algorithm` · `std::fstream`

### Tools & Development Environment
`GCC / G++ / MinGW` · `Visual Studio Code` · `Git` · `GitHub`

---

# 🏗️ General Application Architecture

The C++ applications developed during the internship followed a structured, modular, and layered software design:

```text
                    ┌─────────────────────────────────┐
                    │      User / Console UI Layer     │
                    │   (CLI Menus, Prompts & Inputs) │
                    └────────────────┬────────────────┘
                                     │
                                     ▼
                    ┌─────────────────────────────────┐
                    │   Controller & Business Logic   │
                    │   (Validation, Rules & Ops)     │
                    └────────────────┬────────────────┘
                                     │
                                     ▼
                    ┌─────────────────────────────────┐
                    │    Domain Models & Entities     │
                    │ (Classes: Student, Account, etc)│
                    └────────────────┬────────────────┘
                                     │
                                     ▼
                    ┌─────────────────────────────────┐
                    │   Data Persistence / File I/O   │
                    │   (fstream: Text & Binary Files)│
                    └─────────────────────────────────┘
```

> Each project enforces separation of concerns: input validation and user interaction are handled in the presentation layer, while business logic and data persistence operate independently via clean class interfaces.

---

# 📂 Repository Structure

This repository is structured as an **internship documentation and deliverables hub**:

```text
2025-29_Shaurya_Shivhare_25scs1003002884_3rd_Semester_2CSE14/
│
├── README.md
│
├── Documentation/
│   ├── Internship_Report_Shaurya_Shivhare.pdf
│   └── Internship_Presentation_Shaurya_Shivhare.pptx
│
├── Certificates/
│   └── README.md
│
├── Offer_Letter/
│   └── Thiranex_OfferLetter_Shaurya_Shivhare_THX-AUG1726-265.pdf
│
└── Project_Repositories/
    └── Project_links.md
```

---

# 📑 Internship Deliverables

| Document | Description | Status |
|---|---|---|
| 📜 **Offer Letter** | Official Thiranex Internship Selection Letter (`THX-AUG1726-265`) | Available in `Offer_Letter/` |
| 🏆 **Completion Certificate** | Official Thiranex Internship Certificate | Pending (Will be updated upon issuance) |
| 📘 **Internship Report** | Comprehensive academic report on C++ projects and learnings | Available in `Documentation/` |
| 📊 **Internship Presentation** | Summary presentation slides for internship evaluation | Available in `Documentation/` |
| 📖 **README.md** | Complete repository documentation and project directory | Available |

---

# 🎯 Internship Objectives

- Master core and advanced C++ programming concepts and modern standards.
- Apply Object-Oriented Programming (OOP) principles — Encapsulation, Inheritance, Polymorphism, and Abstraction.
- Design modular, scalable, and maintainable software architectures.
- Implement efficient data structures and algorithms using the C++ Standard Template Library (STL).
- Build robust file handling mechanisms for offline data persistence.
- Implement defensive programming practices, input sanitization, and exception handling.
- Practice professional version control workflows with Git and GitHub.

---

# 📈 Project Progression

The internship projects progressively built upon technical complexity:

```text
Tic-Tac-Toe Game
        │
        ▼
Control Flow, Arrays, Game State & Logic
        │
        ▼
StudentVault (Student Record System)
        │
        ▼
OOP Models, File I/O, Search & Grade Computation
        │
        ▼
Library Management System
        │
        ▼
Multi-Entity Relationships, Inventory & Fine Logic
        │
        ▼
Bank Management System
        │
        ▼
Security, Authentication, Multi-Account Ledgers & Transactions
```

---

# 🧪 Testing & Verification

Each application was rigorously tested and verified across multiple test scenarios:

- **Boundary Condition Testing:** Testing maximum/minimum values for balances, roll numbers, and array indices.
- **Input Validation:** Ensuring non-numeric input handling for numeric prompts to prevent infinite loops.
- **Persistence Verification:** Verifying data integrity across program restarts (file reading/writing).
- **Edge Case Execution:** Testing zero balances, overdraft attempts, nonexistent search queries, and tie games in Tic-Tac-Toe.
- **Memory Safety:** Ensuring proper memory allocation, object lifetimes, and scope management.

---

# 📚 Skills Developed

- **C++ Programming:** Syntax, memory model, pointers, references, and modern standards.
- **OOP Architecture:** Class design, operator overloading, inheritance hierarchies, and polymorphism.
- **Data Persistence:** File stream operations (`ifstream`, `ofstream`, `fstream`), file parsing, and serialization.
- **Data Structures & STL:** Vector, map, list, iterators, and algorithms (`std::sort`, `std::find`).
- **Software Engineering:** Code modularity, clean code practices, and debugging techniques.
- **Version Control:** Git commits, branch management, repository structuring, and GitHub project management.

---

# 🔗 Project Repository Links

| # | Project Name | Tech Stack | GitHub Repository |
|---|---|---|---|
| 01 | **StudentVault** | C++, OOP, File I/O, STL | [Open Repository](https://github.com/CodeWizard-1234/studentvault) |
| 02 | **Bank Management System** | C++, OOP, File Streams, STL | [Open Repository](https://github.com/CodeWizard-1234/bank-management-system) |
| 03 | **Library Management System** | C++, OOP, Algorithms, File I/O | [Open Repository](https://github.com/CodeWizard-1234/library-management-system-) |
| 04 | **Tic-Tac-Toe Game** | C++, Algorithms, Matrix Logic | [Open Repository](https://github.com/CodeWizard-1234/tic-tac-toe) |

---

# 👨‍💻 Author

**Shaurya Shivhare**  
- **Roll Number:** 25scs1003002884  
- **Batch / Class:** 2025–2029 • 3rd Semester • 2CSE14  
- **Branch:** Computer Science & Engineering  
- **Internship:** Intern – C++ Programming at Thiranex  
- **GitHub:** [@CodeWizard-1234](https://github.com/CodeWizard-1234)  

---

## 📌 Disclaimer

This repository is maintained for **academic internship documentation, evaluation, and record submission**.

Source code, commit histories, and project implementation files are hosted in the individual GitHub project repositories linked above.

---

<p align="center">
  <b>Thiranex Internship Portfolio</b>
  <br><br>
  C++ Programming • Thiranex • 2026
</p>
