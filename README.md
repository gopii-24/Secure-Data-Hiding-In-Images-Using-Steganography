# Cryptic Images: Secure Data Embedding Using Steganography
This project demonstrates how to securely hide and retrieve a secret message in an image using a custom encryption-decryption algorithm. The code utilizes the concept of Least Significant Bit (LSB) encoding to embed a message and a passcode into an image. The image is then saved with the hidden data, and the user can retrieve the hidden message by entering the correct passcode.

# Overview

This Python-based project allows users to:

    Encrypt a secret message and passcode into an image using the LSB technique.
    Decrypt the hidden message from the image by providing the correct passcode.

The process involves encoding each character of the message into the least significant bits of the image's pixel data and retrieving the message upon successful passcode verification.

# Features

 1. Image Encryption:
    Embeds a secret message into the image and stores it as encryptedImage.jpg.

 2. Message Decryption:
    Extracts the hidden message from the encryptedImage.jpg once the correct passcode is entered.

 3. Custom Passcode Protection:
    Ensures that only authorized users can decrypt the message by validating a user-provided passcode.

 4. Image Processing with OpenCV:
    Uses the OpenCV library to manipulate and save the image after the encryption process.

# Requirements

 1. Python 3.x
 2. OpenCV (opencv-python package)
 3. mypic.jpg

# Installation
 
  1. Install the required libraries (if not already installed):
  2. pip install opencv-python
  3. Place your image (e.g., mypic.jpg) in the project directory.
