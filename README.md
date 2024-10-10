# PRODIGY_CS_02

# Simple Image Encryption Tool

## Description
This program allows users to encrypt and decrypt BMP image files using a simple pixel manipulation technique. It shifts the RGB values of each pixel based on a specified key, ensuring that the resulting image appears altered when encrypted and can be restored when decrypted.

## Features
- Encrypt BMP images by shifting pixel RGB values.
- Decrypt previously encrypted BMP images.
- Maintains image integrity by handling padding appropriately.

## Requirements
- C++ compiler (e.g., g++, clang++)
- Standard C++ libraries

## How to Compile
1. Save the code in a file named `image_encryption.cpp`.
2. Open a terminal and navigate to the directory where the file is saved.
3. Compile the program using the following command:
   ```bash
   g++ image_encryption.cpp -o image_encryption
   ```

## How to Run
After compiling, you can run the program with:
```bash
./image_encryption
```

## Usage
1. The program will prompt you to choose whether to encrypt or decrypt an image. Enter `E` for encryption or `D` for decryption.
2. The program will attempt to read an image file named `input_image.bmp`. Ensure this file is present in the same directory as the executable.
3. The encrypted image will be saved as `encrypted_image.bmp`, and the decrypted image will be saved as `decrypted_image.bmp`.

## Example
### Encrypting
```
Simple Image Encryption Tool
Choose operation (E)ncrypt or (D)ecrypt: E
Image encrypted and saved as 'encrypted_image.bmp'.
```

### Decrypting
```
Simple Image Encryption Tool
Choose operation (E)ncrypt or (D)ecrypt: D
Image decrypted and saved as 'decrypted_image.bmp'.
```

## Limitations
- The program only supports BMP image files.
- The encryption is based on a fixed key value; consider using more complex algorithms for enhanced security.

## License
This project is open-source and available for personal or educational use.

