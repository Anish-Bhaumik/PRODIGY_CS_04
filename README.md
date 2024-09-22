
# PRODIGY_CS_04: Simple Keylogger

## Overview
The Simple Keylogger is a basic tool designed to record and log keystrokes on a computer. This project demonstrates the implementation of keylogging functionality using Python, with a focus on ethical considerations and the importance of obtaining permissions when working with such tools.

## Ethical Considerations
Please note that keyloggers can pose serious privacy and security risks. Ensure you have explicit permission from users before running this tool. Unauthorized use may violate laws and ethical guidelines.


## Features
- Keylogging: Captures all keystrokes and saves them to a specified log file.
- User Instructions: Provides clear instructions for usage and how to exit the tool.
- ESC Key Functionality: Allows users to stop logging by pressing the 'ESC' key, enhancing control over the application.
## Requirements
- Python 3.x
- pynput library (install via 'pip install pynput')
## Installation

1. Clone this repository:

```bash
git clone https://github.com/Anish-Bhaumik/PRODIGY_CS_04.git
```
2. Navigate to the project directory:

```bash
cd PRODIGY_CS_04
```
3. Install the required library:

```bash
pip install pynput
```
    
## Usage
1. Run the keylogger:
```bash
python3 keylogger.py
```
2. The output will look like this:
```plaintext
 
  __   _   __ __   ___   _     ___     _  __  ___   __   __ _      __     __    __   ___   ___  
/' _/ | | |  V  | | _,\ | |   | __|   | |/ / | __|  \ `v' /| |    /__\   / _]  / _] | __| | _ \ 
`._`. | | | \_/ | | v_/ | |_  | _|    |   <  | _|    `. .' | |_  | \/ | | [/\ | [/\ | _|  | v / 
|___/ |_| |_| |_| |_|   |___| |___|   |_|\_\ |___|    !_!  |___|  \__/   \__/  \__/ |___| |_|_\ 

================================================================================
Welcome to the Simple Keylogger.
Instructions:
- This tool records keystrokes and saves them to a log file (e.g., 'keylog.txt').
- To stop typing and exit the keylogger, press the 'ESC' key, then select '2' to exit the program.
================================================================================
Select an option:
1. Start logging keystrokes.
2. Exit.
Enter your choice (1 or 2): 1
Logging started. Type anything you want; press 'ESC' to stop:
```
3. To Stop Logging: Press the 'ESC' key. The keylogger will pause, and you can then select 2 to exit the program.
4. Log File: Keystrokes will be saved in 'keylog.txt'.



## Credits
- Developed by: Anish Bhaumik
- Internship Program: Prodigy InfoTech - Cyber Security Internship Program