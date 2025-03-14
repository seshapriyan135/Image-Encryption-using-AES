# Image Encryption using AES

## Overview
This project implements an image encryption system using the Advanced Encryption Standard (AES) algorithm. It allows users to securely encrypt and decrypt image files, ensuring data confidentiality.

## Features
- Encrypt images using AES encryption
- Decrypt images securely
- Support for multiple image formats (JPG, PNG, BMP, etc.)
- User-friendly interface for encryption and decryption

## Technologies Used
- Python
- Cryptography Library (PyCryptodome/PyCrypto)
- OpenCV
- NumPy

## Installation
Clone the repository:
```bash
git clone https://github.com/seshapriyan135/Image-Encryption-using-AES.git
cd Image-Encryption-using-AES
```
Install Dependencies:
```bash
pip install -r requirements.txt
```
## Usage
1. Select an image file to encrypt.  
2. Run the encryption script to generate an encrypted image file.  
3. Use the decryption script with the correct key to restore the original image.  

## Encryption Process
- Convert image data into a byte stream.  
- Apply AES encryption with a secure key.  
- Store or transmit the encrypted image securely. 
