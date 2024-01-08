# Secure Messaging App

This Python application provides a graphical user interface (GUI) for securely sending and receiving encrypted messages using a basic XOR encryption algorithm. The Tkinter library is used for creating the GUI.

## Features

- Encrypts messages using XOR encryption with a randomly generated key.
- Decrypts messages with the correct key.
- Simple and user-friendly interface.

## Usage

1. Enter the message you want to send in the provided input field.
2. Click the "Send Message" button to encrypt the entered message. The encrypted message and the key are saved in separate files.
3. Click the "Take Data" button to decrypt the previously encrypted message. The decrypted message is displayed in a pop-up window.

## Files

- `encryption_script.py`: Encrypts user input and stores the result in a file.
- `decryption_script.py`: Decrypts messages from the file using the saved key.

## Prerequisites

- Python 3.x
- Tkinter library (usually included with Python installations)

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/secure-messaging-app.git
   ```
 Navigate to the project directory:
 
   ```bash
cd secure-messaging-app
   ```

Run the application:

   ```bash
python secure_messaging_app.py
   ```
