# 🔐 Image Encryption & Decryption Application

This project is a **Java-based desktop application** that allows users to securely encrypt and decrypt image files using the **AES (Advanced Encryption Standard)** algorithm. A simple GUI built with **Java Swing** enables users to enter a password, select an image, and perform encryption or decryption operations easily.

---

## 📌 Features

- 🔒 **AES Encryption** for image data
- 🧾 **SHA-256 password hashing** to generate secure keys
- 🖼️ **Supports any image file format**
- 💻 **User-friendly GUI** using Java Swing
- 🗂️ Encrypted images saved as `.enc`, decrypted images restored as `.jpg`

---

## 🛠️ Technologies Used

- Java (JDK 8+)
- Java Swing (for GUI)
- Java Cryptography Architecture (JCA)
- AES Cipher (`javax.crypto`)
- SHA-256 hashing (`java.security`)

---

## 🧠 How It Works

1. User inputs a password
2. Password is hashed with **SHA-256** to create a secret AES key
3. User selects an image file via `JFileChooser`
4. The image is read as a byte array
5. The app encrypts or decrypts the image using AES
6. Output is saved in the same directory

---

## 🖥️ GUI Overview

The application GUI includes:
- A password field for key input
- "Encrypt Image" and "Decrypt Image" buttons
- File chooser dialog for selecting images
- Dialog messages for success or failure feedback

---


### ✅ Prerequisites

- Java Development Kit (JDK 8 or later)
- Java-compatible IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans)

### 📦 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ImageEncryptionApp.git
