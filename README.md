# one-time-pad-simulator
A simple Python-based One-Time Pad (OTP) encryption simulator that demonstrates key generation, XOR-based encryption, and decryption. Includes an interactive terminal interface for learning how OTP works.
# One-Time Pad Encryption Simulator

This project is a simple Python-based simulator that demonstrates how the **One-Time Pad (OTP)** encryption method works. OTP is an encryption technique that uses a random key equal in length to the plaintext and combines it using XOR operations. When used correctly, OTP provides *theoretical perfect secrecy*.

## 🔐 Features
- Generates a truly random key using `os.urandom`
- Encrypts plaintext using XOR (One-Time Pad)
- Decrypts ciphertext back to the original message
- Displays key and ciphertext in hexadecimal format
- Interactive terminal interface
- Validates key and plaintext lengths
- Supports all text, including Unicode characters

## 📁 How It Works
1. User enters a plaintext message  
2. A random key (same length in bytes) is generated  
3. Plaintext and key are XORed to create ciphertext  
4. The program decrypts the ciphertext using the key  
5. Results are displayed in a clear, educational format  

## ▶️ Running the Program

Make sure you have Python installed, then run:

```bash
python otp_simulator.py
Plaintext: Hello
Key (hex): 9a1f0c...
Ciphertext (hex): f43b5a...
Decrypted message: Hello
