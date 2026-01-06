# ☕ Kulhar Chuski – QR Cafe Menu System

A simple **QR-based cafe ordering system** inspired by desi cafés like *Kulhar Chuski*.
Customers scan a QR code placed on each table, view the menu, place orders, and the order
is instantly received on **Telegram** with **table number and bill total**.

---

## 🚀 Features

- 📱 QR Scan → Menu Opens
- 🪑 Automatic Table Number Detection
- 🍽 Desi Cafe Menu (Kulhar Chai, Maggi, Bun Maska, etc.)
- 📲 Orders Delivered to Telegram
- 🧾 Auto Bill Calculation
- 💯 Fully FREE (No server, no paid hosting)

---

## 🛠 Tech Stack (Free)

- **HTML + CSS + JavaScript**
- **GitHub Pages** – Free Hosting
- **Telegram Bot API** – Order Receiver

---

## 📂 Project Structure


---

## ⚙️ Setup Guide

### 1️⃣ Create Telegram Bot
- Open Telegram → `@BotFather`
- Use `/newbot`
- Copy the **BOT TOKEN**

### 2️⃣ Get Chat ID
- Send any message to your bot
- Open in browser:
- Copy the `"chat":{"id":...}` value

### 3️⃣ Update index.html
Replace:
```js
const BOT_TOKEN = "YOUR_BOT_TOKEN";
const CHAT_ID  = "YOUR_CHAT_ID";
