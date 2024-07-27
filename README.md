# PRODIGY_CS_04

The Simple Keylogger project is a basic software application designed to record keystrokes on a computer. This project aims to provide an educational tool for understanding how keyloggers work, as well as demonstrating the potential security risks they pose. It emphasizes responsible use and is intended solely for ethical purposes such as monitoring one's own computer usage or in a controlled, consensual environment for security testing.

# Features
Keystroke Logging: Records all keystrokes made on the keyboard, including letters, numbers, and special characters.
Stealth Mode: Operates in the background without disrupting the user's activities.
Log File Generation: Saves recorded keystrokes to a log file for later review.
Time Stamping: Adds timestamps to each keystroke entry to provide context on when each key was pressed.
Periodic Email Reports: Option to send recorded logs to a specified email address at regular intervals.
User-Friendly Interface: Simple interface to start, stop, and configure the keylogger settings.
Cross-Platform Compatibility: Runs on multiple operating systems, including Windows, macOS, and Linux.
# Implementation
Programming Language: Developed using Python for its simplicity and extensive library support.
Libraries Used:
pynput for capturing keystrokes.
smtplib for sending email reports.
datetime for adding timestamps.
Log Storage: Utilizes local storage to save log files in a secure and readable format.
Configuration File: Includes a configuration file for easy setup of email reports and log file settings.
# Security Considerations
Ethical Use: Intended for use on personal computers or in environments where monitoring is legally permitted and all parties are aware.
Data Privacy: Ensures logs are securely stored and transmitted to prevent unauthorized access.
Uninstallation: Provides a straightforward method for completely removing the keylogger and all its data from the system.
