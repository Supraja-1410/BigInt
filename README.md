# 🔢 1024-bit Big Integer Arithmetic Program

This project implements a **1024-bit Big Integer Arithmetic Library** in **C**, enabling precise and safe handling of extremely large numbers. It supports arithmetic operations (addition, subtraction, multiplication, division) using custom data structures and optimized algorithms.

---

## 📚 Features
- **Custom BigInt Type**: Represents big integers (up to 309 decimal digits) with dynamic memory allocation.
- **High-Precision Arithmetic**:
  - **Addition & Subtraction**: Digit-wise calculation with sign management.
  - **Multiplication**: Classical and optimized **Karatsuba** method for large numbers.
  - **Division**: Long division algorithm with robust error checking.
- **Error Handling**:
  - Overflow checks for operations exceeding 1024 bits.
  - Graceful handling of division by zero.
  - Validates user input to ensure correct number formats.
- **Dynamic Memory Management**: Allocates and frees memory efficiently, ensuring program stability.
- **Interactive Console Interface**: Provides a menu-driven interface for users to input large numbers and select operations.

---

## 🛠 Technologies Used
- **C Language**
- **Structures, Arrays, Strings**
- **Dynamic Memory Allocation**
- **Karatsuba Multiplication Algorithm**

---

## 📂 Project Structure

## Example
Operations:
1 : Addition
2 : Subtraction
3 : Multiplication
4 : Division
5 : Exit
Enter your option: 1
Enter first number: +12345678901234567890
Enter second number: -9876543210987654321
Sum of two numbers is: +2469135690246913569
