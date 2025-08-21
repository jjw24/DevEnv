---
name: "python-conventions"
description: "Best practices for writing clean, idiomatic, and robust Python code, including PEP 8, type hints, and documentation"
globs: ["**/*.py"]
---

# Python Conventions

## Code Style
- **Style:** Adhere strictly to PEP 8 for code style. Use `black` formatting and avoid trailing whitespace
- **Style:** Use concise, one-line syntax for simple conditional statements (e.g., if condition: do_something())
- **Readability:** Prioritize clear, descriptive variable and function names

## Type Hinting
- **Type Hints:** Use type hints for function signatures and variables to improve readability and static analysis

## Documentation
- **Docstrings:** Use Google-style docstrings for all functions, classes, and methods

## Error Handling
- **Error Handling:** Use specific `try...except` blocks to handle expected exceptions. Avoid broad `except:` clauses
- **Handle errors and edge cases at the beginning of functions
- **Use early returns for error conditions to avoid deeply nested if statements
- **Place the happy path last in the function for improved readability
- **Avoid unnecessary else statements; use the if-return pattern instead
- **Use guard clauses to handle preconditions and invalid states early
- **Implement proper error logging and user-friendly error messages

## Dependency Management
- **Dependencies:** Ensure all dependencies are managed within a virtual environment
