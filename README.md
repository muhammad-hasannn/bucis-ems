# BUCIS Event Management and Ticket Booking System

A simple console-based Event Management and Ticket Booking System developed in C++.
This project allows users to register customers, manage events, and perform ticket booking and cancellation with basic validation and file handling.

This project was developed as part of **Assignment 3 (Project Based Learning)** for the *Computer Programming* course (Spring 2025).

---

## Features

* Customer registration with CNIC validation
* Event creation and management
* Ticket booking and cancellation
* Payment status tracking (paid/unpaid)
* Search functionality (by CNIC and Event ID)
* Sorting of events
* File-based data storage

---

## Built With
 
- **Language:** C++
- **Concepts used:** Structs, file I/O (`fstream`), formatted output (`iomanip`), bubble sort, input validation
 
---

## Project Structure

```
bucis-ems/
│
├── pbl.cpp              # Main source code
├── customerData.txt     # Stores customer records
├── eventData.txt        # Stores event records
├── CP PBL.pdf           # pdf file with question and screenshots
└── README.md            
```

---

## How to Run the Project

### Prerequisites

* C++ compiler (e.g., g++, MinGW, or any IDE like CodeBlocks/Dev-C++)
* Basic terminal/command prompt

---

### Steps

1. Clone the repository:

```
git clone https://github.com/muhammad-hasannn/bucis-ems.git
```

2. Navigate to the project folder:

```
cd bucis-ems
```

3. Compile the code:

```
g++ pbl.cpp -o program
```

4. Run the program:

```
./program
```

---

## Important Notes

* The program is console-based and runs in a terminal.
* Event data is stored in `.txt` files using a simple delimiter (`|`).
* Ensure the `.txt` files are in the same directory as the source code.
* Maximum 10 events can be added
* All of the data resets after thevtermination of program.

---

## Context
 
This project was submitted as **Assignment 3 (Project Based Learning)** for the **Computer Programming** course, Spring 2025 semester at BUCIS. The full course repository including all assignments and labs is available at [cp_sp25](https://github.com/muhammad-hasannn/cp_sp25).
