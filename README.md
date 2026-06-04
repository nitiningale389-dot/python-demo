# Personal Data Collector (Python Notebook)

## Overview
This project is a simple interactive Python program that collects basic personal information from a user and displays it along with data types and memory addresses.

## Features
- Collects user name
- Collects age
- Collects height (in meters)
- Collects favorite number
- Displays entered data
- Shows Python data types using `type()`
- Shows memory addresses using `id()`
- Calculates an approximate birth year based on the user's age

## Technologies Used
- Python 3
- Jupyter Notebook (`.ipynb`)

## How It Works
1. The program welcomes the user.
2. It asks for:
   - Name
   - Age
   - Height
   - Favorite Number
3. The collected information is displayed.
4. The program calculates the approximate birth year using:
   
   ```python
   birth_year = 2026 - age
   ```

5. A goodbye message is displayed.

## Sample Output

```text
Welcome to the interactive Personal Data Collector!

Please enter your name: John
Please enter your age: 20
Please enter your height in meters: 1.75
Please enter your favourite number: 7

Thank you! Here is the information we collected:
Name: John
Age: 20
Height: 1.75
Favourite Number: 7

Your birth year is approximately: 2006
```

## Learning Concepts
This project demonstrates:
- User input with `input()`
- Type conversion (`str`, `int`, `float`)
- Variables and data types
- Output formatting with `print()`
- Memory addresses using `id()`
- Basic arithmetic operations

## File Structure

```text
PR1.ipynb   # Main Jupyter Notebook
README.md   # Project documentation
```

## Author
Created as a beginner Python practice project.

