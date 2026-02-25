# Capstone Project Idea Submission

## 1. Project Title

Automated Job Scraper & Alert System

-----

## 2. Project Description

The project is an Automated Job Scraper & Alert System that fetches live job listings from the RemoteOK public API, stores them in a local SQLite database, and allows users to search and filter jobs based on keywords, tags, or salary. It solves the problem of manually browsing multiple job boards by centralising relevant listings in one place and notifying users of new postings since their last login. The system supports multiple users, each with their own login, personal alert feed, and saved favourites list.

-----

## 3. Proposed Features

- Fetch live job listings from the RemoteOK public API
- Store jobs in a SQLite database with duplicate prevention
- Multi-user system with registration and login
- Password hashing for secure credential storage
- Search and filter jobs by keyword, tags, or salary range
- Alert system that flags new jobs per user since last login
- Save and view favourite jobs per user
- Export filtered results to a CSV file
- Clean job descriptions by stripping HTML tags using regex
- If time allows, I will integrate the Streamlit web interface for a more visual and interactive experience

-----

## 4. Python Concepts You Plan to Use

- Variables, data types, loops and conditionals
- Lists, dictionaries and sets for parsing and deduplication
- Functions for modular code structure
- File handling via CSV export
- OOP: classes and objects to model job listings and users
- Regular expressions for cleaning HTML from descriptions
- Database integration with SQLite3
- APIs via the requests library
- If time allows Streamlit for web UI

-----

## 5. Tools and Libraries

- `requests` — fetch data from RemoteOK API
- `sqlite3` — built-in, store job listings and user data
- `re` — built-in, regex for cleaning descriptions
- `csv` — built-in, export results
- `datetime` — built-in, timestamp fetched jobs
- `hashlib` — built-in, secure password hashing
- `os` — built-in, file and path management
- If time allows, `streamlit` — web interface