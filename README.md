# Password Locker
### Password locker is a simple python application that stores and generates passwords for different user accounts
### April,08, 2019
#### By **[John Victor Njoroge Karanja](https://github.com/twyfordsparks)**

## Description
Password Locker is an application that helps users generate and store passwords for their multiple social or online platforms accounts.
The password locker runs on the terminal and uses short codes to navigate through it.
When starting up the application, the user is met with the following shortcodes:

    1. cc - Creates a new credential
    2. dc - Displays credentials
    3. fc - Find a credential
    4. ex - Exit the application

## project's BDD
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display codes for navigation | **In terminal: $./password_locker.py** | Welcome, choose an option: ca-Create Account, li-Log In, ex-Exit |
| Display prompt for creating an account | **Enter: ca** | Enter your first name, last name and password |
| Display prompt for login in | **Enter: li** | Enter your account name and password |
| Display codes for navigation | **Successful login** | Choose an option: cc - Create Credential, dc - Display Credentials, copy - Copy Credential, ex - exit |
| Display prompt for creating a credential | **Enter: cc** | Enter the site name, your username and password |
| Display a list of credentials | **Enter: dc** | Prints a list of saved credentials |
| Display prompt for which credential to copy | **Enter: copy** | Enter the site name of the credential you wish to copy. |
| Exit application | **Enter: ex** | Exit the current navigation stage |

## Prerequisites
    - Python 3.6 required

## Set-up and Installation
    - Clone the Repository from https://github.com/twyfordsparks/locker.git
    -run this in the terminal
      git clone https://github.com/twyfordsparks/locker.git
    - Install python 3.6
    - Run `python3.6 run.py`

## Known bugs
No known errors as at the completion of the project but in case of any bug or error,kindly contact me through the email,johnvictor0002@gmail.com .

## Technologies used
    - Python 3.6

## Support and contact details
Contact me at johnvictor0002@gmail.com for any comments, reviews or advice.