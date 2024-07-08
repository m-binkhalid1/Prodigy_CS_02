Image Encryption Tool
This project provides a simple graphical user interface (GUI) tool for encrypting images using a key. The tool is built using Python and Tkinter and allows users to select an image file (JPG or PNG) and encrypt it using a specified key.

Features
File Selection: Users can choose an image file to encrypt.
Key Input: Users can enter a numeric key for the encryption process.
Encryption: The selected image is encrypted using the entered key.
How It Works
Select an Image: Click the "Encrypt" button to open a file dialog and select an image file (JPG or PNG) from your computer.
Enter a Key: Input a numeric key in the provided text box.
Encrypt the Image: The image is read, and each byte is XORed with the provided key to produce the encrypted image. The original file is overwritten with the encrypted data.
Usage
Run the script.
Click on the "Encrypt" button.
Choose the image file you want to encrypt.
Enter the encryption key in the text box.
The selected image will be encrypted with the provided key.
Prerequisites
Python 3.x
Tkinter library (usually included with Python)
