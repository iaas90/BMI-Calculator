# 🩺 Simple Java BMI Calculator

## 📖 Table of Contents  
- [Description](#description)  
- [Features](#features)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Compile and Run](#compile-and-run)  
- [Usage Example](#usage-example)  
- [Project Structure](#project-structure)  
- [Potential Improvements](#potential-improvements)  
- [License / Notes](#license--notes)  

---

## Description  
This is a simple command-line Java program that calculates the Body Mass Index (BMI) based on user input. The user is prompted to enter their weight in kilograms and height in meters. The program then computes the BMI using the standard formula and prints the result.  

## Features  
- ✅ Calculates BMI using metric units (kg, m)  
- ✅ Simple and minimal — no extra libraries or dependencies required  
- ✅ Suitable as a learning exercise for Java beginners — demonstrates user input, arithmetic operations, and console output  

## Getting Started  

### Prerequisites  
- Java Development Kit (JDK) (version 8 or higher recommended)  
- Command-line / terminal access  

### Compile and Run  
From the root directory (where the `BMICalc` folder resides), run:
```bash
javac BMICalc/BMICalc.java
java BMICalc.BMICalc
````

Then follow the on-screen prompts to enter your weight and height.

---

## Usage Example

```
Enter your weight in kg  
> 70  
Enter your height in Meters  
> 1.75  

Your BMI is: 22.857142857142858
```

---

## Project Structure

```
BMICalc/
  └─ BMICalc.java   ← Main program
```

---

## Potential Improvements

* Format the BMI result to show only 2 decimal places (e.g. using `printf`) — makes the output cleaner. ([Stack Overflow][1])
* Add BMI category classification (underweight, normal, overweight, obese) based on the result. ([w3resource][2])
* Add input validation (e.g. check for non-positive or non-numeric input)
* Expand to support different units (e.g. pounds & inches)
* Optionally build a GUI version or web interface for easier use

---

## License / Notes

This is a simple learning project — you can use, modify, or expand it as you like.

```

