# Nalar AI — Studi Kasus PABWE P2

Website simulasi perusahaan jasa Artificial Intelligence bernama **Nalar AI**,
dibuat untuk studi kasus praktikum CSS & CSS Framework.

## Halaman

| Halaman | File | Teknologi styling |
|---|---|---|
| Landing page | `index.html` + `assets/css/style.css` | HTML + CSS murni (external CSS) |
| Daftar blog | `blog.html` | Bootstrap 5 + Bootstrap Icons |
| Detail blog | `blog-detail.html` | Bootstrap 5 + Bootstrap Icons |
| CV digital | `cv.html` | Tailwind CSS 4 (Play CDN) + Tabler Icons |

Semua halaman saling terhubung lewat navigasi (navbar) dan berbagi identitas
visual yang sama (nama brand "Nalar AI", warna aksen amber `#f2a33c`, dan
warna gelap `#0f1226`).

## Struktur folder

```
nalar-ai/
├── index.html          # Landing page (CSS murni)
├── blog.html           # Daftar blog (Bootstrap 5)
├── blog-detail.html    # Detail blog (Bootstrap 5)
├── cv.html             # CV (Tailwind CSS 4)
├── assets/
│   └── css/
│       └── style.css   # CSS eksternal untuk index.html
└── README.md
```

## Cara menjalankan

Buka `index.html` langsung di browser, atau jalankan lewat live server
(mis. ekstensi "Live Server" di VS Code) agar navigasi antar halaman dan
gambar dari CDN termuat dengan baik. Semua library (Bootstrap, Tailwind,
Google Fonts, ikon) dimuat lewat CDN sehingga perlu koneksi internet.
