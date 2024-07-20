# Car Rental System

This is a simple car rental system implemented in C++. It allows users to manage customers, employees, and cars. The system is designed to be modular, with separate classes for each entity.

## Getting Started

To get started, extract the code into a separate folder and compile it using a C++ compiler. Once compiled, run the executable to launch the system.

## Prerequisites

A C++ compiler is required to build and run this system.

## Built With

- C++11

## Authors

- Shahnawaz Mustafir
- 
## Initial Database:

### CUSTOMERS

| ID | NAME | PASSWORD | DUES | RECORD | CURRENTLY RENTED CARS | OTHER DETAILS |
|----|------|----------|------|--------|-----------------------|---------------|
| 1  | C1   | P1       | 0    | 40     | 0                     | NA            |
| 2  | C2   | P2       | 0    | 40     | 0                     | NA            |
| 3  | C3   | P3       | 0    | 40     | 0                     | NA            |
| 4  | C4   | P4       | 0    | 40     | 0                     | NA            |
| 5  | C5   | P5       | 0    | 40     | 0                     | NA            |

### EMPLOYEES

| ID | NAME | PASSWORD | DUES | RECORD | CURRENTLY RENTED CARS | OTHER DETAILS |
|----|------|----------|------|--------|-----------------------|---------------|
| 1  | E1   | P1       | 0    | 40     | 0                     | NA            |
| 2  | E2   | P2       | 0    | 40     | 0                     | NA            |
| 3  | E3   | P3       | 0    | 40     | 0                     | NA            |
| 4  | E4   | P4       | 0    | 40     | 0                     | NA            |
| 5  | E5   | P5       | 0    | 40     | 0                     | NA            |

### CARS

| ID | CONDITION | OTHER DETAILS | AVAILABILITY | CURRENTLY RENTED BY | BOOK DATE | DUE DATE |
|----|-----------|---------------|--------------|----------------------|-----------|----------|
| 1  | CAR1      | NA            | AVAILABLE    | NA                   | NA        | NA       |
| 2  | CAR2      | NA            | AVAILABLE    | NA                   | NA        | NA       |
| 3  | CAR3      | NA            | AVAILABLE    | NA                   | NA        | NA       |
| 4  | CAR4      | NA            | AVAILABLE    | NA                   | NA        | NA       |
| 5  | CAR5      | NA            | AVAILABLE    | NA                   | NA        | NA       |

### MANAGER ACCESS

- ID: 1
- PASSWORD: manager

## Assumptions

- Users won't tamper with the given text files.
- Some checks, such as ensuring the correct car model is entered during return, are assumed to be the user's responsibility.
- Most edge cases have been addressed.
- Any missed cases are due to time constraints.
- IDs are automatically assigned using counters stored in the "globals.txt" file. They are saved at the end of the main function. Please exit the program properly by following the instructions provided to prevent data from becoming asynchronous.
