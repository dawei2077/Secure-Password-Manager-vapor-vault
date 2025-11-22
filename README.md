# Secure-Password-Manager-vapor-vault

V A P O R V A U L T // 95
A military-grade, offline-first password manager with a Windows 95 aesthetic.

🔐 Why is this secure?
Unlike LastPass or 1Password, Vapor Vault is designed to run OFFLINE.
1.	AES-256-GCM Encryption: Industry standard encryption.
2.	Zero Knowledge: Your password never leaves your device.
3.	No Servers: There is no database to hack. Your data lives in your browser's local storage.
4.	Auditable: This project is open source. You can verify the code yourself.

💾 How to Use (The Secure Way)
Option 1: The "Fort Knox" Method (Recommended)
1.	Download the index.html file from the latest release.
2.	Move the file to a secure location (like a USB stick).
3.	Disconnect your internet.
4.	Open index.html in your browser (Incognito mode recommended).
5.	Your vault is now active.
Option 2: The "Paranoid" Method (Build from Source)
If you don't trust the pre-built file, build it yourself:
1.	Install Node.js.
2.	Clone this repo.
3.	Run npm install.
4.	Run npm run build.
5.	The secure file will be generated in the dist folder.

⚠️ Safety Rules
1.	Backups: Since there is no cloud, if you clear your browser data, you lose your passwords. Use the Export button frequently and save the JSON file to a USB stick.
2.	Extensions: Disable browser extensions while using the vault to prevent screen reading.

Built with React, Vite, and 90s Nostalgia.
