Name - Dolly singh
Company - Codtech IT Solutions
Domain - C Prohramming
Internship period - 03 June 2026 - 01 July 2026
# Electricity Bill Generator in C

## Overview

The Electricity Bill Generator is a simple C programming project that calculates the electricity bill based on the number of units consumed by a customer. The program uses slab-based billing rates and applies an additional surcharge when the bill amount exceeds a specified limit.

This project demonstrates the use of conditional statements, arithmetic calculations, and user input/output operations in C. It is designed to help beginners understand real-world applications of programming concepts.

## Features

* Accepts customer name and electricity units consumed
* Calculates bill using slab-wise electricity rates
* Automatically applies surcharge for high bill amounts
* Displays a detailed electricity bill summary
* User-friendly command-line interface
* Fast and accurate bill calculation

## Technologies Used

* C Programming Language
* Standard Input/Output Library (`stdio.h`)

## Billing Structure

The electricity bill is calculated according to the following slabs:

| Units Consumed | Rate per Unit |
| -------------- | ------------- |
| 0 – 100        | Rs. 1.50      |
| 101 – 200      | Rs. 2.50      |
| 201 – 300      | Rs. 4.00      |
| Above 300      | Rs. 6.00      |

### Surcharge

* A surcharge of **10%** is applied if the bill amount exceeds **Rs. 1000**.

## Working Principle

1. The user enters the customer name and the number of electricity units consumed.
2. The program calculates the bill based on predefined slab rates.
3. If the bill exceeds Rs. 1000, a 10% surcharge is added.
4. The final bill, including surcharge, is displayed in a formatted output.

## Learning Objectives

This project helps in understanding:

* Conditional statements (`if`, `else if`, `else`)
* Arithmetic operations and calculations
* User input and output handling
* Real-world billing systems
* Program logic and decision-making
* Formatted output generation

## Sample Output

```text
===== Electricity Bill Generator =====

Customer Name : Rahul
Units Consumed: 350

Bill Amount   : Rs. 1100.00
Surcharge     : Rs. 110.00
--------------------------------------
Total Bill    : Rs. 1210.00
```

## Future Enhancements

The project can be enhanced by adding:

* Customer ID generation
* Bill payment status
* Monthly bill history
* File handling for record storage
* Graphical User Interface (GUI)
* Different tariff plans
* Tax calculation and discounts

## Conclusion

The Electricity Bill Generator is a beginner-friendly C project that simulates a real-world electricity billing system. It provides practical experience in implementing conditional logic, performing calculations, and generating structured output, making it an excellent project for learning and academic purposes.
