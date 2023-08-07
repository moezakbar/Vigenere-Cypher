# Vigenere-Cypher
A project in python
Project Description: Vigenère Cipher Encryption Program

This project showcases a Python program that implements the Vigenère Cipher encryption technique, an improvement over the classic Caesar Cipher. The program interacts with the user, prompting them to enter plaintext and a keyword. It then displays the Vigenère encrypted form of the plaintext on the screen.

Key Features:

Vigenère Table Creation: The program utilizes a function to construct a Vigenère table, represented as a dictionary, containing alphabets as keys and lists of corresponding alphabets as values. This table is used for encryption purposes.
Input Validation and Formatting: The program efficiently handles user input, converting all plaintext and keyword characters to uppercase and eliminating any non-alphabetic characters from the plaintext.
Keyword Alignment: The program aligns the keyword with the plaintext to match their lengths. If the keyword is shorter than the plaintext, it repeats the keyword to match the plaintext's length. Conversely, if the keyword is longer than the plaintext, it truncates the excess.
Vigenère Encryption: Using the Vigenère table, the program encrypts the plaintext using the provided keyword. For each character in the plaintext, the corresponding encrypted character is determined by finding the intersection of the plaintext character's row and the keyword character's column in the Vigenère table.
