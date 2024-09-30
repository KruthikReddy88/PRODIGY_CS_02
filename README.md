# Simple Image Encryption Tool

## Description
This C-based tool allows users to encrypt and decrypt BMP images using simple pixel manipulation techniques. By applying a basic mathematical operation to the RGB values of each pixel, the program provides a straightforward method for protecting the contents of an image.

## Features
Image Encryption: Modifies pixel RGB values by adding a key, resulting in an encrypted image.
Image Decryption: Reverses the encryption process by subtracting the same key, restoring the original image.
Supports BMP Format: Works specifically with 24-bit uncompressed BMP images.

## How It Works
### Read BMP Image: 
The program reads the pixel data from a specified BMP image file.
### Encrypt/Decrypt Process:
During encryption, the program adds a specified key to each pixel's RGB values.
During decryption, it subtracts the same key from the pixel values.
### Write BMP Image: 
The modified pixel data is saved back to a new BMP image file.

## Usage
### Compile the Program: 
Make sure you have a C compiler installed (e.g., GCC). Compile the program using:
Copy code
### Run the Program: 
Execute the compiled program:

### Choose Operation: 
When prompted, enter:

E or e to encrypt an image.
D or d to decrypt an image.
Input and Output Files:

Input: The program expects an input image file named input_image.bmp.
Output: The encrypted image will be saved as encrypted_image.bmp, and the decrypted image will be saved as decrypted_image.bmp.

## Example

Simple Image Encryption Tool
Choose operation (E)ncrypt or (D)ecrypt: E
Image encrypted and saved as 'encrypted_image.bmp'.

## Requirements
C Compiler: GCC or any compatible C compiler.
BMP Images: The tool works specifically with uncompressed 24-bit BMP format images.

## Limitations
The program currently only supports uncompressed BMP files.
The key used for encryption and decryption must be the same.
Padding in BMP files is handled automatically, but ensure the input is a valid BMP file.

## License
This project is licensed under the MIT License.

