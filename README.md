Educational Info-Gathering Script (SAFE VERSION) 

⚠️ WARNING: SANITIZED FOR SAFETY
This is a non-functional, educational proof-of-concept.

The original script was a data-stealer, but this version has been completely sanitized to be 100% safe. It contains no malicious or privacy-violating code and uses mock data for all sensitive operations. It is safe to run and share publicly.

Project Overview
This repository demonstrates the structure and execution flow of an information-gathering script for learning defensive programming and understanding malware structure.

Key Safety Changes (What was Removed)
The code runs safely because all privacy-invasive functions were replaced with mock data:

Browser Passwords: Removed all decryption logic and file access (win32crypt, sqlite3, AES). Returns static mock data.

Unique Identifiers: Replaced all calls for MAC address and Global IP address with safe placeholders (00:00:00:00:00:00 and 0.0.0.0).

Clipboard Content: Disabled actual clipboard reading. Returns a safe placeholder string.

Private Data Access: The script does not read any private local files or keys.

How to Run

Prerequisites

Python 3.x

Python 

Execution
To run the safe, sanitized script:

python .\info_stealer.py

