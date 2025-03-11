# Overview  
This Python script provides a simple yet secure way to **encrypt and decrypt messages** using the `cryptography.fernet` module. It employs **symmetric encryption**, meaning the same key is used for both encryption and decryption.  

## Features  
- **Key Generation**  
  Securely generates an encryption key using `Fernet.generate_key()`.  

- **Message Encryption**  
  Encrypts a user-provided message for secure storage or transmission.  

- **Message Decryption**  
  Decrypts the encrypted message when the correct key is provided.  

## How It Works  
1️) **Key Generation**  
   A random encryption key is generated using `Fernet.generate_key()`.  

2️) **Encryption**  
   The user inputs a message, which is then encrypted using the generated key.  

3️) **Decryption**  
   The user enters the key to decrypt the message. If the key matches, the message is successfully decrypted.  

## License  
This project is licensed under the **MIT License**.
