# Secure-Password-Manager: VAPOR VAULT

# Vapor Vault // 95 💾

A secure, offline-first password manager with a retro Windows 95 aesthetic.

## ⚡ Functionality
* **Password Generator:** Built-in cryptographic tool to generate high-entropy passwords with customizable length and character sets.
* **Strength Checker:** Real-time analysis of password complexity with visual feedback (Weak/Moderate/Strong).
* **Searchable Database:** Instantly filter through credentials with local-only search.
* **Change Password:** Securely update your Master Password without losing your data. (Re-encrypts the entire vault)
* **Encrypted Backup:** Export your entire vault to an encrypted JSON file for safe external storage.

## 🔒 Security Features
* **Encryption:** AES-256-GCM (Military Grade).
* **Key Derivation:** PBKDF2 (100,000 iterations) with unique salts.
* **Zero Knowledge:** Your master password is never stored or transmitted.
* **Offline Architecture:** No servers, no cloud databases, no tracking. The app runs entirely in your browser's local memory.

## 🛠️ Tech Stack
* React 19
* Vite (Custom Single-File Build)
* Tailwind CSS
* Web Crypto API (Native Browser Standard)

## 🚀 How to Run
1.  Download the `password_vault.html` from the **Releases** section.
2.  Disconnect from the internet (optional, for air-gap security).
3.  Open the file in your browser.

⚠️IMPORTANT: CLEARING BROWSER DATA OR COOKIES WILL PERMANENTLY DELETE YOUR VAULT. ALWAYS DOWNLOAD A BACKUP FIRST.
* Click the "BACKUP" button to download an encypted .json backup. Upload data later with the "RESTORE" button.

## ❓ Troubleshooting

**Q: I forgot my Master Password. How do I reset it?**
**A:** Because this is a Zero-Knowledge system, **there is no "Forgot Password" feature.** Your password *is* the encryption key. If you lose it, your data is mathematically unrecoverable.
* **Solution:** You must manually clear your browser's "Site Data" to wipe the vault and start over with a new database.

**Q: I clicked "Clear History" and my vault disappeared.**
**A:** This application runs entirely in your browser's `Local Storage`. If you wipe your browser data (cookies/site data), you wipe the vault.
* **Prevention:** Always use the **[ BACKUP ]** button to save a `.json` copy of your vault to your computer before clearing browser cache.
* **Recovery:** If you have a backup file, click the **[ RESTORE ]** button on the dashboard to reload your data.

**Q: The screen is blank when I open the file.**
**A:** Ensure that **JavaScript is enabled** in your browser settings. This application requires JavaScript to handle the encryption logic.

**Q: Can I use this on my phone?**
**A:** Yes. Since it is a single HTML file, it works on mobile browsers (iOS Safari, Android Chrome). However, file management (Backups/Restores) is generally easier on a desktop computer.

## 📄 License
MIT License - Free for personal and commercial use.
