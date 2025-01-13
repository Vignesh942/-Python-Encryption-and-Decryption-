# -Python-Encryption-and-Decryption-

Overview
This Python script demonstrates how to encrypt and decrypt a message using the cryptography.fernet module. It uses symmetric encryption, meaning the same key is used for both encryption and decryption.


Features
Key Generation: Generates a secret key using the Fernet.generate_key() method.
Encryption: Encrypts a user-entered message.
Decryption: Decrypts the encrypted message if the user provides the correct key.


How It Works
Key Generation: A random encryption key is generated using Fernet.generate_key().
Encryption: The user enters a message which is then encrypted using the generated key.
Decryption: The user is prompted to enter the key to decrypt the message. If the entered key matches the generated key, the message is decrypted.


License
This project is licensed under the MIT License.
