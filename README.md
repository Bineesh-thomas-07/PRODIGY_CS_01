# Caesar Cipher Program


This project implements a Caesar Cipher tool for basic encryption and decryption of text messages. The Caesar Cipher, a well-known encryption technique, shifts each letter in a text by a certain number of positions in the alphabet. This program is interactive, allowing users to either encrypt or decrypt messages based on a shift value provided.

# How the Code Works

# Function caesar_cipher(text, shift):
This function is the core of the program, where each character in the input text is shifted by a specified shift amount.
If the character is alphabetical:
It calculates the new character based on its ASCII value, applying a shift within the bounds of lowercase or uppercase letters.
Non-alphabetical characters are directly added to the result without modification.
For decryption, the shift is simply negated to reverse the transformation.

# Function main():

This is the user interface for the program, prompting the user to choose between encrypting or decrypting a message, or exiting the program.
Based on the choice, the program requests a message, shift value, and desired action (encrypt/decrypt).
If encryption is selected, it applies a positive shift to the message, and for decryption, it applies a negative shift.
The program also handles invalid inputs gracefully.

# Sample Interactions
# Encrypting a Message:
Enter choice: 1

Enter your message: hello

Enter the shift value (integer): 9

Do you want to 'encrypt' or 'decrypt' the message? encrypt

The encrypted message is: qnuux

# Decrypting a Message:
Enter choice: 1

Enter your message: qnuux

Enter the shift value (integer): 9

Do you want to 'encrypt' or 'decrypt' the message? decrypt

The decrypted message is: hello

# Usage
Run the program.
Choose 1 to encrypt/decrypt a message or 2 to exit.
Enter your message and shift value, then specify whether to encrypt or decrypt.


# How It Works
The program defines a caesar_cipher function to handle the character shifting, supporting both uppercase and lowercase characters, and preserving non-alphabet characters as they are. The main function provides a simple command-line interface for users to interact with the encryption and decryption processes.

Contributing
Contributions are welcome! Please submit a pull request with any improvements, additional features, or bug fixes.
