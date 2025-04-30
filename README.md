# 🔐 Password Strength Checker (Python CLI)

This Python script checks the strength of a password based on key criteria such as length, use of uppercase and lowercase letters, numbers, and special characters. It provides real-time feedback to help users improve their password security.

## 🚀 Features

- Evaluates password strength as **Strong**, **Medium**, or **Weak**
- Provides suggestions to improve password quality
- Simple command-line interface
- Uses regular expressions for validation

## ✅ Password Rules

A password is evaluated on the following criteria:

1. At least 8 characters in length
2. Contains at least one uppercase letter (A-Z)
3. Contains at least one lowercase letter (a-z)
4. Contains at least one number (0-9)
5. Contains at least one special character (e.g., !@#$%^&*)

## 📦 Requirements

- Python 3.x

> No external dependencies needed—uses built-in `re` module.

## 💻 How to Use

1. Clone or download this repository.
2. Open your terminal or command prompt.
3. Run the script:

```bash
python password_checker.py

Enter a password to check its strength: Hello123

Password Strength: 🟡 Medium Password

Suggestions to improve:
- ❌ Include at least one special character (!@#$...).

✨ Future Improvements
GUI version using Tkinter

Web version with Flask

Common password blacklist

Password entropy score calculation

