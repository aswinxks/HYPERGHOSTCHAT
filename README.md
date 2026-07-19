👻 HyperGhostChat - Beat All Security
End-to-End Encrypted Chat Application with Non-Extractable Keys & Per-Message Ratchet

https://img.shields.io/badge/version-1.0.0-purple
https://img.shields.io/badge/Firebase-Realtime-orange
https://img.shields.io/badge/WebCrypto-E2EE-blue
https://img.shields.io/badge/license-MIT-green

📌 Overview
HyperGhostChat is a cutting-edge, secure messaging platform built with military-grade encryption standards. It leverages Web Crypto API for true client-side encryption, ensuring that only you and your recipient can read messages — not even the server or Firebase admin can decrypt them.

🚀 Developed by: Aswinxks <img width="903" height="594" alt="image" src="https://github.com/user-attachments/assets/00426b13-aa99-49a5-82c4-28d8c8c63cbe" />
🌟 Features
✅ Real-time Messaging — Powered by Firebase Realtime Database

✅ Contact Management — Add, delete, and search contacts

✅ Friend Requests — Secure connection establishment

✅ Emergency Help — One-tap emergency messaging to Official Admin

✅ Admin Broadcasts — Official announcements with read receipts

✅ Import/Export Chats — Backup and restore conversations (JSON)

✅ Read Receipts — Track messages read by recipients

✅ Online Status — Real-time user presence indicators

✅ Responsive UI — Works seamlessly on mobile and desktop

✅ Dark Theme — Eye-friendly dark mode interface

✅ Plan & Subscription — Freemium model with verified badges

🛡️ Security Architecture
┌─────────────────────────────────────────────────────┐
│                    Client-Side                       │
│  ┌──────────────────────────────────────────────┐   │
│  │            Web Crypto API (ECDH)             │   │
│  │  - Generate Key Pair (Non-Extractable)       │   │
│  │  - Derive Shared Secret (ECDH)              │   │
│  │  - HKDF Ratchet (Per-Message Keys)          │   │
│  │  - AES-GCM Encryption/Decryption            │   │
│  └──────────────────────────────────────────────┘   │
│                        │                             │
│                        ▼                             │
│  ┌──────────────────────────────────────────────┐   │
│  │            IndexedDB Storage                  │   │
│  │  - Encrypted Message Store                   │   │
│  │  - Private Keys (Non-Extractable)           │   │
│  └──────────────────────────────────────────────┘   │
│                        │                             │
│                        ▼                             │
│  ┌──────────────────────────────────────────────┐   │
│  │         Firebase Realtime Database           │   │
│  │  - Public Keys (Only for Exchange)          │   │
│  │  - Encrypted Message Relay                  │   │
│  └──────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────┘


<img width="730" height="433" alt="image" src="https://github.com/user-attachments/assets/2e90fbba-fa23-451c-b043-525b70b9dc8f" />

🚀 Getting Started
Prerequisites
A modern browser (Chrome/Edge/Firefox recommended)

Firebase account (for backend setup)


