# Birthday Email Sender

## Overview

Birthday Email Sender is a Python application that automatically sends personalized birthday wishes via email using the Simple Mail Transfer Protocol (SMTP). The application prompts the user to enter the recipient's email address and name, then sends a customized birthday greeting.

This project demonstrates how to send emails securely using Gmail's SMTP server and Python's built-in email libraries.

---

## Features

* Sends personalized birthday wishes via email.
* Uses Gmail SMTP for secure email delivery.
* Accepts recipient email address as user input.
* Generates a customized birthday message.
* Simple command-line interface.
* Beginner-friendly Python project.

---

## Technologies Used

* Python 3
* smtplib
* email.mime.text

---

## Project Structure

```text
Birthday-Email-Sender/
│
├── birthday_email_sender.py
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Birthday-Email-Sender.git
```

Navigate to the project directory:

```bash
cd Birthday-Email-Sender
```

---

## Requirements

Python 3.x

This project uses Python's built-in libraries, so no additional packages need to be installed.

---

## Gmail Configuration

Before running the application:

1. Enable Two-Step Verification on your Google account.
2. Generate a Gmail App Password.
3. Replace the following values in the source code:

```python
sender = "your_email@gmail.com"
password = "your_app_password"
```

Use:

* Your Gmail address
* Your generated App Password

Do not use your regular Gmail password.

---

## Run the Application

Execute the following command:

```bash
python birthday_email_sender.py
```

or

```bash
python3 birthday_email_sender.py
```

---

## Example

### Input

```text
Enter receiver email:
john@example.com

Enter your name:
John
```

### Email Sent

**Subject**

```
Congratulations
```

**Message**

```
Happy Birthday, John!

Wishing you a wonderful birthday filled with happiness, good health, and success.

Have a great day!
```

---

## Learning Objectives

This project demonstrates:

* SMTP email communication
* Sending emails using Python
* MIME email formatting
* User input handling
* Secure authentication with Gmail App Passwords

---

## Future Improvements

* Automatic birthday reminders.
* Read recipient details from a CSV or Excel file.
* Send emails to multiple recipients.
* HTML email templates.
* Attach birthday greeting cards or images.
* Schedule automatic birthday emails.
* Graphical User Interface (GUI).
* Personalized message templates.

---

## Security Note

Never hardcode your email password in source code.

Instead, use:

* Environment variables
* Configuration files
* Secret management tools

This helps protect your credentials and improves application security.

---

## Author

Nek Sandha

Python | AI | Automation | Generative AI
