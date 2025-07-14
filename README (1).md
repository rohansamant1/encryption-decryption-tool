
# 🔐 Encryption-Decryption Tool

A simple Python desktop GUI application that allows users to encrypt and decrypt messages using the **Vigenère cipher**. Built using Tkinter, the tool provides an easy-to-use interface for encoding and decoding text using a user-provided key.

---

## ✨ Features

- Encrypt messages with a custom key
- Decrypt messages using the correct key
- Simple and interactive GUI using Tkinter
- Reset and Exit options for usability
- Based on the Vigenère cipher with Base64 encoding

---

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **GUI Library**: Tkinter (built-in)
- **Encryption Logic**: Vigenère Cipher + Base64

---

## 🚀 Getting Started

### Prerequisites

- Python 3 installed on your system

### Running the App

1. **Clone the repository**  
   ```bash
   git clone https://github.com/rohansamant1/encryption-decryption-tool.git
   cd encryption-decryption-tool
   ```

2. **Run the application**
   ```bash
   python app.py
   ```

> If your file has a different name, replace `app.py` with the actual filename.

---

## 🧠 How It Works

1. **Enter a message** you want to encrypt or decrypt.
2. **Provide a key** that will be used to encode/decode the message.
3. **Select a mode**:
   - `e` for encryption
   - `d` for decryption
4. Click **Show Message** to get the result.
5. Use **Reset** to clear inputs or **Exit** to close the program.

---

## 🔐 Encryption Logic

The encryption uses a modified Vigenère cipher algorithm:
- Characters are transformed using modular arithmetic based on the key.
- The output is encoded using Base64 to ensure compatibility with URL-safe characters.

---


## 👤 Author

**Rohan Samant**  
[GitHub Profile](https://github.com/rohansamant1)

---

