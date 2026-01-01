ATM Management System (x86 Assembly – COAL Project)

The ATM Management System is a console-based simulation of a real-world ATM, developed using x86 Assembly Language (MASM) with the Irvine32 library. This project was completed as part of the Computer Organization & Assembly Language (COAL) course at FAST-NUCES.
The system focuses on low-level programming concepts, including memory management, register usage, procedure-based design, and conditional control flow, while implementing realistic banking operations.

- Features

Secure Login System
Account number verification
4-digit PIN authentication
Card lock after 3 incorrect PIN attempts
Multi-User Support
Separate accounts with individual balances
Secure session-based user handling
Core ATM Operations
Balance inquiry (total & available balance)
Cash withdrawal with fixed denominations
Deposit with input validation
Fund transfer between accounts (self-transfer restricted)
Transaction Receipts
Transaction type (Withdraw / Deposit / Transfer)
Amount
Source and destination accounts
Updated account balance
Robust Error Handling
Invalid menu selections
Insufficient balance
Incorrect credentials
Invalid transaction inputs

- Technical Implementation

Modular design using procedures (PROC / ENDP)
Efficient use of arrays for accounts, PINs, and balances
Indexed memory access and register-based computation
Conditional branching and looping for menu navigation
Console I/O via Irvine32 library
Clear separation of data, logic, and control flow

- Tech Stack

Language: x86 Assembly (MASM)
Library: Irvine32
Platform: Windows (Console Application)
Assembler: MASM (Microsoft Macro Assembler)

- Learning Outcomes

Strong understanding of low-level system design
Hands-on experience with registers, memory addressing, and stack usage
Improved debugging and logical problem-solving skills
Practical exposure to real-world system simulation at the assembly level

- How to Run

Install MASM and ensure Irvine32 is properly configured
Open the project in a supported IDE (Visual Studio recommended)
Assemble and link the .asm file
Run the executable in the console

- Author

Syed Muzammil
Cybersecurity Undergraduate | FAST-NUCES

- Course

Computer Organization & Assembly Language (COAL)
National University of Computer and Emerging Sciences (FAST-NUCES)
