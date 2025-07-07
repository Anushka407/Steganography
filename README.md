## Steganography: Hiding Text in Image

EDUNET FOUNDATION |IBM SKILLSBULID| Cyber Security Virtual Internship 

## Project Overview:-
This project demonstrates image-based steganography using Python, where secret text messages are hidden inside digital images without changing their visible appearance. The technique uses the Least Significant Bit (LSB) method to conceal the information securely within the image pixels.

## Objective:-
To develop a simple and efficient system for embedding and extracting secret messages within images using steganography techniques to ensure data confidentiality and secure communication.


## Technologies and Tools Used
Python

Jupyter Notebook

Python Libraries:
Pillow (Image processing)

NumPy (Optional, for image manipulation)

##  How the Project Works

# Encoding Process:
Load the original image.

Convert the secret message into binary format.

Hide binary bits inside the image pixels using the Least Significant Bit (LSB) method.

Save the new image with the hidden message.

# Decoding Process:
Load the encoded image.

Extract the LSB bits from the image pixels.

Convert binary bits back to readable text to reveal the hidden message.

## Results
Input Image: Original image before embedding the message.

Output Image: Encoded image that visually appears the same.

Decoded Message: This is a secret message.

Observation: The input and output images look visually identical, ensuring the hidden data is not detectable by the human eye.

## Conclusion
This project successfully implemented image-based steganography using Python. The message was embedded without affecting the image's visible quality and was accurately retrieved. This technique is useful for secure, hidden communication.

## Future Scope
Extend the project to audio and video steganography.

Add encryption before embedding for enhanced security.

Develop a GUI for easier user interaction.

Use machine learning for steganalysis (detecting hidden data).

## References
Python Official Documentation

AICTE Cyber Security Internship Material
