# CryptX 🔐

CryptX is a simple yet powerful file and folder encryption and decryption tool using AES-256 (GCM).

## ✨ Features

- 🔒 **AES-256-GCM Encryption**
  - High-security authenticated encryption (confidentiality + integrity)
  - Password-based key derivation using PBKDF2 (with salt & iterations)

- 📁 **File and Folder Encryption**
  - Encrypt/Decrypt any file format
  - Encrypt folders (recursively) and auto-zip
  - Decrypt zipped folders and restore files

- 🔑 **Password Security**
  - Password is never stored
  - Minimum password length requirement
  - Key derived using PBKDF2 + random salt

- 🖥️ **Simple GUI (Tkinter)**
  - Easy-to-use layout
  - File/folder browsing
  - Real-time status and progress bar

- 🛠️ **Overwrite Protection**
  - Prompts before overwriting existing files
  - Optional overwrite toggle

- 📦 **Output Handling**
  - All output files saved in the original directory
  - Folder encryption creates `.zip` files with encrypted content

---

## 📄 Supported File Types

CryptX supports encryption of **any file type**:

| Category     | Examples                                  |
|--------------|-------------------------------------------|
| Documents    | `.txt`, `.docx`, `.pdf`, `.md`            |
| Images       | `.png`, `.jpg`, `.gif`, `.bmp`            |
| Media        | `.mp3`, `.wav`, `.mp4`, `.avi`, `.mkv`    |
| Archives     | `.zip`, `.rar`, `.7z`, `.tar.gz`          |
| Executables  | `.exe`, `.sh`, `.bat`, `.apk`             |
| Source Code  | `.py`, `.cpp`, `.js`, `.json`, `.xml`     |
| ...and more  | Any binary/text file is supported         |

> Folder encryption/decryption processes all valid files recursively and preserves folder structure when zipping and unzipping. CryptX treats files as raw binary data, so it does not depend on the file's extension. As a result, any file is supported for encryption and decryption.


## Installation
just download exe and run. it may trigger virus detection because of encryption logic.
<img width="703" height="531" alt="image" src="https://github.com/user-attachments/assets/7926fc11-7f5e-46ea-a791-29c9978b1531" />

