# ☕ WebGIS Peta Sebaran Coffeeshop Pekanbaru

Proyek tugas kelompok Sistem Informasi Geografis (SIG) — peta interaktif sebaran coffeeshop di Kota Pekanbaru menggunakan QGIS dan Leaflet.js.

## 🌐 Demo
👉 **[Lihat Peta Online](https://[username-kamu].github.io/webgis-coffeeshop-pekanbaru)**

## ✨ Fitur
- 🗺️ Peta interaktif dengan zoom & pan
- ☕ 100+ titik coffeeshop dengan popup info
- 🏘️ Layer batas kecamatan berwarna (15 kecamatan)
- 🛣️ Layer jaringan jalan Pekanbaru
- 🔍 Fitur pencarian nama kafe
- 📊 Panel statistik & legenda
- 📍 Toggle layer on/off
- 🌑 Basemap dark mode (CartoDB Dark)

## 🗂️ Struktur File
```
├── index.html          # Halaman utama WebGIS
├── css/                # Stylesheet Leaflet
├── js/                 # Library JavaScript
├── data/               # Data GeoJSON (layer)
├── legend/             # Gambar legenda
└── markers/            # Icon marker
```

## 🚀 Cara Hosting di GitHub Pages

1. Buat repository baru di GitHub (nama bebas, misal: `webgis-coffeeshop-pekanbaru`)
2. Upload semua file (drag & drop atau git push)
3. Masuk ke **Settings → Pages**
4. Source: pilih **"Deploy from a branch"**
5. Branch: pilih **`main`** → folder **`/ (root)`** → Save
6. Tunggu 1–2 menit → link akan muncul: `https://[username].github.io/[nama-repo]`

## 📚 Teknologi
- [QGIS](https://qgis.org) + Plugin QGIS2Web
- [Leaflet.js](https://leafletjs.com)
- [CartoDB Basemaps](https://carto.com/basemaps)
- Data BIG Indonesia (RBI 50K)
