# Steganography

## Overview
StegnoEncryption combines *steganography* and *encryption* to securely hide sensitive information within images, ensuring data confidentiality and protection from unauthorized access.

## What is Steganography?
Steganography is the practice of concealing information within another medium, such as an image, audio file, or text. Unlike encryption, which makes data unreadable without a key, steganography hides the very existence of the message. This technique is widely used for secure communication, watermarking, and digital rights management.

## Features
- Encrypts and embeds messages in images.
- Extracts and decrypts hidden messages.
- Supports various image formats (PNG, JPG).
- Uses *OpenCV* for image processing.
- Simple command-line interface.

## OpenCV Library
This project utilizes the *OpenCV* library for handling image processing tasks such as reading, modifying, and saving images. OpenCV allows efficient manipulation of image pixels, which is essential for embedding and extracting hidden messages without significantly altering the visual quality of the image.
