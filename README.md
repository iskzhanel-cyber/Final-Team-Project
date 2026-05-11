# Final-Team-Project
# Learning Buddy Telegram Bot

## Project Description
Here we have brief description of our project divided into 3 groupps:

First, this Telegram bot allows users to upload CSV/XLSX datasets and perform data analysis directly inside Telegram.

Users can:
- Upload datasets
- View dataset information
- Generate summary statistics
- Detect missing values
- Build histograms
- View correlations
- Export cleaned datasets

---

## Features

📂 Load Dataset  
📊 Dataset Info  
📈 Summary Statistics  
⚠ Missing Values  
🔗 Correlation Matrix  
📉 Histograms  
🔍 Search Columns  
💾 Export Clean Dataset  

---

## Technologies Used

- Python
- pandas
- numpy
- matplotlib
- pyTelegramBotAPI

---

## Installation

Install required libraries:

```bash
pip install -r requirements.txt
```

---

## How to Run

1. Open the project folder
2. Add your Telegram Bot Token
3. Run:

```bash
python bot.py
```

---

## File Formats Supported

- CSV
- XLSX

---

## Example Commands

- Upload dataset
- Histogram age
- Summary
- Correlation

---

## Author
Iskakova Zhanel

# 🎮 Fun Work Telegram Bot

## Project Description

Second, this Telegram bot provides a set of fun and utility tools accessible directly inside Telegram.

Users can:

- Use a built-in calculator with a button keyboard
- Set countdown timers with automatic notifications
- Share their GPS location and get a Google Maps link
- Assign custom stickers to each tool

-----

Features

🧮 Calculator  
⏱ Timer  
📍 Location  
🎭 Sticker Customization

-----

Technologies Used

- Python
- pyTelegramBotAPI
- threading

-----

Installation

Install required libraries:
pip install -r requirements.txt

Or manually:
pip install pytelegrambotapi

-----

How to Run

1. Open the project folder
1. Add your Telegram Bot Token
1. Run:
python team_bot.py

-----

How to Use

🧮 Calculator

- Press 🎮 Fun Work → 🧮 Calculator
- Use the on-screen keyboard to enter numbers and operators
- Press = to calculate
- Press ⌫ to delete last character, 🗑 to clear

⏱ Timer

- Press 🎮 Fun Work → ⏱ Timer
- Choose a preset: 30 sec, 1 min, 5 min, 10 min, 15 min, 30 min, 1 hour
- Or press ⌨️ Custom time and type any number of seconds
- The bot will send a notification when the timer ends

📍 Location

- Press 🎮 Fun Work → 📍 Location
- Tap the button to share your GPS coordinates
- The bot returns your latitude, longitude and a Google Maps link

🎭 Sticker Customization

- Press 🎮 Fun Work → 🎭 Sticker
- Choose a tool (Calculator, Timer, or Location)
- Send any sticker — it will appear every time you open that tool

-----

Example Commands

- Open 🎮 Fun Work from the main menu
- Type 45 after selecting Custom time to set a 45-second timer

-----

## Author
Baktygerey Shugyla

# ZIP Search Module

The ZIP Search module allows users to upload ZIP archives and perform file-based search and analysis directly inside Telegram.

### Features

📦 Upload ZIP archives  
📄 Display all files inside ZIP  
🔍 Search words inside TXT/CSV files  
📅 Search records by year  
🏙 Find records by city and year  
📊 Generate ZIP archive summary  
❓ Built-in help menu  

---

## How It Works

1. The user uploads a `.zip` archive
2. The bot saves the archive for the current user
3. The user can select different ZIP analysis functions using menu buttons

The bot processes:
- `.txt` files
- `.csv` files

inside the uploaded archive.

---

## ZIP Functions

### Files Inside ZIP
Displays all files stored inside the uploaded archive.

Example:
```text
ip_data_2020.txt
ip_data_2021.txt
regions.csv
```

---

### Search Word

Searches for a specific word inside all TXT and CSV files.

Example command:
```text
search Astana
```

The bot returns all matching lines where the word appears.

---

### Search by Year

Finds all records connected to a selected year.

Example:
```text
year 2020
```

---

### Find by City and Year

Searches records using two conditions simultaneously.

Example:
```text
find Astana 2021
```

---

### ZIP Summary

Generates archive statistics:
- total number of files
- number of TXT files
- number of CSV files
- total number of lines

---

### ZIP Help

Displays all available ZIP commands and usage examples.

---

## Programming Concepts Used

- Telegram message handlers
- File downloading
- ZIP processing with `zipfile`
- Dictionaries for user storage
- Exception handling (`try/except`)
- File iteration
- Text searching
- Conditional statements

---

## Why This Module Is Useful

This module demonstrates practical work with:
- archives
- file systems
- text processing
- search algorithms
- Telegram bot interaction

It makes the bot more interactive and shows how Python can automate file-based analysis tasks.
## Author
Tursynbay Aspan
