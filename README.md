Advanced Programming Techniques - CA ONE
Student Number: 20068781
Course: M.Sc. Cyber Security
Module: B9CY108 - Advanced Programming Techniques
Submission Date: December 13, 2025

Assignment Overview
This repository contains implementations for four programming problems demonstrating advanced programming concepts in C# and Python.

Project Structure
Programming-CA-1-20068781/
│
├── Question1_ContactBook/          # C# Contact Book Management System
│   ├── Program.cs
│   └── Screenshots/
│
├── Question2_FileExtension/        # C# File Extension Information System
│   ├── Program.cs
│   └── Screenshots/
│
├── Question3_ClientServer/         # Python Client-Server Application
│   ├── Que3_server.py
│   ├── Que3_client.py
│   ├── dbs_applications.db
│   └── Screenshots/
│
├── Question4_HotelScraper/         # Python Hotel Data Extraction System
│   ├── Que4.py
│   ├── hotel_data.csv
│   ├── seaside_paradise.html
│   ├── mountain_view_lodge.html
│   └── Screenshots/
│
└── CA_ONE_REPORT.pdf               # Complete assignment report
Technologies Used
Part I - C# Programming

Question 1: Object-oriented programming, List data structure, CRUD operations
Question 2: Dictionary data structure, file extension knowledge base

Part II - Python Programming

Question 3: TCP socket programming, SQLite database, JSON serialization
Question 4: BeautifulSoup (web scraping), CSV file handling, data analysis

How to Run
Question 1 & 2 (C#)

Open the .csproj file in Visual Studio or VS Code
Build and run the project
Follow the console menu instructions

Question 3 (Python - Client-Server)

First, start the server:

bash   python Que3_server.py

In a new terminal, run the client:

bash   python Que3_client.py

Follow the prompts to submit an application

Question 4 (Python - Web Scraping)
bashpython Que4.py
The program will generate hotel_data.csv with extracted data.

Dependencies
Python Requirements

beautifulsoup4
sqlite3 (built-in)
socket (built-in)
csv (built-in)
json (built-in)

Install required packages:
bashpip install beautifulsoup4

Key Features
Contact Book (Q1)

20 pre-populated contacts
Complete CRUD operations
Mobile number validation (9 digits)
Method overloading demonstration

File Extension System (Q2)

25+ file extensions database
Category-based browsing
Fast dictionary lookup
Graceful error handling

Client-Server Application (Q3)

TCP connection-oriented protocol
SQLite database persistence
UUID-based application numbers
Input validation with retry logic

Hotel Data Scraper (Q4)

HTML parsing with BeautifulSoup
Dynamic pricing calculations
Weekend and holiday premiums
CSV export with statistical analysis
