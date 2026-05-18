# Python File Automation System
A beginner-friendly Python automation project that automatically organizes files into folders based on their file type. This project demonstrates the basics of Python automation, file handling, and workflow scripting.


# Project Overview

Managing files manually can be repetitive and time-consuming. This automation script scans a folder, identifies file types, and moves files into categorized folders automatically.

For example:

Before running the script:

Downloads/
│
├── photo.jpg
├── report.pdf
├── movie.mp4
├── notes.txt

After running the script:

Downloads/
│
├── Images/
│   └── photo.jpg
│
├── Documents/
│   ├── report.pdf
│   └── notes.txt
│
├── Videos/
│   └── movie.mp4

This project is a simple example of how Python can automate repetitive tasks efficiently.

---

# Features

- Automatically organizes files by extension
- Creates folders automatically if they do not exist
- Supports multiple file categories
- Reduces manual file management effort
- Beginner-friendly Python project
- Demonstrates automation fundamentals

---

# Technologies Used

- Python
- os module
- shutil module

---

# File Categories Supported

| Category   | Extensions |
|------------|------------|
| Images     | .jpg, .jpeg, .png |
| Documents  | .pdf, .docx, .txt |
| Videos     | .mp4, .mkv |

You can easily customize the script to support more file types.

---

# How It Works

The script performs the following steps:

1. Scans the selected folder
2. Checks each file extension
3. Creates category folders if needed
4. Moves files into the correct folders automatically

---

# Project Structure

python-file-automation/
│
├── file_organizer.py
├── README.md
└── test_folder/

---

# Installation & Setup

## Step 1: Install Python

Download and install Python from:

https://www.python.org/downloads/

---

## Step 2: Clone or Download the Project

Download this repository or clone it using Git:

```bash
git clone https://github.com/yourusername/python-file-automation.git
