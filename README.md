# 🔐 PythonBruteForce

[![license](https://img.shields.io/github/license/canmenzo/PythonBruteForce)](LICENSE)
![python](https://img.shields.io/badge/python-3.6+-blue?logo=python&logoColor=white)
![status](https://img.shields.io/badge/status-learning%20project-lightgrey)

A small learning exercise: encrypt a message with a Caesar cipher, then recover it by brute-forcing every possible key. Archived, not maintained.

### ✨ Features
- 🔑 `caesar_encrypt.py` shifts a message by a key you choose and saves it to `encrypted_message.txt`
- 🔓 `caesar_decrypt.py` reads `encrypted_message.txt` and prints the result of all 52 possible shifts, so you can spot the readable one
- 🔤 Uses a single 52-letter alphabet (`A-Z` then `a-z`), so shifts wrap from uppercase into lowercase; other characters are left as-is
- 📄 `encrypted_message.txt` holds a sample ciphertext to try the decryptor on

### 🚀 Quick start
```bash
git clone https://github.com/canmenzo/PythonBruteForce.git
cd PythonBruteForce
python3 caesar_encrypt.py   # prompts for a message and a key, writes encrypted_message.txt
python3 caesar_decrypt.py   # prints every candidate decryption
```
Both scripts read and write `encrypted_message.txt` in the current directory. No dependencies beyond the standard library.

### 📄 License
MIT
