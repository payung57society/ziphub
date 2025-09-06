# PAYUNG57 SOCIETY Store

Sebuah toko online sederhana untuk brand **PAYUNG57 SOCIETY**, dibuat dengan React + Vite + TailwindCSS.  
Bisa langsung di-deploy ke **Netlify**.

---

## 🚀 Cara Jalankan di Lokal

1. Clone repo atau extract ZIP ini.
2. Install dependency:
   ```bash
   npm install
   ```
3. Jalanin server dev:
   ```bash
   npm run dev
   ```
4. Buka di browser: http://localhost:5173

---

## 🌐 Deploy ke Netlify

1. Push project ini ke GitHub repo baru.
2. Masuk ke [Netlify](https://app.netlify.com/).
3. Klik **"Add new site" → "Import from GitHub"**.
4. Pilih repo ini, lalu atur:
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`
5. Klik deploy. Selesai! 🎉

---

## 🛒 Edit Produk

Buka file:
```
src/App.jsx
```
Cari bagian:
```js
const PRODUCTS = [
  {
    id: 'payung-figure-1',
    title: '1/7 Scale PAYUNG57 Figure - Banjir Sccater',
    price: 89.99,
    image: 'https://via.placeholder.com/420x560.png?text=PAYUNG57+Figure',
    description: 'Highly detailed painted PVC figure, 1/7 scale. Limited production run.',
  },
  // dst...
]
```
Tambah / edit produk sesuai kebutuhan.

---

## 📦 Teknologi
- React 18
- Vite
- TailwindCSS
- Deploy via Netlify

---

© 2025 PAYUNG57 SOCIETY
