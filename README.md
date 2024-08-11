Web-Based AES and RSA Encryption/Decryption Tool

Overview

This project is a web-based tool designed to perform AES (Advanced Encryption Standard) and RSA (Rivest–Shamir–Adleman) encryption and decryption operations. It provides a user-friendly interface for encrypting and decrypting data using symmetric and asymmetric encryption algorithms, and includes functionality for generating RSA key pairs.

Features
AES Encryption/Decryption: Encrypt and decrypt data using the AES symmetric encryption algorithm with a hardcoded key ('secretkey123').
RSA Encryption/Decryption: Encrypt and decrypt data using RSA asymmetric encryption. Users can input their RSA public and private keys for these operations.
RSA Key Pair Generation: Generate RSA key pairs with user-defined key lengths. The generated public and private keys are displayed for use in RSA encryption and decryption.
Technologies Used
CryptoJS: JavaScript library for AES encryption and decryption.
JSEncrypt: JavaScript library for RSA encryption, decryption, and key pair generation.
Usage Instructions
AES Encryption/Decryption:

Enter plaintext in the "Input Text" field.
Click the "Encrypt AES" button to encrypt the text. The encrypted output will be shown in the "AES Output" field.
To decrypt, paste the encrypted text into the "AES Output" field and click "Decrypt AES". The original text will appear in the "Input Text" field.
RSA Encryption/Decryption:

Enter plaintext in the "RSA Input" field.
Paste the RSA public key into the "Public Key" field and click "Encrypt RSA" to get the encrypted result in the "RSA Output" field.
To decrypt, paste the encrypted text into the "RSA Output" field and the RSA private key into the "Private Key" field. Click "Decrypt RSA" to reveal the original text in the "RSA Input" field.
RSA Key Pair Generation:

Specify the desired key length in the "Key Length" field (e.g., 2048 bits).
Click "Generate Key Pair" to generate and display the RSA public and private keys.