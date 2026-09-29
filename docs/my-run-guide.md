# Run Guide

## Prerequisites

- **Git 2.23 or later**, including `git switch` and `git restore`.
- **JDK 17 or later**: both `java` and the compiler `javac` must be available.
- **Python 3.9 or later**. The lab runner uses only Python's standard library.
- A **GitHub account** and permission to push to your own fork.
- A terminal and a text editor.

## How to run the demo
Run the following command from the root directory:

```bash
python3 run.py demo
```

## Description

This demo initializes the library catalog, registers members, processes sample loans and returns, and prints out the system state and overdue calculations to verify the core borrowing rules.