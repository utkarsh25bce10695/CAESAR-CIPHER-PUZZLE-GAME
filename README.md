# Message Encrypt Decrypt

## Overview of the Project

This project is a Python-based command-line application designed to secure text messages using the classic Caesar Cipher algorithm. The tool ensures privacy by implementing a basic authentication system before granting access to the encryption and decryption features. Users can transform plain text into ciphertext and vice versa by specifying a numeric shift key, making it a useful tool for understanding fundamental cryptography concepts.

## Features
<ul>
<li> User Authentication: A built-in login mechanism that requires a specific username and password to access the application. </li>

<li> Caesar Cipher Encryption: Converts readable text into encrypted strings based on a user-defined numeric shift. </li>

<li> Caesar Cipher Decryption: Reverses the encryption process to retrieve the original message. </li>

<li> Customizable Shift Key: Allows users to choose any integer as the key for shifting characters. </li>

<li> Interactive Session: Features a while loop that allows users to process multiple messages without restarting the program. </li>

<li> Input Handling: Automatically normalizes inputs to lowercase to ensuring consistent processing. </li>
</ul>

## Technologies/Tools Used
<ul>
<li> Programming Language: Python 3 </li>

<li> Standard Libraries: string (used for alphabet manipulation) </li>

<li> Interface: Command Line Interface (CLI) </li>
</ul>

## Steps to Install & Run the Project
<ul>
<li> Prerequisites: Ensure you have Python installed on your machine. You can check this by running python --version in your terminal. </li>

<li> Download: Download the message_encrypt.py file to your local machine. </li>

<li> Open Terminal: Open your Command Prompt (Windows) or Terminal (Mac/Linux). </li>

<li> Navigate: Use the cd command to navigate to the folder where you saved the file.</li>

cd path/to/your/folder


<li> Run: Execute the script using the following command: </li>

python message_encrypt.py
</ul>

## Instructions for Testing

To successfully test the application, follow these steps:

1. ## Authentication:
<ul>
<li> Launch the program.</li>
<li> Username: Enter utkarsh</li>
<li> Password: Enter utkarsh@123</li>
</ul>
**Note: Entering incorrect credentials will deny access and terminate the program.**

2. ## Encryption Test:
<ul>
<li> When prompted "Do you want to decrypt or encrypt?", type: encrypt</li>
<li> Shift: Enter 3</li>
<li> Message: Enter hello</li>
<li> Expected Output: khoor</li>
</ul>  

3. ## Decryption Test:
<ul>
<li> Choose to continue when asked.</li>
<li> Type: decrypt</li>
<li> Shift: Enter 3</li>
<li> Message: Enter khoor</li>
<li> Expected Output: hello</li>
</ul>

4. ## Exit:
<ul>
<li> When asked "Do you want to do it with another message?", type no to exit the application.</li>
</ul>
