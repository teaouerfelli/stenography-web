# SRENOGRAPHY-WEB
## 1.Description

- **What the project does:**  
  This project is a web-based application that allows users to hide and retrieve secret messages within digital
  images using steganography and encryption techniques.

- **What problem it solves:**  
  It addresses the challenge of securely transmitting sensitive information without attracting attention. Instead of    sending visible encrypted messages, the information is concealed inside an image, making the communication appear     normal while keeping the content protected.

- **How it works (high level):**  
  The application uses Least Significant Bit (LSB) steganography to embed data into image pixels in a way that is       visually imperceptible. Before embedding, the message is encrypted using a password-based key derivation process.     During decoding, the hidden data is extracted from the image and decrypted using the same password to recover the     original message.
