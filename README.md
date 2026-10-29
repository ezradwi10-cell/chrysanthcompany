# Chrysanths — The Company Profile

Website company profile bergaya flipbook majalah. Situs statis (HTML, CSS, dan JavaScript saja), tanpa proses build, jadi bisa langsung dipasang di GitHub Pages.

## Isi repositori

```
index.html     halaman utama (semua teks ada di sini)
assets/        foto dan logo (logo, office, contact, ezra, nata, steven, collab, p1a–p2c)
favicon.png    ikon tab browser
404.html       halaman jika alamat tidak ditemukan
.nojekyll      agar GitHub Pages menyajikan file apa adanya
```

## Pasang di GitHub Pages

**Lewat browser (paling mudah)**

1. Buat repositori baru di GitHub, misalnya `chrysanths-profile` (Public).
2. Klik **Add file > Upload files**, lalu seret *semua isi* folder ini (termasuk folder `assets`) dan klik **Commit changes**.
3. Buka **Settings > Pages**. Pada *Build and deployment*, pilih **Deploy from a branch**, branch **main**, folder **/ (root)**, lalu **Save**.
4. Tunggu 1–2 menit. Alamatnya: `https://USERNAME.github.io/chrysanths-profile/`

**Lewat terminal**

```bash
git init
git add .
git commit -m "Company profile Chrysanths"
git branch -M main
git remote add origin https://github.com/USERNAME/chrysanths-profile.git
git push -u origin main
```

Lalu aktifkan Pages seperti langkah 3 di atas.

## Cara mengubah isi

- **Teks, nama tim, layanan, klien, kontak:** buka `index.html`, cari bagian `pages.push(` lalu ubah teksnya.
- **Foto:** ganti file di folder `assets/` dengan nama yang sama.
- **Warna:** ubah nilai di blok `:root` pada bagian `<style>`.
- **Domain sendiri:** Settings > Pages > Custom domain.

## Catatan

- Font (Bodoni Moda dan Hanken Grotesk) dimuat dari Google Fonts, jadi perlu koneksi internet. Tanpa itu, tampilan memakai font cadangan.
- Navigasi: tombol ‹ ›, panah keyboard, atau geser di layar sentuh.
- Foto dan logo adalah milik Chrysanths. Pastikan kamu berhak mempublikasikannya.
