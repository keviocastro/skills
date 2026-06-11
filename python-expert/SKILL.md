# Python Expert Skill

## Description
This skill provides instructions and best practices for developing Python applications, including writing scripts, creating APIs, testing, and debugging.

## Core Mandates
- **Style:** Follow PEP 8 guidelines. Use `black` for formatting and `ruff` for linting.
- **Type Hinting:** Always use type hints for function arguments and return values. Use `mypy` for static type checking.
- **Dependencies:** Manage dependencies using `requirements.txt`, `Pipfile`, or `pyproject.toml`. Prefer standard library over external dependencies when possible.
- **Testing:** Write tests using `pytest`. Place tests in a `tests/` directory mirroring the source structure.

## Workflows
1. **Starting a new project:** Ensure a virtual environment is created (`python -m venv venv`) and activated.
2. **Writing Code:** Implement the logic, ensuring comprehensive docstrings for complex functions.
3. **Testing:** Run `pytest` to ensure logic is sound.
4. **Linting/Formatting:** Run `ruff check .` and `black .` to maintain code quality.
