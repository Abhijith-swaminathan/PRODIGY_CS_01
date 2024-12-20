Caesar Cipher - Python Program

Description

This Python program implements the Caesar Cipher encryption and decryption technique. The Caesar Cipher is a substitution cipher where each letter in the plaintext is shifted by a fixed number of positions (the "shift value") in the alphabet. The program allows users to encrypt and decrypt messages with a specified shift value.

Features
Encrypt: Encrypts a given plaintext using a specified shift value.
Decrypt: Decrypts a ciphertext back to its original form using the same shift value.
Customizable Shift: Users can input their desired shift value.
Handles Uppercase and Lowercase Letters: Maintains the case of letters during encryption and decryption.
Handles Non-Alphabetical Characters: Retains spaces, punctuation, and numbers without alteration.

How to Use
The program supports two operations:

Encryption: The user enters plaintext and a shift value to generate the encrypted message.
Decryption: The user provides ciphertext and the same shift value to retrieve the original plaintext.

Example Usage

Encrypting a Message:-

Enter operation: Encrypt
Enter shift value: 3
Enter plaintext: Hello, World!
Encrypted text: Khoor, Zruog!

Decrypting a Message:-

Enter operation: Decrypt
Enter shift value: 3
Enter ciphertext: Khoor, Zruog!
Decrypted text: Hello, World!

How It Works
Let’s take an example of encrypting the word "HELLO" with a shift of 3:

The letter H shifts to K.
The letter E shifts to H.
The letter L shifts to O.
The second L also shifts to O.
The letter O shifts to R.
The encrypted message becomes "KHOOO".

For decryption, each letter shifts backward by the same value:

The letter K shifts to H.
The letter H shifts to E.
The letter O shifts to L.
The second O shifts to L.
The letter R shifts to O.
The decrypted message becomes "HELLO".
