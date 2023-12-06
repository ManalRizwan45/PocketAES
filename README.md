# PocketAES
This repository contains a simplified implementation of the Advanced Encryption Standard (AES), referred to as PocketAES. The project provides three command-line interface (CLI) programs written in Python to demonstrate encryption, decryption, and individual stages of the PocketAES algorithm.

Programs Overview:

Encryption Demonstration:

Program: D1.py
Description: This program showcases the encryption process of a single block using PocketAES. It prompts the user for a plaintext block and encryption key, then displays the results after each encryption stage, including SubNibbles, ShiftRow, MixColumns, and GenerateRoundKeys.
Individual Stage Operation

Program: D2.py
Description: This program allows users to input a text block and key in hexadecimal format. It computes and displays the outputs of individual PocketAES encryption stages—SubNibbles, ShiftRow, MixColumns, and GenerateRoundKeys. Users can visualize how each stage contributes to the overall encryption process.
Text File Encryption and Decryption

Program: D3.py
Description: This program implements the ASCII text encryption and decryption scheme defined in Section B. It reads an encrypted text file (secret.txt), decrypts it using PocketAES, and outputs the result to a plaintext file (plain.txt). Users are prompted for the encryption key, and the program takes care of null padding present in the ciphertext.
