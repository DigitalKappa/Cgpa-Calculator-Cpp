# CGPA Calculator & Semester Performance Analyzer

>A C++ console application to calculate semester GPA and cumulative CGPA across an 8-semester degree — built to practice OOP, arrays, and function design.

## Overview

This program helps students track academic performance across an 8-semester degree. It accepts marks for multiple subjects per semester, converts raw scores to a 4-point GPA scale weighted by credit hours, and computes individual semester GPAs and the final CGPA. Results are displayed in a clean tabular format.

Built using two classes — `Degreeresult` for student identity and `markscalculator` for GPA logic — this project was my first serious attempt at multi-class C++ design.


## Features

- Handles all 8 semesters with correct subject and credit-hour configuration
- Weighted GPA calculation on a standard 4.0 scale
- Stores all semester GPAs in an internal array
- Tabular display of all semester results
- Final CGPA calculation and grade classification
- Demonstrates function overloading and static variables
- Two-class OOP design: `Degreeresult` + `markscalculator`

## Technologies Used

- **Language:** C++
- **Concepts:** Classes, Arrays, Function Overloading, Static Variables, cin/cout
- **IDE:** Visual Studio / Code::Blocks / Dev-C++

## How It Works

1. User enters name and roll number — stored in `Degreeresult`
2. For semesters 1–7, marks are entered for 5 subjects (credit hours: 3, 3, 3, 2, 4)
3. Semester 8 has 2 subjects (credit hours: 2 and 4)
4. `markscalculator` converts marks to GPA points using a weighted formula
5. Each semester GPA is stored in an array and displayed after entry
6. After all 8 semesters, CGPA is computed as the average of all GPAs
7. A final grade is assigned based on the CGPA value

---

## Installation & Setup

**Requirements:** g++ compiler or any C++ IDE
```bash
# Clone the repository
git clone https://github.com/your-username/cgpa-calculator-cpp.git
cd cgpa-calculator-cpp

# Compile
g++ main.cpp -o cgpa_calculator

# Run
./cgpa_calculator
```

## Usage

Run the program and follow the prompts. Enter your name, roll number, and marks for each subject per semester. The program will display a semester-by-semester GPA table and your final CGPA at the end.

## Future Improvements

- Save results to a `.txt` or `.csv` file for record keeping
- Support user-defined credit hours instead of hardcoded values
- Add a target CGPA predictor for remaining semesters
- Build a simple GUI version using Qt or Windows Forms

## What I Learned

- How to split responsibilities across multiple classes in C++
- Using arrays to store and retrieve calculated values across the program
- Applying function overloading for different semester configurations
- How real-world GPA systems are modeled programmatically


## 🧾 Short Description
```
A menu-driven C++ console application simulating core banking operations — account creation, deposit, withdrawal, and balance display — built to practice OOP encapsulation and input validation.
