Overview

The File Encryption App is a Java Swing application that allows users to encrypt and decrypt files using AES encryption with CBC mode and PKCS5 padding.
Features

    Select a file to encrypt or decrypt using a file chooser dialog.
    Enter a password to encrypt or decrypt the selected file.
    Encrypt files, producing a new file with the ".encrypted" extension.
    Decrypt files previously encrypted with this program, producing a new file with the ".decrypted" extension.
    Log messages for successful encryption/decryption or errors.

Usage

    Launching the Application: Run the program by executing the main method in the FileEncryptionApp class.

    bash

    java FileEncryptionApp

    Selecting a File: Click the "Browse" button to select a file for encryption or decryption.

    Entering a Password: Enter a password in the "Password" field. This password will be used for encryption or decryption.

    Encrypting a File: Click the "Encrypt" button to encrypt the selected file. The encrypted file will be saved with a ".encrypted" extension in the same directory as the original file.

    Decrypting a File: Click the "Decrypt" button to decrypt a previously encrypted file. Select the encrypted file, and enter the same password used for encryption. The decrypted file will be saved with a ".decrypted" extension in the same directory as the encrypted file.

    Viewing Logs: Log messages for encryption/decryption operations or errors will be displayed in the text area.

Dependencies

    Java Development Kit (JDK) 8 or later

Notes

    Ensure that you remember the password used for encryption, as it is required for decryption. There is no way to recover the original file without the correct password.# File-encryptor
