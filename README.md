Bank Management System
🏦 Secure Command-Line Bank Management System
A Python CLI application simulating core banking operations with secure user authentication, account management, financial transactions (deposits, withdrawals, transfers), transaction history, and an admin panel for oversight.
✨ Features
User registration, login, and password hashing.
Create and manage multiple savings/checking accounts.
Perform deposits, withdrawals, and inter-account transfers.
View detailed transaction history.
Admin panel: manage users (activate/deactivate), view all accounts and transactions.
💻 Technologies
Python 3.x
SQLAlchemy (ORM)
SQLite (Database)
bcrypt (Password Hashing)
🚀 Getting Started
Clone the repository.
Create and activate a virtual environment:
python -m venv .venv
# Windows: .\.venv\Scripts\activate
# macOS/Linux: source ./.venv/bin/activate

Install dependencies:
pip install sqlalchemy bcrypt

Run the application (all code in main.py):
python main.py



E-commerce Backend Engine

🛒 RESTful E-commerce Backend API
A conceptual RESTful API backend built with Python (Flask/Django) for an e-commerce platform. It provides essential services for user management, product catalog, shopping carts, and order processing, designed for frontend integration.
✨ Features
User authentication (registration, login, RBAC for customers/admins).
Product management (CRUD operations).
Shopping cart functionality (add/remove items, update quantity).
Order processing and history.
Stock management and validation.
💻 Technologies
Python 3.x
Flask / Django (Web Framework)
PostgreSQL / SQLite (Database)
SQLAlchemy / Django ORM (ORM)
bcrypt / Django's hashing (Authentication)
🚀 Getting Started
Clone the repository.
Create and activate a virtual environment (as above).
Install dependencies (choose based on Flask or Django):
# For Flask example:
pip install Flask SQLAlchemy Flask-Migrate bcrypt
# For Django example:
pip install Django djangorestframework

Configure database and run migrations (specifics vary by framework).
Run the server:
# Flask: flask run
# Django: python manage.py runserver


 Multi-User Chat Application

💬 Real-time Multi-User Chat (Socket & Threading)
A foundational real-time chat application demonstrating direct network communication using Python's socket module and concurrent client handling via threading. It features a server that broadcasts messages, supports custom nicknames, and includes basic moderation commands.
✨ Features
Instant message exchange between multiple clients.
Server handles concurrent connections.
Clients use unique nicknames.
Messages broadcast to all participants.
Basic admin commands (e.g., /kick).
💻 Technologies
Python 3.x
socket module (Network communication)
threading module (Concurrency)
🚀 Getting Started
Clone the repository (ensure server.py and client.py are present).
Create and activate a virtual environment (as above).
No external dependencies required.
Open two (or more) separate terminal windows.
In the first terminal, run the server:
python server.py

In the second (and subsequent) terminals, run the client:
python client.py

Enter a nickname when prompted.


 Custom File Encryption/Decryption Tool

🔒 Secure File Encryption/Decryption Tool (AES-256)
A command-line utility in Python for advanced file encryption and decryption. It employs AES-256 symmetric encryption with robust PBKDF2 key derivation from a user-defined passphrase, ensuring strong data confidentiality.
✨ Features
Encrypts files using AES-256 in CBC mode.
Securely derives keys from passwords using PBKDF2 with SHA256.
Generates unique cryptographic salts and Initialization Vectors (IVs) per encryption.
Supports large files by processing data in chunks.
Includes comprehensive error handling for file operations and password validation.
💻 Technologies
Python 3.x
cryptography library (AES, PBKDF2, padding primitives)
secrets module (Cryptographically strong randomness)
🚀 Getting Started
Clone the repository (ensure encrypt_tool.py is present).
Create and activate a virtual environment (as above).
Install dependencies:
pip install cryptography

Run the tool:
python encrypt_tool.py

Follow the interactive prompts to encrypt or decrypt files.


