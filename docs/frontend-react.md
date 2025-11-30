# ⚛️ React.js Security Best Practices

Panduan mendalam untuk mengamankan aplikasi React.

## 1. Mencegah XSS (Cross Site Scripting)
React secara default melakukan *escaping* pada output, namun ada celah jika menggunakan metode yang salah.

### ❌ Jangan Lakukan Ini (Vulnerable)
Menggunakan `dangerouslySetInnerHTML` tanpa sanitasi.
```javascript
const UserComment = ({ text }) => {
  return <div dangerouslySetInnerHTML={{ __html: text }} />;
};
