# Assets Folder Guide

Folder ini berisi semua asset yang digunakan dalam website portfolio Anda.

## Struktur Folder

```
assets/
├── images/          - Gambar untuk portfolio projects
├── icons/           - Icon-icon (optional)
└── fonts/           - Custom fonts (optional)
```

## Cara Menambahkan Gambar

### 1. **Lokasi Gambar Portfolio**
   - Tempat: `assets/images/`
   - Nama file yang diharapkan untuk portfolio items:
     - `project-1.jpg` - Mobile App Design (UI/UX)
     - `project-2.jpg` - Website Redesign (UI/UX)
     - `project-3.jpg` - Sales Dashboard
     - `project-4.jpg` - Customer Analytics

### 2. **Format & Ukuran Rekomendasi**
   - Format: JPG, PNG, atau WebP
   - Ukuran: 600x600px minimum (untuk portfolio cards)
   - Ukuran lebih kecil untuk web (optimize terlebih dahulu)

### 3. **Cara Update Gambar**
   - Letakkan file gambar di `assets/images/`
   - Nama harus sesuai dengan file yang di-reference di index.html
   - Otomatis akan muncul di portfolio section

## Tips Customization

### 1. **Ganti Warna Tema Biru**
   - Edit `css/style.css` di bagian `:root`
   - Ubah variable color seperti `--primary-color`, `--primary-light`, dll

### 2. **Edit Konten Teks**
   - Buka `index.html` dan edit langsung
   - Ubah nama, deskripsi, contact info, dll

### 3. **Edit Detail Project**
   - File: `projects/uiux-project-1.html`, `dashboard-project-1.html`, dll
   - Ubah deskripsi, tools, dan hasil achievement

### 4. **Tambah Social Links**
   - Edit di section `footer` di `index.html`
   - Ganti href dengan link LinkedIn, Dribbble, dll

## File Structure Lengkap

```
Portofolio/
├── index.html                  - Halaman utama
├── css/
│   ├── style.css              - CSS utama
│   └── project.css            - CSS untuk halaman project detail
├── js/
│   └── script.js              - JavaScript untuk interaktivitas
├── projects/
│   ├── uiux-project-1.html    - Detail UI/UX Project 1
│   ├── uiux-project-2.html    - Detail UI/UX Project 2
│   ├── dashboard-project-1.html - Detail Dashboard Project 1
│   └── dashboard-project-2.html - Detail Dashboard Project 2
├── assets/
│   ├── images/                - Folder untuk gambar projects
│   ├── icons/                 - Folder untuk icons (optional)
│   └── fonts/                 - Folder untuk custom fonts (optional)
└── README.md                  - Dokumentasi ini
```

## Quick Edit Checklist

- [ ] Ganti nama di navbar (`.nav-brand`)
- [ ] Update hero section title & subtitle
- [ ] Ganti about section text
- [ ] Edit contact form dengan info Anda (email, phone, location)
- [ ] Tambah gambar portfolio di `assets/images/`
- [ ] Update social media links di footer
- [ ] Ubah warna jika ingin tema berbeda

## Deployment Tips

Website ini siap untuk di-deploy ke:
- Netlify
- Vercel
- GitHub Pages
- Traditional hosting (cPanel, etc)

Semua file static, tidak perlu backend server!

---

Happy Customizing! 🚀
