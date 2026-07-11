# 🔐 Encryption Visual Demo


# 🚀 Live Demo
👉 https://encryption-decryption-connection.netlify.app/


# 📖 Project Overview

This project visually explains how secure communication works on the Internet.

Instead of reading long theoretical explanations, users can interact with the simulation step by step.

The project is divided into two phases:

### Phase 1
TCP Connection Establishment

### Phase 2
Encryption & Secure Communication

- AES (Symmetric Encryption)
- RSA (Asymmetric Encryption)

# ✨ Features

## TCP 3-Way Handshake

- Client sends SYN
- Server replies with SYN-ACK
- Client sends ACK
- Connection status updates
- Activity log
- Sequence numbers
- Port numbers

## Symmetric Encryption (AES)

- Generate Secret Key
- Simulate Key Exchange
- Encrypt Message
- Send Ciphertext
- Decrypt Message
- Show decrypted message
- Simulate attacker stealing the shared key

## Asymmetric Encryption (RSA)

- Generate Public & Private Keys
- Share Public Key
- Encrypt using Public Key
- Decrypt using Private Key
- Public Key visualization
- Private Key remains secret

## Interactive UI

- Real-time animations
- Neon Cyber UI
- Activity Logs
- Network Simulation
- Responsive Layout
- Visual Encryption Process

# 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)

# 📂 Project Structure

```
Encryption-Visual-Demo/
│
├── index.html
├── style.css
├── script.js
├── assets/
│     ├── images
│     ├── icons
│
└── README.md
```

# 🔄 Project Workflow

```
Client
   │
   ▼
TCP 3-Way Handshake
   │
   ▼
Secure Connection Established
   │
   ▼
Choose Encryption Type
   │
   ├──────────────┐
   ▼              ▼
AES             RSA
   │              │
Encrypt        Generate Keys
   │              │
Send Data     Share Public Key
   │              │
Decrypt       Decrypt using Private Key
   │              │
   ▼              ▼
Secure Communication
```

---

# 🎯 Learning Objectives

This project helps users understand:

- How TCP establishes a connection
- Why encryption is required
- Difference between AES and RSA
- Secret Key vs Public Key
- Public Key Infrastructure
- Encryption & Decryption workflow
- Secure client-server communication

---

# 🔑 AES vs RSA

| Feature | AES | RSA |
|----------|-----|-----|
| Key Type | Same Key | Public & Private Keys |
| Speed | Fast | Slower |
| Security | Shared Secret | Key Pair |
| Best Use | Large Data Encryption | Key Exchange & Authentication |

---

# 👨‍💻 How to Run

Clone the repository

```bash
git clone https://github.com/YourUsername/Encryption-Visual-Demo.git
```

Go to the project folder

```bash
cd Encryption-Visual-Demo
```

Open

```
index.html
```

No installation required.


# 👤 Author
**Rishu Agarwal**
