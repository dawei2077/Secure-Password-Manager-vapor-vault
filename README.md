# Secure-Password-Manager: VAPOR VAULT

# Vapor Vault // 95 💾

A secure, offline-first password manager with a retro Windows 95 aesthetic.

## ⚡ Functionality
* **Password Generator:** Built-in cryptographic tool to generate high-entropy passwords with customizable length and character sets.
* **Strength Checker:** Real-time analysis of password complexity with visual feedback (Weak/Moderate/Strong).
* **Encrypted Backup:** Export your entire vault to an encrypted JSON file for safe cold storage (USB backup).
* **Searchable Database:** Instantly filter through credentials with local-only search.

## 🔒 Security Features
* **Encryption:** AES-256-GCM (Military Grade).
* **Key Derivation:** PBKDF2 (100,000 iterations) with unique salts.
* **Zero Knowledge:** Your master password is never stored or transmitted.
* **Offline Architecture:** No servers, no cloud databases, no tracking. The app runs entirely in your browser's local memory.

## 🛠️ Tech Stack
* React 18
* Vite (Custom Single-File Build)
* Tailwind CSS
* Web Crypto API (Native Browser Standard)

## 🚀 How to Run
1.  Download the `index.html` from the **Releases** section.
2.  Disconnect from the internet (optional, for air-gap security).
3.  Open the file in your browser.

## 📄 License
MIT License - Free for personal and commercial use.
