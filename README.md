# Message Encrypt Decrypt

## Overview of the Project

This project is a Python-based command-line application designed to secure text messages using the classic Caesar Cipher algorithm. The tool ensures privacy by implementing a basic authentication system before granting access to the encryption and decryption features. Users can transform plain text into ciphertext and vice versa by specifying a numeric shift key, making it a useful tool for understanding fundamental cryptography concepts.

## Features

User Authentication: A built-in login mechanism that requires a specific username and password to access the application.

Caesar Cipher Encryption: Converts readable text into encrypted strings based on a user-defined numeric shift.

Caesar Cipher Decryption: Reverses the encryption process to retrieve the original message.

Customizable Shift Key: Allows users to choose any integer as the key for shifting characters.

Interactive Session: Features a while loop that allows users to process multiple messages without restarting the program.

Input Handling: Automatically normalizes inputs to lowercase to ensuring consistent processing.

## Technologies/Tools Used

Programming Language: Python 3

Standard Libraries: string (used for alphabet manipulation)

Interface: Command Line Interface (CLI)

## Steps to Install & Run the Project

Prerequisites: Ensure you have Python installed on your machine. You can check this by running python --version in your terminal.

Download: Download the message_encrypt.py file to your local machine.

Open Terminal: Open your Command Prompt (Windows) or Terminal (Mac/Linux).

Navigate: Use the cd command to navigate to the folder where you saved the file.

cd path/to/your/folder


Run: Execute the script using the following command:

python message_encrypt.py


Instructions for Testing

To successfully test the application, follow these steps:

Authentication:

Launch the program.

Username: Enter utkarsh

Password: Enter utkarsh@123

Note: Entering incorrect credentials will deny access and terminate the program.

Encryption Test:

When prompted "Do you want to decrypt or encrypt?", type: encrypt

Shift: Enter 3

Message: Enter hello

Expected Output: khoor

Decryption Test:

Choose to continue when asked.

Type: decrypt

Shift: Enter 3

Message: Enter khoor

Expected Output: hello

Exit:

When asked "Do you want to do it with another message?", type no to exit the application.