Library Management System
A Python desktop app to manage books, issues, returns, and fines using Tkinter and SQLite.dd, search, issue, return, and delete books.
Late fee calculation after a 14-day grace period.
Simple and user-friendly interface.
How to Run:

Install Python 3.12.
Open the project folder in any IDE.
Run main.py.
Future Scope: Login system, barcode scanning, report generation.

📄 PDF Merger & Splitter Utility
A lightweight desktop tool to merge, split, and extract PDF pages.Merge multiple PDFs.Split into single-page files.Extract selected pages via GUI.

How to Run:
Install Python 3.12.
Install PyPDF2 using the command: pip install PyPDF2.
Open the project folder in any IDE.
Run main.py.
Future Scope: Drag-and-drop, page reordering, progress bar.

⏰ Task Scheduler with Notifications
A desktop reminder app with scheduled tasks and desktop notifications.Add one-time, daily, or weekly tasks.Get real-time desktop alerts.Unique task IDs and SQLite storage.
How to Run:

Install Python 3.12.
Install Plyer using the command: pip install plyer.
Open the project folder in any IDE.
Run main.py.

Future Scope: Task editing, CSV export/import, sound alerts.


🔗 URL Shortener Microservice
A Flask-based microservice to generate and manage short URLs.Create short links with base62 encoding.Redirect to original URLs.Simple form-based web app.

How to Run:
Install Python 3.12.
Install Flask using the command: pip install flask.
Run the file URLShortener.py.
Open a browser and go to: http://localhost:5000/.
Future Scope: Click tracking, custom aliases, cloud deployment.

📦 Inventory Management System
📌 Description
A GUI-based Inventory Management System built using Python and Tkinter. It helps small businesses manage their stock by allowing them to add, update, delete, and search inventory items. It also supports CSV export, total inventory value calculation, and alerts for low stock levels.

⭐ Features
➕ Add, update, delete, and search inventory items

📊 View total inventory value

📁 Export inventory data to CSV

⚠️ Restock alerts for low quantity

🖥️ User-friendly GUI with real-time table display

🛠️ Technologies
Python 3.x

Tkinter

CSV (built-in)

🚀 Getting Started
🔧 Create and activate a virtual environment
Type the following: python -m venv .venv

For Windows, type: ..venv\Scripts\activate

For macOS/Linux, type: source .venv/bin/activate

📥 Install dependencies
Type: pip install -r requirements.txt

▶️ Run the app
Type: python inventory_gui.py

🛠️ CLI-Based Project Tracker with GUI
📌 Description
A GUI-based project tracker that helps freelancers or developers track project hours, time logs, billing, and notes. It allows project-wise log entries, hourly billing computation, summary generation, and CSV export.

⭐ Features
➕ Add projects with hourly rate

🕒 Log work hours with notes

📄 View logs in a dynamic table

🧾 Generate and view billing summaries

📁 Export time logs to CSV

🖥️ GUI built using Tkinter

🛠️ Technologies
Python 3.x

Tkinter

CSV

datetime

🚀 Getting Started
🔧 Create and activate a virtual environment
Type the following: python -m venv .venv

For Windows, type: ..venv\Scripts\activate

For macOS/Linux, type: source .venv/bin/activate

📥 Install dependencies
Type: pip install -r requirements.txt

▶️ Run the app
Type: python project_tracker.py

🌐 DNS Lookup and Traceroute Tool
📌 Description
A Python-based network diagnostic tool that performs DNS resolution, traceroutes, and latency checks. It helps users and network engineers analyze connectivity issues.

⭐ Features
🌍 DNS Lookup

🛰️ ICMP-based Traceroute

⏱️ Latency testing using ping logic

🛠️ Technologies
Python 3.x

socket

scapy

time

🚀 Getting Started
🔧 Create and activate a virtual environment
Type the following: python -m venv .venv

For Windows, type: ..venv\Scripts\activate

