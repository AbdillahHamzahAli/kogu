# [Kogu Space](https://koguspace.netlify.app)

Landing page statis untuk brand minuman Kogu Space. Dibangun dengan HTML dan CSS murni, ringan, responsif, dan mudah dikustomisasi.

## Fitur

- **Header & Navigasi**: Navigasi ke setiap section (`#home`, `#menu`, `#reviews`, `#location`, `#about`).
- **Hero Section**: Banner promo "Limited Time" dengan CTA.
- **Menu (Most Popular Drink)**: Kartu produk grid 4 kolom (otomatis menjadi 1 kolom di layar kecil).
- **Reviews**: Testimoni pelanggan dengan rating bintang.
- **Spot Us (Lokasi)**: Alamat, kontak, jam operasional, Instagram, dan galeri gambar.
- **Footer**: Tautan cepat dan sosial.
- **Responsif**: Media query untuk perangkat mobile (≤768px).

## Teknologi

- **HTML5** (`index.html`)
- **CSS3** (`style.css`)
- **Google Fonts**: Poppins

## Struktur Proyek

```
kogu/
├─ index.html
├─ style.css
├─ assets/
│  └─ img/ (logo, hero, produk, ikon, dll.)
└─ LICENSE
```

## Cara Menjalankan

- **Lokal (paling mudah)**: buka langsung `index.html` di browser modern (Chrome/Edge/Firefox/Safari).
- **Opsional (server lokal)**: gunakan ekstensi Live Server (VS Code) atau server statis apa pun untuk pengembangan dengan live reload.

## Kustomisasi Cepat

- **Warna tema**: ubah CSS variable di `style.css` pada blok `:root`.
  ```css
  :root {
    --primary-color: #f2eae1;
    --secondary-color: #6196cf;
    --text-color: #fbfcfe;
    --deep-secondary: #004775;
    --accent: #f5d17b;
    --header-h: 72px;
  }
  ```
- **Logo & Gambar**: ganti berkas di `assets/img/` (mis. `logo.png`, `hero-img.png`, ikon, dan gambar produk/galeri) lalu sesuaikan path di `index.html`.
- **Menu Produk**: edit elemen pada section `#menu` di `index.html` bagian `.product-card` untuk menambah/mengubah kartu produk.
- **Teks Promo/CTA**: ubah konten pada section `#home` di `index.html`.
- **Informasi Toko**: sesuaikan alamat, nomor telepon, jam, dan Instagram pada section `#location`.

## Praktik Responsif

- Grid produk menjadi 1 kolom pada mobile.
- Review dan layout lain beradaptasi melalui media query di `style.css` (≤768px).

## Aset

- Semua aset gambar di `assets/img/`. Pastikan nama berkas sesuai dengan yang dirujuk di `index.html`.

## Kredit

Desain dan implementasi front-end sederhana untuk kebutuhan landing page Kogu Space.
