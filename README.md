# 🛡️ Awesome Web Security Roadmap & Checklist

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/tirtasadewa285/awesome-web-security-roadmap?style=social)
![GitHub forks](https://img.shields.io/github/forks/tirtasadewa285/awesome-web-security-roadmap?style=social)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

**Panduan Lengkap (Roadmap) Keamanan Web untuk Developer React, Node.js, & PHP.**
*Bridging the gap between Fullstack Development and Cyber Security.*

[English](./README.md) | [Bahasa Indonesia](./README.md)

</div>

---

## 📖 About / Tentang
Repositori ini dirancang sebagai referensi cepat ("Cheat Sheet") dan panduan mendalam bagi Fullstack Developer yang ingin menulis kode yang aman (Secure Coding).

Kami fokus pada mitigasi kerentanan **OWASP Top 10** pada teknologi yang paling banyak digunakan di Indonesia: **React.js, Node.js (Express), dan PHP**.

---

## 🗂️ Table of Contents (Daftar Isi)

### 1. ⚛️ Frontend Security (React.js)
Bagaimana mengamankan Client-side dari serangan XSS dan pencurian data.
> **[👉 BACA PANDUAN LENGKAP REACT DI SINI](./docs/frontend-react.md)**

*Highlight:*
- [ ] **Sanitization:** Mencegah DOM-based XSS.
- [ ] **Auth Storage:** Cookie HttpOnly vs LocalStorage.
- [ ] **Dependencies:** Audit library pihak ketiga.

### 2. 🟢 Backend Security (Node.js)
Teknik hardening untuk server berbasis JavaScript/Express.
> **[👉 BACA PANDUAN LENGKAP NODE.JS DI SINI](./docs/backend-node.md)**

*Highlight:*
- [ ] **Helmet:** Secure HTTP Headers.
- [ ] **Rate Limiting:** Mencegah DDoS & Brute Force.
- [ ] **NoSQL Injection:** Sanitasi query MongoDB.

### 3. 🐘 Backend Security (PHP)
Praktik modern (PHP 8+) untuk mencegah serangan klasik.
> **[👉 BACA PANDUAN LENGKAP PHP DI SINI](./docs/backend-php.md)**

*Highlight:*
- [ ] **SQL Injection:** Wajib Prepared Statements (PDO).
- [ ] **Session Fixation:** Manajemen sesi yang aman.
- [ ] **File Uploads:** Validasi ketat untuk upload file.

---

## 🛠 Tools & Resources
Alat bantu wajib untuk Fullstack Developer:

| Tool | Fungsi | Tipe |
| :--- | :--- | :--- |
| **OWASP ZAP** | Scanner keamanan otomatis untuk web app | DAST |
| **Burp Suite** | Intercept & modify request (Manual Testing) | Proxy |
| **Snyk** | Mencari celah keamanan di dependencies (npm/composer) | SCA |
| **SonarQube** | Analisis kualitas kode & security hotspot | SAST |
| **Helmet.js** | Middleware keamanan untuk Express/Node | Library |

---

## 🤝 Contribution
Ingin berkontribusi? Silakan baca [CONTRIBUTING.md](./CONTRIBUTING.md).

## ⚠️ Disclaimer
Informasi di sini untuk tujuan edukasi. Baca [DISCLAIMER.md](./DISCLAIMER.md) selengkapnya.

<div align="center">
Made with ❤️ by <a href="https://github.com/tirtasadewa285">Tirta Sadewa</a>
</div>
