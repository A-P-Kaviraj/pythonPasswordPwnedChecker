# Python Password Pawned Checker

## Description
`checkmypass.py` is a Python program designed to check if passwords have been compromised in data breaches. It utilizes the Pwned Passwords API to determine if a password has been exposed in known data breaches. The program takes multiple passwords as command-line arguments and checks each one for compromise.

## Table of Contents
- Installation
- Usage
- Output

## Installation
1. Clone the repository:
    ```
    git clone https://github.com/your-username/pythonPasswordPwnedChecker.git
    ```
2. Navigate to the project directory:
    ```
    cd pythonPasswordPwnedChecker
    ```
3. Install the required dependencies:
    ```
    pip install requests
    ```

## Usage
```bash
python checkmypass.py password1 password2 password3

```
## Output

```bash
Checking passwords...
Password 1: Compromised ❌
Password 1 was found 47705 times... you should probably change your password
Password 2: Secure ✅
Password 2 was NOT found, carry on!
Done!
```
