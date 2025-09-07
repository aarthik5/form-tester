Form Tester Selenium Project

Overview

form_tester.py is a Python Selenium automation script that fills out forms on web pages and submits them. It demonstrates:
	•	Automation of form input
	•	Exception handling for errors
	•	Validation testing with different input data

This project uses the demo form at https://demoqa.com/automation-practice-form.

⸻

Features
	•	Automates filling form fields: First Name, Last Name, Email, Phone Number
	•	Submits the form and detects success or failure
	•	Handles invalid input gracefully
	•	Demonstrates automation and exception handling skills

⸻

Requirements
	•	Python 3.x
	•	Selenium WebDriver
	•	webdriver-manager package

Install dependencies with:

pip install selenium webdriver-manager


⸻

Usage
	1.	Run the script

python form_tester.py

	2.	Script Behavior

The script automatically:
	•	Opens the demo form
	•	Fills in test data (valid and invalid)
	•	Submits the form
	•	Prints success or failure messages in the terminal

⸻

Example Output

[SUCCESS] Form submitted successfully for John Doe
[ERROR] Exception while submitting form: Element not found
[FAILED] Form submission failed for Alice Smith


⸻

Project Structure

form-tester/
├── form_tester.py
├── README.md
└── .gitignore (optional)

Tip: Use .gitignore to ignore temporary files or browser logs.
