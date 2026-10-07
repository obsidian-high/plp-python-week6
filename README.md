# Week 6 Assignment: Hands-On Lab - Grades, Eligibility & Smart Decisions

This repository contains my Week 6 Python assignment.

- `safe_tools.py` - Contains three safe functions that handle division, number conversion, and dictionary key lookup errors.

An `if` check cannot catch `abc` on its own because `abc` is text, and the problem happens when Python tries to convert that text into an integer. The `int()` conversion raises a `ValueError`, so `try` and `except ValueError` are needed to handle it safely.