For macOS/Linux, type: source .venv/bin/activate

📥 Install dependencies
Type: pip install scapy

▶️ Run the app
Type: python dns_tool.py

⚠️ Note: You might see a "No libpcap provider available" warning. It can be ignored if basic traceroute and ping are functioning.

🗂️ Advanced File Organizer Bot
📌 Description
An intelligent file organization bot with a GUI that monitors a selected folder and organizes files in real-time based on extension, type, or size. Ideal for automating cleanup in Downloads or Desktop folders.

⭐ Features
🗂️ GUI for selecting folder and sorting options

📁 Organizes files by extension/type/size

🔄 Real-time monitoring using Watchdog

📂 Auto-creates categorized folders

🛠️ Technologies
Python 3.x

Tkinter

Watchdog

OS / shutil

🚀 Getting Started
🔧 Create and activate a virtual environment
Type the following: python -m venv .venv

For Windows, type: ..venv\Scripts\activate

For macOS/Linux, type: source .venv/bin/activate

📥 Install dependencies
Type: pip install watchdog

▶️ Run the app
Type: python file_organizer.py

✅ Each project includes clean UI, error handling, and is beginner-friendly yet practical for real-world use.


Command-Line Password Manager
Project Description
This project is a secure Python-based command-line application designed to manage and protect user passwords. It uses a master password to control access and applies AES encryption (via the cryptography library) to store all credentials safely in a local file.
Users can add, view, and manage credentials for multiple websites or apps. Passwords are encrypted and stored in a JSON file (vault.json), and can only be accessed after entering the correct master key. The project uses getpass to securely input passwords without displaying them on the screen.

 Key Highlights
Local password storage with AES encryption
Simple command-line interface (CLI)
Passwords hidden during input using getpass
No internet or external database required — completely offline and secure
Technologies Used
Python 3.x – Core language for scripting
cryptography – Used for AES encryption (Fernet)
getpass – Hides password input in terminal
json – For storing encrypted data in a structured format
base64, os, hashlib – Utilities for secure key derivation and file handling

 Architectural Highlights & Design Choices
Master Password-Based Access:
Users must enter a master password at runtime. This password is used to derive an AES encryption key via PBKDF2HMAC with a salt.
AES Encryption via Fernet:
All site credentials (username + password) are encrypted using a symmetric key with the Fernet protocol, ensuring high security.
Local Vault File (vault.json):
The password vault is stored as an encrypted JSON file locally. No cloud or third-party storage is involved, reducing attack surfaces.
Modular Design:
The program separates concerns like encryption, file handling, and user interaction into functions for easy updates and debugging.

 Challenges and Solutions
Challenge
Solution
Securely storing passwords
Used cryptography.fernet to encrypt data
Protecting user input
Implemented getpass to hide password entries
Preventing brute force or misuse
Encrypted data using a derived key from a salted master password
First-run file setup
Automatically generates salt and vault file on the first execution


 Future Enhancements
 Search Functionality: Quickly find credentials by site name
 Delete or Update Entries: Allow modifying or removing existing passwords
 Export/Backup: Secure export and import of encrypted vaults
Auto-Lock: Lock the vault after a period of inactivity
Brute Force Protection: Add attempt limits and cooldown timers
Optional Cloud Sync: Encrypted vault sync to cloud (with user consent)
















Expense & Budget Tracker

 1. Project Overview
The Expense & Budget Tracker is a GUI-based personal finance tool built in Python using Tkinter.
Its primary purpose is to help users log daily expenses, set monthly budgets, and analyze their spending habits through clear reports and visual charts.
This project simplifies everyday money management by allowing users to enter expense details, store them locally, and view summaries that promote better financial decision-making.

 2. Key Features
