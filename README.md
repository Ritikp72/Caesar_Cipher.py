# Caesar Cipher

A simple Python implementation of the **Caesar Cipher** encryption and decryption algorithm.

## Description

The Caesar Cipher is one of the earliest and simplest encryption techniques.  
It works by shifting the letters of the alphabet by a fixed number (called the shift value).  
This program allows you to:

- Encrypt text with a given shift value
- Decrypt text with a given shift value
- Handle both uppercase and lowercase letters

## Features

- Input any text to encrypt or decrypt
- Supports letters in both uppercase and lowercase
- Validates shift values (must be an integer between 1 and 25)

## Example

```python
from Caesar_Cipher import encrypt, decrypt

# Encrypt
encrypted_text = encrypt("freeCodeCamp", 3)
print(encrypted_text)

# Decrypt
decrypted_text = decrypt(encrypted_text, 3)
print(decrypted_text)
