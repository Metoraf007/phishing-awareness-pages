# Phishing Awareness Landing Page 🛡️

This project is a **single-page phishing simulation** designed to raise awareness about the risks of scanning unknown QR codes or joining untrusted Wi-Fi networks.

When users access the page (e.g., by scanning a QR code or connecting to a fake Wi-Fi network), they are presented with:
1. A **fake login screen**
2. A **loading spinner** (simulating verification)
3. A **security awareness message** warning about phishing risks

---

## 🔍 Purpose

This tool is part of an internal cybersecurity awareness campaign. It aims to:
- Simulate real-world phishing techniques (e.g., fake logins)
- Educate users immediately after interaction
- Reinforce safe practices like verifying QR codes and Wi-Fi networks

> ⚠️ **No credentials are collected or stored.**  
> This is a non-malicious simulation for educational purposes only.

---

## 🚀 How to Use

1. **Deploy via GitHub Pages** (free):
   - Upload `index.html` and `logo.png` to the root of the repository
   - Enable GitHub Pages in repo settings → Pages → Source → Main → Root
   - Copy the generated URL

2. **Generate a QR Code**:
   - Use any free QR generator (e.g., [qr-code-generator.com](https://www.qr-code-generator.com/))
   - Point it to the GitHub Pages URL

3. **Distribute**:
   - Print the QR code
   - Place in common areas or connect to fake/test Wi-Fi hotspots

---

## 📁 Files

| File         | Description                                      |
|--------------|--------------------------------------------------|
| `index.html` | The phishing simulation SPA (responsive, dark mode) |
| `logo.png`   | Optional company logo displayed on the page      |
| `README.md`  | This documentation file                          |

---

## 📱 Features

- Mobile-first responsive layout using Bootstrap 5
- Dark mode for realism and clarity
- Fake login form + awareness message
- Clean design with no external tracking or ads
- Zero backend: all logic handled client-side

---

## 🔐 Disclaimer

This project is intended for **internal educational use only**.  
If hosted publicly, be sure to:
- Clearly state that it's a simulation
- Avoid any misleading branding
- Ensure it cannot be misused or mistaken for a real login page

---

## 🧑‍💻 Maintainer

Developed by the Security Awareness Team  
Feel free to fork and adapt for your organization’s needs.

---

## 📸 Preview

![Preview Screenshot](preview.png) <!-- Add a screenshot if you like -->
