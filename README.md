# Password Manager

A secure and user-friendly password manager application built with Python and Tkinter.

## Features

- 🔒 Secure password storage in JSON format
- 🔑 Random password generation with customizable length
- �� Automatic password copying to clipboard
- 🔍 Search functionality to find stored passwords
- 📧 Email/username storage with passwords
- 🖥️ User-friendly GUI interface

## Requirements

- Python 3.x
- Tkinter (usually comes with Python)
- pyperclip

## Installation

1. Clone this repository or download the source code
2. Install the required package:
   ```bash
   pip install pyperclip
   ```

## Usage

1. Run the application:
   ```bash
   python main.py
   ```

2. To add a new password:
   - Enter the website name
   - Enter your email/username
   - Either enter your password or click "Generate Password" to create a secure one
   - Click "Add" to save the credentials

3. To search for a password:
   - Enter the website name
   - Click "Search" to retrieve the stored credentials

4. To generate a new password:
   - Click "Generate Password" to create a secure random password
   - The password will be automatically copied to your clipboard

## Security Notes

- Passwords are stored locally in a JSON file
- The application includes basic input validation
- Generated passwords include a mix of letters, numbers, and symbols

## File Structure

- `main.py` - Main application code
- `data.json` - Storage file for passwords
- `logo.png` - Application logo

## License

This project is open source and available for personal and educational use.

## Author

Created as part of the 100 Days of Code Python Pro Bootcamp.
