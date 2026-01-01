ATM Management System
x86 Assembly Language (COAL Project)
1. Introduction

The ATM Management System is a console-based simulation of an Automated Teller Machine developed using x86 Assembly Language (MASM) and the Irvine32 library. This project was completed as part of the Computer Organization and Assembly Language (COAL) course at the National University of Computer and Emerging Sciences (FAST-NUCES).

The primary objective of this project is to demonstrate a practical understanding of low-level system programming concepts by implementing real-world banking operations at the assembly level.

2. System Features

Secure authentication using account number and PIN verification

Card locking mechanism after three incorrect PIN attempts

Support for multiple user accounts with independent balances

Balance inquiry displaying total and available balance

Cash withdrawal using predefined denominations

Deposit functionality with input validation

Fund transfer between accounts with self-transfer prevention

Automatic transaction receipt generation

Comprehensive error handling for invalid inputs and insufficient balance

3. Functional Modules

Login Module: Handles account verification and PIN authentication

Balance Inquiry Module: Displays account balances

Withdrawal Module: Processes cash withdrawal requests

Deposit Module: Handles deposit transactions

Transfer Module: Transfers funds between valid accounts

Receipt Module: Prints transaction details after each operation

Menu Control Module: Manages navigation and user interaction

4. Technical Implementation

Modular program structure using procedures (PROC / ENDP)

Use of arrays to manage account numbers, PINs, and balances

Indexed memory access for efficient data handling

Conditional branching and looping for menu and logic control

Register-based arithmetic and memory operations

Console input/output handled through the Irvine32 library

Clear separation of data, logic, and control flow segments

5. Technology Stack

Programming Language: x86 Assembly Language (MASM)

Library: Irvine32

Platform: Windows Console Application

Development Environment: Visual Studio with MASM support

6. How to Run

Install MASM and configure the Irvine32 library

Open the project in Visual Studio

Assemble and link the ATM.asm file

Execute the program in the console window

7. Learning Outcomes

Strong understanding of computer organization and architecture

Practical experience with low-level memory and register management

Improved skills in assembly-level debugging and logic design

Exposure to real-world system modeling using assembly language

8. Author

Syed Muzammil
Cybersecurity Undergraduate
National University of Computer and Emerging Sciences (FAST-NUCES)

9. Course Information

Course Title: Computer Organization and Assembly Language (COAL)
Institution: National University of Computer and Emerging Sciences (FAST-NUCES)
