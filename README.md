# Task Automation – Extract Emails from a .txt File
## Overview

This project is a simple Python-based task automation tool that extracts email addresses from a text (.txt) file. It scans the file, identifies valid email patterns using regular expressions, and saves the extracted email addresses into a separate output file.
This project demonstrates basic automation, file handling, and pattern matching using Python.

## Features

* Reads data from a .txt file
* Extracts valid email addresses using Regular Expressions
* Removes duplicate emails (optional if implemented)
* Saves extracted emails into a new file
* Simple and easy to understand code structure

## Technologies Used

* Python
* Regular Expressions (re module)
* File Handling

## Project Structure

Task-Automation-Email-Extractor
─ extract_emails.py
─ input.txt
─ extracted_emails.txt
─ requirements.txt
─ README.md

## How It Works

1. The program opens a text file (input.txt).
2. It searches for patterns that match email addresses.
3. All detected emails are stored in a list.
4. The extracted emails are written into extracted_emails.txt.

## Installation and Setup

1. Make sure Python is installed.
2. Clone the repository or download the files.
3. Place your text content inside input.txt.
4. Run the script:
   python extract_emails.py
5. Check extracted_emails.txt for results.

## Future Improvements

* Add email validation verification
* Add GUI interface
* Accept file path from user input
* Export results to CSV format
* Add logging system

## Learning Outcomes

* Understanding of file handling in Python
* Practical use of Regular Expressions
* Basic automation concepts
* Writing clean and structured scripts
