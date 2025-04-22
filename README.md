# 🧾 Form Validation using Regex

This project demonstrates how to validate user input in a form using regular expressions (regex). It ensures that data like email addresses, phone numbers, passwords, and names meet specific formatting rules.

## 🚀 Features

- Email format validation
- Phone number validation
- Password strength validation
- Name field (letters only) validation
- Real-time feedback (if frontend is included)
- Backend validation using Python

## 📂 Project Structure


## 🧪 Regex Patterns Used

| Field      | Pattern                                                                 |
|------------|-------------------------------------------------------------------------|
| Email      | `r^[\w\.-]+@[\w\.-]+\.\w{2,4}$`                                          |
| Phone      | `r^\+?[0-9]{10,13}$`                                                     |
| Dateofbirth| ` r'\d{2}-\d{2}-\d{4}'|
| Name       | `r'^[A-Za-z ]+$'                                                     |

> Feel free to tweak these regex patterns based on your needs.

## 🛠️ Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/your-username/form-validation-regex.git
cd form-validation-regex
