# Steganography--Hiding-message-in-an-Image

This repository contains a simple implementation of image steganography, a method of hiding secret data within an image. The project is implemented in Python.

## Project Description

The project includes two main parts: encoding a secret message into an image, and decoding the secret message from the image. The encoding process involves replacing pixel values in the image with ASCII values of the characters in the secret message. The decoding process involves extracting the ASCII values from the image and converting them back into characters to reconstruct the secret message.

## Dependencies

This project requires the following Python libraries:

- OpenCV (`cv2`): Used for reading and writing images.
- os: Used for opening the image file.

You can install these libraries using pip:

```bash
pip install opencv-python
```

## How to Use

1. Clone this repository.<br>
2. Run the encoding script and enter your secret message and password when prompted.<br>
3. The script will create a new image file with the secret message encoded into it.<br>
4. Run the decoding script and enter the correct password when prompted.<br>
5. The script will extract the secret message from the image and print it.<br>

## Limitations and Future Work

This is a basic implementation of steganography and lacks many features necessary for practical use, such as error checking, encryption, and efficient use of image data. Future work could include adding these features and improving the robustness and efficiency of the encoding and decoding processes.
