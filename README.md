# 🛂 User Input Validation Functions for Sign-Up System

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Cross--Platform-lightgrey)

## 📘 Overview

This project demonstrates how to build reusable Python validation functions to clean and verify user input during account sign-ups. It was developed in response to issues with invalid or incomplete sign-up attempts crashing a mobile app at a startup.

The notebook provides a foundational validation system for:

- **Name** validation
- **Email** validation (including domain checking)

These functions ensure that only valid, well-formed user inputs proceed to account creation, helping reduce app crashes and improve data integrity.

---

## 🚀 Getting Started

### 📦 Requirements

- Python 3.7+
- Jupyter Notebook

### 🔧 Setup

1. Clone this repository:

  ```bash
  git clone https://github.com/JarrarShahid/Core-Sign_Up-Functions-to-Help-Validate-New-Users.git
  cd Core-Sign_Up-Functions-to-Help-Validate-New-Users
  ```
2. Start the Jupyter Notebook:
  ```
   jupyter notebook
  ```
3. Open notebook.ipynb and run all cells.

## 🔍 Features
✅ Name Validation
Checks if the name:

  Is a string
  
  Has more than 2 characters

  ```
  validate_name("Tom")  # True
  validate_name("")     # False
  ```
## ✅ Email Validation
Checks if the email:

  Contains an "@" symbol
  
  Ends in a valid top-level domain (.com, .org, .io, etc.)
  
  ```
  validate_email("jane@company.org")  # True
  validate_email("johnexample.com")   # False
  ```

## 📋 Supported Top-Level Domains
```
[
    ".org", ".net", ".edu", ".ac", ".gov", ".com", ".io"
]
```

## 🧠 Why It Matters
Building validation functions like these ensures:

  Fewer app crashes due to malformed data

  Cleaner backend records

  Better user experience

## 👨‍💻 Author
[Jarrar Shahid](https://github.com/JarrarShahid)

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.