Feature
Description
💵 Add Daily Expense
Users can enter an amount, category (e.g., Food, Travel), and notes
🧾 Monthly Budget
Allows setting a fixed monthly budget and checks how much remains
📊 View Reports
Shows total spent, remaining budget, and breakdown per category
📈 Pie Chart Visualization
Generates a visual summary of expenses using Matplotlib
💾 Persistent Storage
All expense data is stored in a CSV file for portability


 3. Technologies Used

Technology
Purpose
Python 3.x
Core programming language
Tkinter
GUI framework to create forms and buttons
CSV
Lightweight file-based storage for expenses
Matplotlib
To create pie charts and visual summaries
Datetime
For recording current date with each expense


 4. Architectural Highlights & Design Choices
 GUI-Centric Design:
Chose Tkinter for simplicity and wide support with Python.
Designed the app for non-technical users—everything is done via buttons and input fields, no terminal use.
File-Based Data Storage:
CSV was chosen over databases to keep it lightweight, portable, and dependency-free.
Data entries are timestamped, enabling future filtering by date.
 Modular Functional Layout:
UI and logic are separated cleanly.
Each action (add expense, view report, show chart) is encapsulated in a method.
 Visual Reporting:
Used Matplotlib to turn expense data into an easy-to-understand pie chart.
Helps users make informed decisions visually.

 5. Challenges and Solutions

Challenge
Solution
Input validation (e.g., non-numeric values)
Added try-except blocks and error prompts using messagebox
Avoiding UI clutter
Created a compact layout using grid() with proper padding
Data storage with no SQL
Used structured CSV format, readable and easy to manipulate
File not found / CSV missing on first run
Script checks and auto-creates data.csv if missing
User forgets category or input
Required field checks and defaults were added


 6. Future Enhancements

Improvement
Description
 User Accounts
       Add login system to support multiple users
Switch to SQLite or MongoDB
       Replace CSV with a real database for scalability
 Date-Based Filtering
        Allow users to filter by week/month or custom date range
 Export Reports
Export summaries to PDF or Excel for offline access
 Web Version
Rebuild using Flask or Django to make it available online
 Mobile App
Create an Android version using Kivy or React Native









Dynamic Web Scraper + Export to Excel


 Project Description
This project is a dynamic web scraping tool built using Python, Selenium, and OpenPyXL that extracts structured data (book titles and prices) from a paginated website: Books to Scrape. It automates browser interaction, handles dynamic content loading, and seamlessly exports the scraped data to an Excel spreadsheet.
The scraper is easily customizable for other sites and is intended to demonstrate real-world web automation, data extraction, and reporting using modern Python tools.

Features
🔄 Pagination Support: Automatically navigates through multiple pages.
🧠 Dynamic Content Handling: Uses Selenium to interact with JavaScript-rendered content.
📤 Excel Export: Data is saved in a clean Excel file (.xlsx) using OpenPyXL.
🔍 Targeted Data Extraction: Scrapes specific information like title and price.
🧩 Modular Code Structure: Organized functions for scraping, exporting, and handling navigation.
🛠️ Easy Customization: Adaptable for scraping other websites with minimal changes.

 Technologies Used
Tool
Purpose
Python 3.x
Core programming language
Selenium
Web browser automation and scraping
OpenPyXL
Writing data to Excel files
ChromeDriver
Driver for controlling Chrome browser
Google Chrome
Headed browser for rendering web content


Architectural Highlights & Design Choices
Selenium for Rendering Dynamic Content
Chosen over BeautifulSoup because the target website could include JavaScript-rendered elements. Selenium handles real browser interaction.
Pagination Loop
Implemented using a loop that dynamically updates the page URL (page-1.html, page-2.html, etc.), enabling scalable data scraping.
Excel Export via OpenPyXL
A structured and well-supported method to export tabular data into .xlsx format, allowing easy viewing and further processing.
Delays with time.sleep()
Used for simplicity and reliability to wait for pages to load. Can be replaced with WebDriverWait for more advanced handling.

 Challenges and Solutions
