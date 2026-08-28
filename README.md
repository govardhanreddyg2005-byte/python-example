# python-example

# 🐍 PyExample Utility Library

A lightweight Python utility library for handling string transformations and mathematical operations.

## Installation

Install the package via pip:

```bash
pip install pyexample-utils
```

## Quick Start

Here is a quick example of how to import and use the library:

```python
from pyexample import StringManipulator, Calculator

# Initialize modules
manipulator = StringManipulator()
calc = Calculator()

# 1. Reverse a string
result_str = manipulator.reverse_text("Hello GitHub")
print(result_str)  # Output: buHtiG olleH

# 2. Add two numbers
result_num = calc.add(10, 5)
print(result_num)  # Output: 15.0
```

## Running Tests

To run the internal unit tests, execute the following command in your terminal:

```bash
python -m unittest discover tests/
```

## License

This project is licensed under the MIT License.
