Caesar Cipher Program
This project implements a Caesar Cipher tool for basic encryption and decryption of text messages. The Caesar Cipher, a well-known encryption technique, shifts each letter in a text by a certain number of positions in the alphabet. This program is interactive, allowing users to either encrypt or decrypt messages based on a shift value provided.

How the Code Works
Function caesar_cipher(text, shift):

This function is the core of the program, where each character in the input text is shifted by a specified shift amount.
If the character is alphabetical:
It calculates the new character based on its ASCII value, applying a shift within the bounds of lowercase or uppercase letters.
Non-alphabetical characters are directly added to the result without modification.
For decryption, the shift is simply negated to reverse the transformation.
Function main():

This is the user interface for the program, prompting the user to choose between encrypting or decrypting a message, or exiting the program.
Based on the choice, the program requests a message, shift value, and desired action (encrypt/decrypt).
If encryption is selected, it applies a positive shift to the message, and for decryption, it applies a negative shift.
The program also handles invalid inputs gracefully.
