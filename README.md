# Calculator

## Table of contents
* [Installation](#installation)
* [Project Motivation](#project-motivation)
* [Setup](#setup)
* [Code Examples](#code-examples)
* [Features](#features)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)
 

## Installation
* Python - version 3.8

## Project Motivation
The aim of the project is to build a simple python package with basic functions: add, subtract, multiply, divide and nth root. Also an ability to reset to zero.

## Setup
- to use the package in your notebook:
```python
!pip install git+https://github.com/Ifyokoh/calculator.git

from calculator.calculator import Calculator
```

## Code Examples
```python
calculator = Calculator()
calculator.add(6)
calculator.subtract(3)
calculator.multiply(2)
calculator.divide(5)
calculator.reset_memory()
```

## Features: _functions_
* Addition / Subtraction: _add / subtract_
* Multiplication / Division: _multiply / divide_
* Take (n) root of number: _take_root_
* Memory of last result: _reset_memory_

## License
This project is licensed under the terms of the **MIT** [license](https://opensource.org/licenses/MIT).

## Acknowledgements
Turing College