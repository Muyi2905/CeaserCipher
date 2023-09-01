# Caesar Cipher Encryption and Decryption

This Python program allows you to encrypt and decrypt messages using the classic Caesar cipher algorithm. The Caesar cipher is a simple substitution cipher that shifts each letter in the plaintext by a fixed number of positions down or up the alphabet.


[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)


## Features

- **Encryption:** Encrypt your messages with a specified shift value.
- **Decryption:** Decrypt Caesar cipher encrypted messages with the correct shift value.
- **Support for Alphabetic Characters:** Works with both uppercase and lowercase letters, preserving non-alphabet characters.
- **User-Friendly Interface:** Provides a simple command-line interface for ease of use.

## How to Use

1. Clone this repository to your local machine.

2. Run the Python script:
    ```
    python caesar_cipher.py
    ```

3. Choose the operation:
   - Type `encode` to encrypt a message.
   - Type `decode` to decrypt a message.

4. Enter your message when prompted.

5. Enter the shift number (an integer) when prompted. The shift value should be between 0 and 25, and it can be any positive or negative integer. If the shift value is greater than 25, it wraps around the alphabet.

6. Get the result: The program will display the encrypted or decrypted message.

7. If you wish to use the program again, type `yes` when asked. To exit, type `no`.

## Example Usage

- To encrypt a message: Choose `encode`, input your message, and specify the shift value.
- To decrypt a message: Choose `decode`, input the encrypted message, and specify the correct shift value used for encryption.

## Contributions

Contributions and suggestions are welcome! Feel free to fork this repository and submit pull requests to improve the program.

## License

This project is open-source and available under the [MIT License](LICENSE).

---


