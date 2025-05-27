# 🔗 Dynamic QR Code Redirect Tool  
Live: [https://thinking-robot-co.github.io/dynamic-qr/](https://thinking-robot-co.github.io/dynamic-qr/)

## 📌 Project Overview

This project is a **Dynamic QR Code Redirect Platform** where users can:

- Log in to their dashboard.
- Create one "card" (a personal landing/dummy page hosted on this domain).
- Associate a custom redirect URL to their card.
- Share their card as a QR code or link.
- Update the destination URL anytime — the QR code remains unchanged.

This tool is ideal for dynamically changing the destination of a QR code without printing a new one.

---

## 🧠 How It Works

1. **User Authentication** – Users sign up or log in via Firebase Authentication.
2. **Card Creation** – Upon login, the user can create a single "card" page.
3. **Redirection Management** – Each card page is dynamically redirected to a URL stored in Firebase Firestore.
4. **QR Code Sharing** – Users can generate a QR code pointing to their card, which always redirects to their current target link.

---

## 💻 Tech Stack

| Component       | Technology        |
|----------------|-------------------|
| Frontend       | HTML, CSS, JavaScript |
| Hosting        | GitHub Pages       |
| Backend        | Firebase (Firestore, Auth, Hosting optional for redirection API if needed) |
| QR Code Gen    | JavaScript library (like `qrcode.js`) |

---

## 🛠 Features

- 🔐 Firebase authentication (Email/Password based login)
- 🌐 Hosted static frontend via GitHub Pages
- 🔄 Real-time redirect updates via Firestore
- 📱 QR code generator for dynamic links
- 👤 One card per user (can be expanded)

---

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/thinking-robot-co/dynamic-qr.git
cd dynamic-qr
