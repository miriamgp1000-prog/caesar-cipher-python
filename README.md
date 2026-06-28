# 🔐 Caesar Cipher

My first Caesar cipher project in Python. A simple text encryption/decryption tool that shifts letters by a fixed number of positions in the alphabet.

## Features
- Encrypt and decrypt text
- Support for uppercase and lowercase letters
- Input validation (shift must be integer between 1-25)

## Usage
```python
from caesar import encrypt, decrypt

# Encrypt a message
encrypted = encrypt("Hello World", 5)
print(encrypted)  # Mjqqt Btwqi

# Decrypt a message
decrypted = decrypt(encrypted, 5)
print(decrypted)  # Hello World
