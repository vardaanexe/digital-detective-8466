# Mission 5 – Numbers & Data

## 1. Task / Objective
The objective of this mission is to understand number systems, perform conversions manually, verify them using Python and create a number converter program.

## 2. Manual Number Conversions

### Decimal to Binary

**13 to Binary**

13 ÷ 2 = 6 remainder 1  
6 ÷ 2 = 3 remainder 0  
3 ÷ 2 = 1 remainder 1  
1 ÷ 2 = 0 remainder 1  

Reading remainders from bottom to top:

13 = 1101 (Binary)

**25 to Binary**

25 ÷ 2 = 12 remainder 1  
12 ÷ 2 = 6 remainder 0  
6 ÷ 2 = 3 remainder 0  
3 ÷ 2 = 1 remainder 1  
1 ÷ 2 = 0 remainder 1  

25 = 11001 (Binary)

### Binary to Decimal

1010 = (1×8) + (0×4) + (1×2) + (0×1) = 10

1101 = (1×8) + (1×4) + (0×2) + (1×1) = 13

### Hexadecimal to Decimal

A = 10

1F = (1×16) + (15×1) = 31

### Binary to Hexadecimal

1111 = 15 in decimal = F in hexadecimal.

## 3. Python Verification

Python can verify conversions using built-in functions:

- `bin(13)` gives `0b1101`
- `bin(25)` gives `0b11001`
- `int("1010", 2)` gives `10`
- `int("1101", 2)` gives `13`
- `int("A", 16)` gives `10`
- `int("1F", 16)` gives `31`
- `hex(15)` gives `0xf`

## 4. Number Converter Program

File: `number_converter.py`

The program will ask the user for a decimal number and display its binary and hexadecimal forms.
### Program Code

The program takes a decimal number as input and converts it into binary and hexadecimal using Python's built-in functions.

### Program Testing

I tested the program with three different inputs:

| Input | Binary Output | Hexadecimal Output |
|---|---|---|
| 13 | 1101 | D |
| 25 | 11001 | 19 |
| 100 | 1100100 | 64 |

All three test cases produced the expected results.

### Difficulties Faced

I initially needed to understand how Python converts decimal numbers into binary and hexadecimal.

### How I Resolved Them

I used Python's built-in `bin()` and `hex()` functions and tested the program with different decimal inputs.

## 5. ASCII and Character Encoding

ASCII stands for American Standard Code for Information Interchange.

- Capital A has ASCII value 65.
- Small a has ASCII value 97.

Character encoding is a system that represents text characters as numbers so computers can store and process them. UTF-8 is a widely used character encoding.

## 6. My Understanding

I learned how decimal, binary and hexadecimal number systems work and how to convert values between them. I also learned that Python can verify these conversions.

## 7. Difficulties Faced

To be completed after practical work.

## 8. How I Resolved Them

To be completed after practical work.

## 9. Evidence / Files

- `README.md`
- `number_converter.py`
- Terminal outputs showing program tests

## 10. Commit Details

Commit message: Mission 5 - Number systems and data conversion