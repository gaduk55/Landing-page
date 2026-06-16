# 🎰 MAWAR TOTO - Premium Landing Page

Landing page premium dengan desain modern dan animasi yang menarik untuk website resmi MAWAR TOTO.

## ✨ Fitur Utama

- 🎨 **Design Modern** - Tema dark dengan aksen merah yang elegan
- ⚡ **Responsive** - Optimal di semua ukuran layar (mobile, tablet, desktop)
- 🎬 **Animated Background** - Background dengan efek animasi grid bergerak
- ✨ **Glowing Effects** - Efek cahaya floating di background
- 📜 **Running Text** - Marquee dengan informasi terbaru
- 🔗 **Call-to-Action Buttons** - Tombol LOGIN dan DAFTAR yang eye-catching
- 🖼️ **Optimized Images** - Lazy loading dan error fallback untuk gambar

## 📁 Struktur File

```
landing-page/
├── index.html          # Main landing page
├── logo.png           # Logo MAWAR TOTO (upload file Anda)
├── banner.jpg         # Banner promo (upload file Anda)
├── .gitignore         # File yang diabaikan Git
└── README.md          # Dokumentasi ini
```

## 🚀 Cara Setup

### 1. Clone Repository
```bash
git clone https://github.com/gaduk55/landing-page.git
cd landing-page
```

### 2. Upload Gambar
- Tambahkan file `logo.png` ke folder root
- Tambahkan file `banner.jpg` ke folder root

**Rekomendasi ukuran:**
- Logo: 280x280px (PNG dengan transparent background)
- Banner: 520x300px atau lebih (JPG atau PNG)

### 3. Edit Konten
Buka `index.html` dengan text editor dan sesuaikan:
- Tagline (WEBSITE RESMI TERPERCAYA)
- Link LOGIN & DAFTAR
- Info minimal deposit
- Text marquee

### 4. Deploy ke GitHub Pages

1. Pergi ke repository settings: https://github.com/gaduk55/landing-page/settings
2. Scroll ke **Pages** section
3. Pilih **Deploy from a branch**
4. Pilih branch **main** dan folder **root (/)**
5. Klik **Save**

Landing page Anda akan live di: `https://gaduk55.github.io/landing-page/`

## 🎨 Customization

### Ubah Warna
Edit di section `<style>`:
```css
/* Dari merah (#ff0000) ke warna lain */
border:2px solid #ff0000;  /* Ubah sini */
box-shadow:0 0 15px red;   /* Ubah sini */
```

### Ubah Font
Ganti Orbitron dengan font lain:
```html
<link href="https://fonts.googleapis.com/css2?family=FONT_NAME&display=swap" rel="stylesheet">
```

### Ubah Link Buttons
```html
<a href="YOUR_LOGIN_URL" class="btn login">LOGIN</a>
<a href="YOUR_REGISTER_URL" class="btn daftar">DAFTAR</a>
```

## 🔧 Troubleshooting

### Gambar tidak muncul?
- Pastikan file `logo.png` dan `banner.jpg` di folder root
- Cek ukuran file (max 2MB recommended)
- Refresh browser (Ctrl+F5)

### Background animation tidak smooth?
- Kurangi `background-size` di CSS (dari 15px ke 20px)
- Atau disable animasi di slower devices

### Deploy ke GitHub Pages tidak working?
- Pastikan repository adalah **Public**
- Tunggu 1-2 menit setelah push
- Cek di Settings > Pages apakah sudah terdeployed

## 📱 Browser Support

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Mobile browsers ✅

## 💡 Tips

1. **Optimize Gambar** - Gunakan tools seperti TinyPNG untuk compress
2. **SEO** - Meta tags sudah included, jangan lupa update description
3. **Analytics** - Tambahkan Google Analytics untuk track traffic
4. **Mobile** - Test di mobile browser untuk memastikan responsive

## 📞 Support

Butuh bantuan? Hubungi atau buat issue di repository ini.

## 📄 License

Bebas digunakan untuk project pribadi maupun komersial.

---

**Created with ❤️ by Copilot** | Last updated: 2026
