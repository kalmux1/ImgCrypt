# ImgCrypt: Secure Your Images with Easy Encryption and Decryption

<p align="center">
  <img src="https://github.com/kalmux1/ImgCrypt/blob/main/Assets/Tool%20Image.png" alt="ImgCrypt GUI">
</p>

## Overview

ImgCrypt is a Python-based graphical tool for encrypting and decrypting image files. It uses a simple XOR-based encryption method to transform the image data, making it unreadable without the correct key. The tool provides a user-friendly GUI for selecting images, entering a key, and performing the encryption or decryption.

## ✨ Features

- **Image Encryption**: Encrypts image files using an XOR cipher with a user-defined key.
- **Image Decryption**: Decrypts the encrypted image files back to their original state.
- **Supports Multiple Formats**: Works with a variety of image formats, including `.jpg`, `.jpeg`, `.png`, `.gif`, `.bmp`, `.tiff`, `.webp`, and `.heif`.
- **GUI Interface**: Easy-to-use graphical interface built with Python's Tkinter library.

## 📚 Requirements

- Python 3.x
- Tkinter (usually included with Python installations)
- PIL (Python Imaging Library, also known as `Pillow`)

## 🚀 Getting Started

1. **Clone the repository**:
    ```bash
    git clone https://github.com/kalmux1/ImgCrypt.git
    cd ImgCrypt
    ```

2. **Install the dependencies**:
    ```bash
    pip install Pillow
    ```

3. **Run the application**:
    ```bash
    python imgcrypt.py
    ```

## 🛠️ How It Works

ImgCrypt utilizes a simple XOR cipher to encrypt and decrypt image files:

- **Encryption**: 
  - Reads the image file and converts it to a byte array.
  - Applies an XOR operation with the user-defined key to each byte in the image.
  - Saves the encrypted data back to the image file.
  - Displays an error if the image cannot be displayed (e.g., already encrypted).

- **Decryption**: 
  - Reads the encrypted image file and converts it to a byte array.
  - Applies the same XOR operation with the user-defined key to each byte in the image.
  - Saves the decrypted data back to the image file.
  - Reloads and displays the decrypted image.

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request. 

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📫 Contact

If you have any questions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/nitin-jaiswal1/) or open an issue on GitHub.

---

Encrypt and decrypt images with ImgCrypt! 🔒🖼️
