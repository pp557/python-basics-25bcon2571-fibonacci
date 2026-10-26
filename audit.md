# README Claims Audit

## 1. Project Description

**Claim:** The program generates and displays the Fibonacci series for a user-specified number of terms.  
**Status:** Supported  
**Evidence:** The program takes `n` as input and uses a `for` loop to print the requested number of terms.

**Claim:** The program uses a `for` loop and variable updates to generate the sequence.  
**Status:** Supported  
**Evidence:** The code uses `for i in range(n):` and updates the variables using `a, b = b, a + b`.

## 2. Features

**Claim:** Takes the number of terms as input from the user.  
**Status:** Supported  
**Evidence:** `n = int(input("Enter the number of terms: "))`

**Claim:** Generates the Fibonacci series starting from 0 and 1.  
**Status:** Supported  
**Evidence:** The variables are initialized as `a = 0` and `b = 1`.

**Claim:** Uses a `for` loop to generate the requested number of terms.  
**Status:** Supported  
**Evidence:** `for i in range(n):` repeats the loop `n` times when `n` is a non-negative integer.

**Claim:** Displays the series on the screen.  
**Status:** Supported  
**Evidence:** `print(a, end=" ")` prints each term.

## 3. Requirements

**Claim:** Python 3.x is required.  
**Status:** Supported  
**Evidence:** The program uses Python syntax and built-in functions.

## 4. Usage

**Claim:** The program can be saved as `fibonacci.py` and run using `python fibonacci.py`.  
**Status:** Supported  
**Evidence:** The code is a Python script that can be run with Python installed, provided the filename and folder are correct.

**Claim:** The user enters the number of terms when prompted.  
**Status:** Supported  
**Evidence:** `input("Enter the number of terms: ")` prompts the user for input.

## 5. Example

**Claim:** Input `5` produces the output `0 1 1 2 3`.  
**Status:** Supported  
**Evidence:** The loop prints five terms, beginning with 0 and 1, and updates them using `a, b = b, a + b`.

## 6. Notes

**Claim:** The program does not include explicit validation for negative input or non-integer input.  
**Status:** Supported  
**Evidence:** The code converts input using `int()` but has no explicit validation or error handling.

## 7. License

**Claim:** License information has not been verified. 
**Status:** Unverified  
**Evidence:** The Python code alone cannot establish whether a license has been specified elsewhere in the repository.
