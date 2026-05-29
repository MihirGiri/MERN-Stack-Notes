# Day 02 — 29 May 2026

## 🎯 Topic: Networks, Internet, Web & DNS

---

## 🔗 What is a Network?
A system where multiple devices (computers, laptops, phones, printers)
are interconnected to communicate, share resources, and pass messages.

---

## 📡 Types of Networks (By Physical Scale)

| Type | Full Form | Coverage |
|------|-----------|----------|
| **LAN** | Local Area Network | Room or Building |
| **MAN** | Metropolitan Area Network | Cities, Towns, States |
| **WAN** | Wide Area Network | Countries or Continents |
| **PAN** | Personal Area Network | Personal space (e.g. wireless headset ↔ phone) |

---

## 🌍 Internet vs WWW

| | Internet | WWW (World Wide Web) |
|---|---|---|
| What | Global "network of networks" | A service/subset of the Internet |
| Scale | Billions of devices worldwide | Interconnected documents & resources |
| Example | Connecting phone to Wi-Fi | Reading Wikipedia, streaming a video |

> 💡 Internet is the infrastructure. Web is a service that runs on it.

---

## 🏠 IP Address
- A **unique identification** for a machine on a network
- Just like a home address helps deliver a gift, an IP address helps
  machines locate and communicate with each other over the internet

### Find Your Own IP Address
```bash
# Windows
ipconfig

# Mac / Linux
ifconfig   or   ip a
```
Or simply Google → **"What is my IP"**

---

## 🌐 Browser & Browser Engine

| Browser | Engine |
|---------|--------|
| Google Chrome | Blink |
| Safari | WebKit |
| Mozilla Firefox | Gecko |

- **Browser** → Software to access websites (Chrome, Safari, Firefox)
- **Browser Engine** → The "brain" of the browser that executes code
  and renders the visual page on your screen

---

## 🔍 DNS, DNS Server & DNR

### The Problem
Browsers don't understand human-readable names like `www.facebook.com`
— they only understand IP addresses.

### The Solution

## 🔍 How DNS Works

```
www.facebook.com
       ↓
 DNS Server (DNR)
       ↓
 IP: 157.240.241.35
       ↓
Browser → Server
       ↓
  Page Loads ✅
```

| Term | Full Form | Role |
|------|-----------|------|
| **DNS** | Domain Name System | System for translating domain names |
| **DNS Server** | — | Server that handles the translation |
| **DNR** | Domain Name Resolution | The actual process of converting name → IP |

---

## 🖥️ Client-Server Example (Homework)
> If you open **Spotify** on your phone to play a song:
- **Client** → Your phone (requesting the song)
- **Server** → Remote database holding the music files
- Server processes the request and streams audio back to your phone ✅

---
