# Caesar Cipher Program

This Python program allows users to encrypt and decrypt text using the Caesar Cipher algorithm. The Caesar Cipher is a type of substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet.

## Features
- Encrypts text by shifting letters by a specified value.
- Decrypts text by reversing the shift.
- Handles both uppercase and lowercase letters.
- Leaves non-alphabetic characters unchanged.

## How to Use

1. **Clone or Download the Repository**
   - Clone the repository using `git clone <repository_url>` or download the ZIP file and extract it.

2. **Run the Program**
   - Open a terminal or command prompt.
   - Navigate to the directory containing the program file.
   - Run the program using the command:
     ```bash
     python caesar_cipher.py
     ```

3. **Input Your Choices**
   - When prompted, type `encrypt` to encrypt a message or `decrypt` to decrypt a message.
   - Enter the message you want to encrypt or decrypt.
   - Enter the shift value (an integer).

4. **View the Result**
   - The program will display the encrypted or decrypted message based on your input.

## Example

### Encrypting a Message
```
Type 'encrypt' to encrypt or 'decrypt' to decrypt: encrypt
Enter your message: Hello, World!
Enter shift value: 3
Encrypted message: Khoor, Zruog!
```

### Decrypting a Message
```
Type 'encrypt' to encrypt or 'decrypt' to decrypt: decrypt
Enter your message: Khoor, Zruog!
Enter shift value: 3
Decrypted message: Hello, World!
```

## Code Explanation

### Functions
- `encrypt(text, shift)`: Encrypts the input text by shifting each letter by the specified shift value.
- `decrypt(text, shift)`: Decrypts the input text by shifting each letter back by the specified shift value.
- `main()`: Handles user input and calls the appropriate function based on the user's choice.

### Logic
- The program checks if each character is an alphabet letter.
- It shifts the character by the specified value, wrapping around the alphabet if necessary.
- Non-alphabetic characters remain unchanged.

## Requirements
- Python 3.x

## License
This project is licensed under the MIT License.
