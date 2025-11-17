# MOBAN KBS Dashboard

Halaman intro animasi untuk MOBAN KBS Dashboard dengan redirect otomatis ke Google Apps Script.

## 🎨 Fitur

### Animasi
- ✨ **Logo Entry Animation** - Logo muncul dengan efek rotasi dan bounce
- 🌊 **Floating Effect** - Logo melayang dengan gerakan smooth
- 💫 **Glow Effect** - Efek cahaya berkedip di sekitar logo
- 📝 **Text Animation** - Teks muncul secara bergantian dengan fade in effect
- 🎭 **Particle System** - 30 partikel melayang dari bawah ke atas
- ⭕ **Background Circles** - Lingkaran animasi di background
- 📊 **Progress Bar** - Loading bar dengan animasi 5 detik

### Fungsionalitas
- ⏱️ **Auto Redirect** - Otomatis mengarahkan ke Google Apps Script setelah 5 detik
- 📱 **Responsive Design** - Tampilan optimal di semua ukuran layar
- 🎯 **Smooth Transitions** - Transisi halus antar animasi
- 🔄 **Dual Redirect Method** - Menggunakan meta refresh dan JavaScript setTimeout

## 🚀 Cara Menggunakan

1. **Download atau copy file HTML**
   ```bash
   git clone [repository-url]
   ```

2. **Buka file di browser**
   - Double click file `index.html`
   - Atau buka melalui web server

3. **Otomatis redirect**
   - Tunggu 5 detik untuk melihat animasi lengkap
   - Akan otomatis redirect ke Apps Script dashboard

## 🛠️ Kustomisasi

### Mengubah Durasi Redirect

Edit bagian ini di file HTML:

```html
<!-- Meta refresh (line 7) -->
<meta http-equiv="refresh" content="5; url=YOUR_URL">

<!-- JavaScript timeout (line ~290) -->
setTimeout(function() {
    window.location.replace('YOUR_URL');
}, 5000); // 5000ms = 5 detik
```

### Mengubah Warna Gradient

Edit CSS gradient di `body`:

```css
body {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Mengubah Teks

Edit HTML di section main content:

```html
<h1 class="title">MOBAN KBS</h1>
<p class="subtitle">Mempersiapkan Dashboard Anda</p>
```

### Mengubah Logo/Icon

Ganti SVG path di dalam `.logo`:

```html
<svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
    <path d="YOUR_SVG_PATH"/>
</svg>
```

## 📋 Timeline Animasi

| Waktu | Event |
|-------|-------|
| 0s | Logo muncul dengan rotasi |
| 0.5s | Title fade in |
| 0.8s | Subtitle fade in |
| 1.2s | Loading bar muncul |
| 5s | Auto redirect ke dashboard |

## 🎯 URL Redirect

Saat ini mengarah ke:
```
https://script.google.com/macros/s/AKfycbw8CL_9oohi20F-rRBQtiTNes-XDLswDfA4cgrX8LCTQZ3ak2CNEhAc0OQieshSf9TW/exec
```

Untuk mengubah URL tujuan, edit di 2 tempat:
1. Meta refresh tag di `<head>`
2. JavaScript `setTimeout` function

## 💻 Teknologi

- HTML5
- CSS3 (Animations, Gradients, Transforms)
- JavaScript (Vanilla)
- SVG Graphics

## 📱 Browser Support

- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Mobile Browsers

## 📝 Lisensi

© 2025 Moban KBS Dashboard. All rights reserved.

## 🤝 Kontribusi

Untuk kontribusi atau pertanyaan, silakan hubungi tim development.

---

**Dibuat dengan ❤️ untuk MOBAN KBS Dashboard**
