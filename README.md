# Week 6 Assignment - Safe Functions

### safe_tools.py

Contains three safe functions: `safe_divide`, `safe_number`, and `get_field`. The functions use `try` and `except` to handle errors without crashing the program.

### README.md

Contains the assignment information and an explanation of why an `if` check cannot catch `abc` on its own.

An `if` check can test conditions, but converting `"abc"` to an integer causes Python's `int()` function to raise a `ValueError`. Using `try` and `except ValueError` allows the program to catch that error and continue running.
