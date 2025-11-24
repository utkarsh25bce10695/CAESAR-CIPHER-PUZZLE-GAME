<h2># Message encrypt and decrypt app</h2>
<h2>Overview</h2>
This is a simple command-line application implemented in Python that allows users to encrypt and
decrypt messages using the classic Caesar Cipher algorithm. It features a basic login system to access
the cipher functionality.

The Caesar Cipher is one of the simplest and most well-known encryption techniques. It is a type of
substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of
positions down the alphabet.

<h2>Features</h2>
Secure Access: Requires a username and password to start the game.<br>
Encryption: Convert plaintext messages into encrypted cipher text using a shift key.<br>
Decryption: Convert cipher text back into the original message using the same shift key.<br>
Modulus Operation: Handles shift keys greater than 26 automatically ( key % 26 ).<br>
Default Credentials: To run the cipher program, you must use the hardcoded default credentials:<br>
  Field Value<br>
Username utkarsh                                            Password utkarsh@123

<h2>How to Run the Code
Prerequisites</h2>
You need to have Python installed on your system. This script was written and tested with Python 3.
Running the Script
1. Save the Code: Save the provided Python code into a file named, for example,
caesar_cipher.py

2. Open Terminal: Navigate to the directory where you saved the file.

3. Execute: Run the script from your terminal using the following command:
python caesar_cipher.py

4. Login: You will be prompted to enter the username and password (see Default Credentials above).

5. Use the Cipher: Once logged in, the program will guide you through encrypting or decrypting
your messages and specifying the shift key.
Code Structure

The core logic is contained within two main functions:
1. caesar_encrypt(message, key) : Encrypts the input message.
2. caesar_decrypt(encrypted_message, key) : Decrypts the cipher message.

Both functions use Python's built-in str.maketrans and translate methods from the string
module for efficient character shifting