Challenge
Solution
Unicode errors from Windows file paths
Used raw strings (r"path\to\file") to fix \u escape errors.
Module errors like No module named selenium
Clarified proper pip install selenium usage within PyCharm/terminal.
Matching ChromeDriver version
Added instructions to match driver with the installed Chrome version.
Dynamic element loading delays
Introduced time.sleep() to allow pages to fully render.


 Future Enhancements
✅ Headless Mode: Run Chrome in headless mode to make the scraper faster and silent.
✅ CSV Export Option: Allow users to choose between .xlsx or .csv formats.
✅ WebDriverWait: Use explicit waits instead of time.sleep() for better control.
✅ Logging System: Add logs to track scraping progress and errors.
✅ User-Agent Rotation / Proxies: Add support for anonymous scraping and anti-blocking measures.
✅ GUI Interface: Build a simple UI using Tkinter or PyQt to allow non-coders to run the tool.


 System Resource Monitor
Description
A Python desktop tool that shows **real-time CPU, RAM, Disk, and Network usage** using `psutil` and `matplotlib`. It provides visual insights into system performance through live plots, making it useful for debugging, learning, or general monitoring.

 Features
- Real-time CPU, memory, disk, and network monitoring
- Live graphical display using `matplotlib`
- Auto-refreshes system usage stats
- Lightweight and easy to use

Technologies
- Python 3.x
- psutil
- matplotlib

Getting Started
#Create and activate a virtual environment
```bash
python -m venv .venv

#Windows
.\.venv\Scripts\activate

#macOS/Linux
source .venv/bin/activate
Install dependencies
pip install -r requirements.txt

Run the app
python system_monitor.py
Requirements
psutil
matplotlib



Automated Backup Script with Logging


Description
A Python script that automates the process of backing up files/folders by compressing them into timestamped ZIP archives. It also logs each backup with file names and backup time for reference or audits.

Features
- Automatic ZIP backups of files or folders
- Timestamps added to filenames
- Log file (`backup.log`) with detailed info
- Simple and customizable script


Technologies
- Python 3.x (standard library only)


Getting Started

#Create and activate a virtual environment
```bash
python -m venv .venv

# Windows
.\.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate

No external dependencies required
Run the app
python backup_script.py
Requirements
Uses only built-in Python modules:
os, shutil, zipfile, datetime, logging

News Aggregator CLI App

Description
A Python CLI app that pulls the latest headlines from [NewsAPI](https://newsapi.org). Users can view top headlines, filter by news category, or search by keywords directly from the terminal.

Features
- View top news headlines
- Filter by categories: business, entertainment, sports, etc.
- Search by custom keyword
- Real-time updates from NewsAPI

Technologies
- Python 3.x
- requests
- NewsAPI

Getting Started

# Create and activate a virtual environment
```bash
python -m venv .venv

# Windows
.\.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate

Install dependencies
pip install -r requirements.txt

Run the app
python news_aggregator.py
Requirements
requests

✅ Also requires a free API key from https://newsapi.org.
 Replace your_api_key_here in the code with your actual API key.
20. Bug Tracker Web App

Description
A web-based bug/issue tracking application built with Python and Flask. Users can create, view, update, and delete bugs with assigned priorities, statuses, and assignees. It helps small teams track and manage software bugs efficiently.

Features
- Add, update, and delete bugs
- Assign status (Open, In Progress, Resolved)
- Set priority (High, Medium, Low)
- Assign to specific users
- View all bugs in a table layout

Technologies
- Python 3.x
- Flask
- SQLite (built-in)
- HTML, CSS (for UI)

Getting Started

# Create and activate a virtual environment
```bash
python -m venv .venv

# Windows
.\.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate

Install dependencies
pip install flask

Run the app
python app.py

Then open:
http://127.0.0.1:5000
Requirements
flask

SQLite will be auto-initialized (bug_tracker.db) on first run.


