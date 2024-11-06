# Caesar Cipher Program

This is a simple Python implementation of the Caesar cipher, which can be used for both encryption and decryption of messages. The program allows you to input a message, choose a shift value, and select whether you want to encrypt or decrypt the message using the Caesar cipher technique.

## Features

- **Encryption**: Shift each letter in the message by a specified number of positions down the alphabet.
- **Decryption**: Reverse the shift to get the original message.
- **Handles both uppercase and lowercase letters**.
- **Non-alphabetic characters (spaces, punctuation, numbers, etc.) remain unchanged**.
- **Interactive command-line interface**.

## How it Works

The Caesar cipher works by shifting the letters of the alphabet by a certain number. For example, with a shift of 3:
- 'A' becomes 'D'
- 'B' becomes 'E'
- 'Z' becomes 'C'

For decryption, the program shifts the letters in the opposite direction, effectively undoing the encryption.

## Getting Started

### Prerequisites

To run the program, you need to have Python installed on your computer. The code is written in Python 3.x, so make sure you have Python 3 installed. You can check if Python is installed by running:

```bash
python --version
```

or

```bash
python3 --version
```

### Running the Program

1. Clone or download this repository to your local machine.
2. Open a terminal and navigate to the folder where you have saved the project files.
3. Run the following command to start the program:

```bash
python caesar_cipher.py
```

or

```bash
python3 caesar_cipher.py
```

4. The program will display an interactive menu where you can choose whether to encrypt or decrypt a message.

### Example Usage

- **Encryption**:
    - Message: `hello`
    - Shift value: `3`
    - Action: `encrypt`
    - Encrypted message: `khoor`

- **Decryption**:
    - Message: `khoor`
    - Shift value: `3`
    - Action: `decrypt`
    - Decrypted message: `hello`

## Code Overview

1. **caesar_cipher(text, shift)**:
    - This function takes in a string `text` and an integer `shift`, then shifts each letter of the string by the given amount. It handles both uppercase and lowercase letters and ignores non-alphabetic characters.

2. **main()**:
    - This function provides a simple command-line interface for the user to interact with the program. It allows the user to input a message, a shift value, and choose whether they want to encrypt or decrypt the message.

## Example Run

```
Welcome to the Caesar Cipher Program!

1. Encrypt/Decrypt a message
2. Exit
Enter choice: 1
Enter your message: hello
Enter the shift value (integer): 3
Do you want to 'encrypt' or 'decrypt' the message? encrypt
The encrypted message is: khoor

1. Encrypt/Decrypt a message
2. Exit
Enter choice: 2
Exiting the program.
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributions

Feel free to fork this repository, submit issues, and make pull requests. Contributions are welcome!

---

Thank you for using the Caesar Cipher Program! Happy coding! 🚀
```

### How to use this README:
- **Replace** the placeholders like `[LICENSE]` with your actual license file if you plan to include one, or remove the section if you don't.
- **Optional**: You can also add a "Screenshots" section if you have images of your program running or any additional features you would like to highlight.

Feel free to modify the README to suit your needs! It gives users clear instructions on how to run the program and provides a good overview of the project.
