# ATM Management System – x86 Assembly

This project is a console-based ATM simulation developed using **x86 Assembly Language (MASM)** with the **Irvine32** library. It was created as part of the **Computer Organization and Assembly Language (COAL)** course at FAST-NUCES. The system demonstrates low-level programming concepts by implementing core banking operations.

---

## Features

- Account number and PIN-based authentication  
- Card lock after three failed PIN attempts  
- Multi-user account handling with independent balances  
- Balance inquiry (total and available balance)  
- Cash withdrawal using fixed denominations  
- Deposit with input validation  
- Fund transfer between valid accounts  
- Transaction receipt generation  
- Error handling for invalid input and insufficient balance  

---

## Implementation Details

- Modular design using assembly procedures (PROC/ENDP)  
- Arrays for storing account numbers, PINs, and balances  
- Indexed memory access and register-based computation  
- Conditional branching and loop-based control flow  
- Console input/output handled via the Irvine32 library  

---

## Technology Stack

- **Language:** x86 Assembly (MASM)  
- **Library:** Irvine32  
- **Platform:** Windows (Console Application)  

---

## How to Run

1. Configure MASM and the Irvine32 library on your system  
2. Assemble and link `ATM.asm`  
3. Run the executable in a console window  

---

## Author

- **Syed Muzammil**  
- Cybersecurity Undergraduate, FAST-NUCES  
