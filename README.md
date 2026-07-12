# 🔧 Portal SPPG Jatian - Maintenance Page

Halaman maintenance untuk **portalsppgjatian.my.id** yang di-hosting di GitHub Pages.

## ✨ Fitur

- 🌙 Animasi modern dengan partikel & bulan
- ⚡ Loading screen yang halus
- 📊 Status layanan (Online/Maintenance)
- 🎨 Logo SPPG Jatian
- ⏳ Countdown 12 jam (persistent)
- 📱 Tombol WhatsApp: 081238176719
- 📱 Fully responsive

## 🚀 Deploy ke GitHub Pages

1. Buat repository baru di GitHub
2. Upload semua file di repository ini
3. Aktifkan GitHub Pages di Settings
4. Tambahkan custom domain `portalsppgjatian.my.id`
5. Konfigurasi DNS di Domainesia

## 🔄 Reset Countdown

Buka Console browser (F12) lalu ketik:
```javascript
localStorage.removeItem('maintenanceStartTime');
location.reload();
