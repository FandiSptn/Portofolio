# Portfolio Fandi Septian

Portfolio web modern dan responsif dengan animasi menarik.

## 📋 Petunjuk Setup

### 1. Tambahkan Foto Profile

Letakkan file foto profile Anda dengan nama `profile.jpg` di folder yang sama dengan `index.html`.

**Format file:**
- Format: JPG, PNG, atau WebP
- Ukuran rekomendasi: 400x400px atau lebih besar (square aspect ratio lebih bagus)
- Ukuran file: Max 2MB untuk performa optimal

**Opsi lain:**
Jika ingin mengubah nama file, edit baris ini di `index.html`:
```html
<img src="profile.jpg" alt="Fandi Septian" ...
```

Ganti `profile.jpg` dengan nama file foto Anda.

### 2. Update Informasi Contact

Edit bagian social links di section contact untuk menambahkan URL yang benar:

**Facebook:**
```html
<a href="https://facebook.com/username-anda" class="social-link" title="Facebook">
```

**Instagram:**
```html
<a href="https://instagram.com/username-anda" class="social-link" title="Instagram">
```

**Email:**
```html
<a href="mailto:email-anda@example.com" class="social-link" title="Email">
```

### 3. Update Informasi Personal

Edit bagian berikut untuk informasi Anda sendiri:

**Hero Section:**
- Ganti "Hi, I'm Fandi Septian" dengan nama Anda
- Ganti "Full Stack Developer" dengan profesi Anda
- Update deskripsi di bagian hero-description

**About Section:**
- Update teks about me sesuai pengalaman Anda
- Ubah atau tambahkan skills di skills grid

**Projects Section:**
- Ubah project title, description, dan tags
- Ganti links ke project Anda
- Update icon project (gunakan Font Awesome icons)

**Contact Section:**
- Update link email di button "Send Me an Email"

## 🎨 Fitur

✨ **Animasi Modern**
- Preloader dengan loader animation
- Fade-in effects saat scroll (AOS)
- Hover effects pada semua elemen interaktif
- Smooth scroll navigation

📱 **Responsive Design**
- Mobile-first approach
- Fully responsive di semua device sizes
- Optimized untuk desktop, tablet, dan mobile

🚀 **Performance**
- Lightweight dan fast loading
- Optimized CSS dan JavaScript
- Backdrop blur effects

## 📁 File Structure

```
portofolio/
├── index.html          # Main file
├── profile.jpg         # Foto profile (tambahkan ini)
└── README.md          # File ini
```

## 🎯 Tips Customization

1. **Mengubah warna theme:**
   Edit CSS variables di bagian `:root` dalam style:
   ```css
   :root {
       --primary: #00d4ff;      /* Warna utama (cyan) */
       --secondary: #ff006e;    /* Warna accent (magenta) */
       --dark: #0a0e27;         /* Warna background gelap */
   }
   ```

2. **Mengubah font:**
   Font menggunakan 'Poppins' dari Google Fonts. Untuk mengubah, edit link di `<head>` bagian Google Fonts.

3. **Menambah project baru:**
   Copy-paste salah satu project card dan ubah isinya sesuai kebutuhan.

## 📝 Lisensi

Portfolio ini bisa Anda gunakan untuk keperluan pribadi dan komersial.

---

**Setup selesai!** Portfolio Anda siap digunakan. 🎉
