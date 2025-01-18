# hybrid-crypto-file-encryption
A Python implementation of hybrid file encryption using Kyber-like post-quantum cryptography and RSA. This project demonstrates secure file encryption and decryption for multiple users by combining the efficiency of symmetric key encryption (mock Kyber) with the robust key exchange capabilities of RSA.

Usage
Prerequisites

    Python 3.x
    Required libraries: pycryptodome, cryptography

Installation

Install the dependencies:

pip install pycryptodome cryptography

Steps to Run

    Create or provide a file to encrypt (e.g., sample_file.txt).
    Generate RSA keys for users.
    Encrypt the file using the provided script:
        The file is encrypted with a Kyber-like algorithm.
        The Kyber key is encrypted using RSA public keys for each user.
    Decrypt the file for a user by:
        Decrypting the Kyber key with the RSA private key.
        Using the Kyber key to decrypt the file content.

Example

The script provides a complete demonstration, including:

    RSA key generation for two users.
    File encryption for the users.
    File decryption by each user.

Output
After running the script, the original file content is securely encrypted and can only be decrypted by authorized users.
This repository is ideal for educational purposes or as a foundation for integrating hybrid cryptographic solutions in secure file sharing applications.
