# ALX Backend Python - Variable Annotations

## Description

This project includes Python scripts that demonstrate the use of variable annotations and type hints. Specifically, it contains a function `add` that adds two floating-point numbers with proper type annotations and documentation.

## Files

- `0-add.py`: Contains the `add` function with type annotations and documentation.
- `0-main.py`: A test script to verify the functionality of the `add` function.

## Requirements

- Python 3.7
- Ubuntu 18.04 LTS environment

## Usage

1. **Make the scripts executable**:

    ```bash
    chmod +x 0-add.py
    chmod +x 0-main.py
    ```

2. **Run the test script**:

    ```bash
    ./0-main.py
    ```

    **Expected Output**:

    ```
    True
    {'a': <class 'float'>, 'b': <class 'float'>, 'return': <class 'float'>}
    ```

## Coding Style

The code follows the `pycodestyle` standards (version 2.5). To check for style compliance, run:

```bash
pycodestyle 0-add.py
