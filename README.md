# 🔐 CipherLab — Cipher Encoder and Decoder

> An interactive browser-based tool to encode and decode messages using classic cryptography techniques.

![Cryptography](https://img.shields.io/badge/topic-cryptography-blue?style=flat-square)
![HTML CSS JS](https://img.shields.io/badge/built%20with-HTML%20%7C%20CSS%20%7C%20JS-blue?style=flat-square)
![No dependencies](https://img.shields.io/badge/dependencies-none-lightgrey?style=flat-square)

---

## What it does

CipherLab lets you type any message and instantly encode or decode it using five different cipher methods. It also shows you a visual cipher alphabet so you can see exactly how each letter is being transformed.

---

## Cipher methods included

| Cipher | How it works |
|--------|-------------|
| Caesar | Shifts each letter by a set number of positions. Used by Julius Caesar around 58 BC |
| ROT13 | A Caesar cipher with a fixed shift of 13. Encoding and decoding are the same operation |
| Atbash | Reverses the alphabet. A becomes Z, B becomes Y, and so on. Used in ancient Hebrew texts |
| Vigenere | Uses a keyword to apply a different shift to each letter. Much harder to crack than Caesar |
| Binary | Converts each character to 8-bit binary, the most basic level of how computers store text |

---

## How to run it

No installation or server needed:

```bash
git clone https://github.com/issamanisb-commits/cipherlab.git
cd cipherlab
open index.html
```

Just open `index.html` in any browser and it works immediately.

---

## Features

- Switch between encode and decode mode
- Adjustable shift slider for Caesar cipher
- Custom keyword input for Vigenere cipher
- Live cipher alphabet that highlights letters from your message
- Copy result button
- Works fully offline with no dependencies

---

## What I learned

- How classical encryption algorithms work mathematically
- Why simple ciphers like Caesar are easy to crack using frequency analysis
- Why the Vigenere cipher was considered unbreakable for 300 years
- How binary is the foundation of all modern digital communication
- The difference between encoding (transforming data) and encryption (securing data)

---

## Project context

Built as part of my application to the **INSA Cybersecurity Summer Camp** (Ethiopia). Understanding how historical ciphers work is the foundation of learning modern cryptography and encryption standards like AES and RSA.

---

## Author

**Issam Anis**
Aspiring cybersecurity professional | Ethiopia
Issamanisb@gmail.com
