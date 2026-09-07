# INTERNSHIP REPORT
## C++ PROGRAMMING INTERNSHIP

<br>

**Submitted in partial fulfillment of the requirements for the evaluation of 3rd Semester Internship**

<br>

---

### **Submitted By:**
- **Name:** Shaurya Shivhare
- **Roll Number / Enrollment No.:** 25scs1003002884
- **Academic Batch:** 2025 – 2029
- **Semester & Section:** 3rd Semester — 2CSE14
- **Department:** Computer Science & Engineering
- **GitHub Profile:** [https://github.com/CodeWizard-1234](https://github.com/CodeWizard-1234)

---

### **Host Organization:**
- **Company:** Thiranex (Skill Development & Future Tech)
- **Website:** [www.thiranex.in](https://www.thiranex.in)
- **Role:** Intern – C++ Programming
- **Internship ID:** THX-AUG1726-265
- **Duration:** 17 August 2026 – 16 September 2026
- **Mode:** Remote / Project-Based

---

<div style="page-break-after: always;"></div>

# 📜 CANDIDATE DECLARATION

I, **Shaurya Shivhare**, Roll No. **25scs1003002884**, student of B.Tech Computer Science & Engineering (Batch 2025–2029, 3rd Semester, Section 2CSE14), hereby declare that the internship report entitled **"C++ Programming Internship at Thiranex"** is an authentic record of my own work carried out during the period from **17 August 2026 to 16 September 2026** under the mentorship of **Thiranex**.

The projects and documentation presented in this report represent my original work and have not been submitted elsewhere for the award of any other degree or diploma.

<br><br>

**Date:** 16 September 2026  
**Place:** Greater Noida / Remote  

<br>

_________________________  
**Shaurya Shivhare**  
Roll No: 25scs1003002884  
B.Tech CSE (2025–2029)  

---

<div style="page-break-after: always;"></div>

# 🙏 ACKNOWLEDGEMENT

I would like to express my sincere gratitude to **Thiranex** for providing me with the opportunity to undertake this **C++ Programming Internship**. The hands-on project-based curriculum, technical guidance, and structured roadmap provided an invaluable foundation in real-world software engineering.

I am deeply thankful to my academic faculty, mentors, and the Department of Computer Science & Engineering for their continuous support, encouragement, and academic facilitation during my 3rd semester.

Finally, I would like to thank my peers and family for their unwavering support throughout this learning journey.

<br>

**Shaurya Shivhare**  
Roll No: 25scs1003002884  

---

<div style="page-break-after: always;"></div>

# 📑 TABLE OF CONTENTS

1. **Executive Summary**
2. **Chapter 1: About the Organization & Internship Scope**
   - 1.1 About Thiranex
   - 1.2 Internship Objectives & Goals
   - 1.3 Scope of the Internship
   - 1.4 Timeline and Milestone Schedule
3. **Chapter 2: Technical Foundation & Core Concepts**
   - 2.1 C++ Language Standards & Architecture
   - 2.2 Object-Oriented Programming (OOP) Principles
   - 2.3 Standard Template Library (STL)
   - 2.4 File Streams & Offline Persistence (`fstream`)
   - 2.5 Memory Management & Pointer Mechanics
   - 2.6 Defensive Programming & Exception Handling
4. **Chapter 3: Detailed Project Implementations**
   - 3.1 Project 1: Student Record Management System (StudentVault)
   - 3.2 Project 2: Bank Management System
   - 3.3 Project 3: Library Management System
   - 3.4 Project 4: Tic-Tac-Toe Game Engine
5. **Chapter 4: Testing, Verification & Debugging**
   - 4.1 Testing Methodologies
   - 4.2 Boundary Value & Edge Case Scenarios
   - 4.3 Key Bugs Encountered & Technical Resolutions
6. **Chapter 5: Skills Developed & Professional Outcomes**
   - 5.1 Technical Competencies Acquired
   - 5.2 Software Engineering Best Practices
7. **Chapter 6: Conclusion & Future Scope**
8. **Appendix & Project Links**

---

<div style="page-break-after: always;"></div>

# 📌 EXECUTIVE SUMMARY

During the 4-week **C++ Programming Internship** at **Thiranex** (17 August 2026 – 16 September 2026), I designed, implemented, tested, and documented four progressive software applications in C++. 

The internship curriculum focused on bridging theoretical computer science fundamentals with practical software development practices. Key areas of focus included:
- Object-Oriented Analysis & Design (Encapsulation, Inheritance, Polymorphism, Abstraction)
- Memory allocation, pointer mechanics, references, and resource management
- Generic programming with the C++ Standard Template Library (STL: `vector`, `map`, `unordered_map`, algorithms)
- Persistent offline file storage using stream serialization (`ifstream`, `ofstream`, `fstream`)
- Defensive programming, boundary validation, and comprehensive edge-case testing
- Version control workflows using Git and GitHub

The four projects completed during the internship are:
1. **StudentVault** — Student Record Management System
2. **Bank Management System** — Multi-Account Transaction & Ledger Engine
3. **Library Management System** — Catalog, Circulation & Fine Tracking System
4. **Tic-Tac-Toe** — Turn-Based Game Engine with AI Bot & State Analysis

---

<div style="page-break-after: always;"></div>

# CHAPTER 1: ABOUT THE ORGANIZATION & INTERNSHIP SCOPE

### 1.1 About Thiranex
**Thiranex** is a future-tech skill development organization dedicated to bridging academia and industry requirements. Thiranex offers structured, project-centric internships across cutting-edge engineering domains, helping student engineers build industry-grade portfolios through hands-on development.

### 1.2 Internship Objectives
The primary objectives of the C++ Programming Internship were:
- To master C++ syntax, type safety, modular compilation, and modern standards.
- To design real-world software using Object-Oriented Design (OOD) and modular class hierarchies.
- To implement efficient data structures (vectors, hash maps, linked lists) for fast search and data manipulation.
- To engineer offline data persistence using file streams without third-party heavy database engines.
- To follow professional Git version control, branching, and repository documentation standards.

### 1.3 Timeline & Milestone Schedule

```text
Week 1: Fundamentals, Control Structures & Tic-Tac-Toe Game
└── Console I/O, Matrix Representations, Game Loop Architecture, Bot Algorithms

Week 2: OOP Principles, File I/O & StudentVault
└── Class Design, Encapsulation, File Stream Persistence, Student Record CRUD

Week 3: Data Relationships, Multi-Entity Systems & Library Management
└── Book Catalogs, Borrowing Transactions, Due-Date & Overdue Fine Logic

Week 4: Advanced Systems, Security & Bank Management System
└── Multi-Account Polymorphism, Transaction Statements, Defensive Validation
```

---

<div style="page-break-after: always;"></div>

# CHAPTER 2: TECHNICAL FOUNDATION & CORE CONCEPTS

### 2.1 Object-Oriented Programming (OOP) Architecture
The projects heavily utilize the four pillars of OOP:
- **Encapsulation:** Protecting class fields (`private`/`protected`) and exposing regulated access through getters, setters, and member functions.
- **Inheritance:** Establishing base classes (e.g., `Account` base class extended by `SavingsAccount` and `CurrentAccount`).
- **Polymorphism:** Utilizing virtual functions and dynamic dispatch for polymorphic execution of transactions and interest calculations.
- **Abstraction:** Hiding low-level file I/O operations and algorithm details behind clean public APIs.

### 2.2 Standard Template Library (STL)
- `std::vector`: Dynamic arrays for runtime data storage (e.g., lists of books, students, transactions).
- `std::map` / `std::unordered_map`: Key-value associative structures for $O(1)$ or $O(\log N)$ lookup by ID, Roll Number, or Account Number.
- `std::sort`, `std::find`, `std::transform`: STL algorithmic operations for fast sorting and searching.

### 2.3 File Stream Persistence (`<fstream>`)
To preserve state across application lifecycles, file streams were utilized:
- `std::ifstream`: For reading serialized records at startup.
- `std::ofstream`: For persisting updated records upon modifications.
- `std::stringstream`: For parsing delimited text records (CSV-style formatting).

---

<div style="page-break-after: always;"></div>

# CHAPTER 3: DETAILED PROJECT IMPLEMENTATIONS

---

## 3.1 Project 1: Student Record Management System — StudentVault

- **Repository:** [https://github.com/CodeWizard-1234/studentvault](https://github.com/CodeWizard-1234/studentvault)
- **Tech Stack:** `C++17`, `OOP`, `File I/O`, `STL`, `Data Structures`

### Overview
StudentVault is an academic administration application designed to maintain, query, and compute academic statistics for student cohorts. It eliminates manual record keeping by providing fast search, automated GPA computation, and disk persistence.

### Key Features & Modules
1. **Student Record Management:** Add new student profiles with personal, demographic, and course details.
2. **Academic Computation:** Automated grade point average (GPA) calculation based on credit hours and marks.
3. **Search & Filter Engine:** Query records by Roll Number, Enrollment ID, Branch, or Name.
4. **Persistent File Storage:** Reads and writes student data to persistent disk files (`students.dat` / `students.txt`).
5. **Update & Delete:** Safe record modification and soft/hard deletion with confirmation prompts.

```text
┌────────────────────────────────────────────────────────┐
│                      STUDENTVAULT                      │
├────────────────────────────────────────────────────────┤
│ [1] Add Student Record     [4] Calculate CGPA / Grades │
│ [2] Search Student By Roll [5] Update Student Info     │
│ [3] Display All Students   [6] Save & Exit             │
└────────────────────────────────────────────────────────┘
```

---

## 3.2 Project 2: Bank Management System

- **Repository:** [https://github.com/CodeWizard-1234/bank-management-system](https://github.com/CodeWizard-1234/bank-management-system)
- **Tech Stack:** `C++`, `OOP (Inheritance, Polymorphism)`, `File Streams`, `STL`

### Overview
A console-based financial system simulating core banking operations including account lifecycle management, deposits, withdrawals, fund transfers, and ledger history.

### Key Features & Modules
1. **Account Types:** Supports both Savings Accounts (with minimum balance & interest) and Current Accounts (with overdraft allowances).
2. **Transaction Engine:** Secure deposit and withdrawal operations with defensive balance checks to prevent negative balances.
3. **Inter-Account Transfers:** Real-time money transfer between accounts with atomic source-deduction and destination-credit.
4. **Audit Trail & Statements:** Logs every transaction with timestamps, transaction IDs, and balance snapshots.
5. **PIN Authentication:** Basic security layer verifying account ownership before executing debits.

---

## 3.3 Project 3: Library Management System

- **Repository:** [https://github.com/CodeWizard-1234/library-management-system-](https://github.com/CodeWizard-1234/library-management-system-)
- **Tech Stack:** `C++`, `OOP`, `STL`, `File I/O`, `Search Algorithms`

### Overview
An automated library circulation system designed to track book inventory, member borrowings, return dates, and overdue penalty calculations.

### Key Features & Modules
1. **Book Catalog:** Add, update, delete, and display books with ISBN, title, author, and available copy count.
2. **Circulation Management:** Issue books to students and process returns, automatically incrementing/decrementing available copies.
3. **Overdue Fine Engine:** Calculates late fees based on the number of days past the designated return date.
4. **Fast Search:** Search by Book ID, title substring, or author name.
5. **File Persistence:** Saves inventory and borrowing registries to persistent storage.

---

## 3.4 Project 4: Tic-Tac-Toe Game Engine

- **Repository:** [https://github.com/CodeWizard-1234/tic-tac-toe](https://github.com/CodeWizard-1234/tic-tac-toe)
- **Tech Stack:** `C++`, `Game Logic`, `Matrix Algorithms`, `CLI`

### Overview
An interactive, turn-based game engine implementing a dynamic 3x3 grid with win/draw condition evaluations, move validation, and an AI opponent mode.

### Key Features & Modules
1. **Game Modes:** Player vs Player (Local 2-player) and Player vs Computer (AI logic).
2. **Board State Evaluation:** Algorithmic verification of 8 winning combinations (3 rows, 3 columns, 2 diagonals) and full-grid draw state.
3. **Input Sanitization:** Validates user choices to prevent overwriting existing cells or entering out-of-bound coordinates.
4. **Score Tracker & Session State:** Keeps track of round victories, ties, and offers instant replay capability.

---

<div style="page-break-after: always;"></div>

# CHAPTER 4: TESTING, VERIFICATION & DEBUGGING

### 4.1 Testing Methodologies
Comprehensive verification was conducted on each project:
- **Unit Testing:** Testing individual member functions (e.g., GPA calculation formula, fine computation algorithm, board winning line detector).
- **Integration Testing:** Ensuring file reading/writing integrates seamlessly with class constructors and destructors.
- **Boundary Value Testing:** 
  - Zero and negative balance withdrawals in Bank Management.
  - Non-existent roll number searches in StudentVault.
  - Zero remaining copies during book issuance in Library Management.
  - Overwriting occupied slots in Tic-Tac-Toe.

### 4.2 Key Challenges & Technical Resolutions
| Challenge | Root Cause | Solution Implemented |
|---|---|---|
| Input stream infinite loop on non-numeric input | `std::cin` failed state when entering chars into integer variables | Implemented `cin.clear()` and `cin.ignore(numeric_limits<streamsize>::max(), '\n')` buffer flushing. |
| Incomplete text read with spaces | Standard `cin >> str` operator splits on whitespace | Replaced with `std::getline(std::cin, str)` for multi-word titles and names. |
| File data corruption on abnormal exit | Unflushed buffer streams | Implemented explicit file stream flushing and RAII file closing in destructors. |

---

<div style="page-break-after: always;"></div>

# CHAPTER 5: CONCLUSION & LEARNING OUTCOMES

### 5.1 Technical Outcomes
- Strengthened mastery of modern C++ programming and modular architecture.
- Gained hands-on experience in implementing robust data persistence without third-party dependencies.
- Learned defensive programming, error handling, and structured testing methodologies.
- Developed professional Git version control and GitHub documentation practices.

### 5.2 Academic Relevance
The skills, design patterns, and applications built during this internship provide a direct practical foundation for subsequent 3rd and 4th-semester subjects, including **Data Structures & Algorithms (DSA)**, **Object-Oriented Software Engineering (OOSE)**, and **Database Management Systems (DBMS)**.

---

# 🔗 APPENDIX: PROJECT REPOSITORY LINKS

| # | Project Name | GitHub Link |
|---|---|---|
| 01 | **StudentVault** | [https://github.com/CodeWizard-1234/studentvault](https://github.com/CodeWizard-1234/studentvault) |
| 02 | **Bank Management System** | [https://github.com/CodeWizard-1234/bank-management-system](https://github.com/CodeWizard-1234/bank-management-system) |
| 03 | **Library Management System** | [https://github.com/CodeWizard-1234/library-management-system-](https://github.com/CodeWizard-1234/library-management-system-) |
| 04 | **Tic-Tac-Toe Game** | [https://github.com/CodeWizard-1234/tic-tac-toe](https://github.com/CodeWizard-1234/tic-tac-toe) |

---

<p align="center">
  <b>Report Completed & Submitted</b><br>
  Shaurya Shivhare • 25scs1003002884 • 3rd Semester (2CSE14) • 2026
</p>
