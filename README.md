# Simple Ciphers

This project implements a GUI-based program for encrypting and decrypting text files of any size containing Russian text using two classical cipher algorithms:
- `Columnar Transposition Cipher`: Utilizes a single user-provided keyword to rearrange text columns, ignoring non-alphabetic characters and preserving only Russian letters.
- `Vigenère Cipher`: Employs a self-generating key based on a user-provided input, applied to Russian text while ignoring non-alphabetic symbols. The program accepts a user-defined key via a graphical interface, processes only the specified alphabet, and outputs encrypted/decrypted files. It ensures robust handling of large files and maintains text integrity.
