# toolkit

Situs tools online gratis. Dihost di GitHub Pages.

## Struktur Folder

```
toolkit/
├── index.html                  ← Dashboard utama
├── sitemap.xml                 ← (dibuat manual / generate)
├── README.md
└── tools/
    ├── teks/
    │   ├── word-count.html     ✅ READY
    │   ├── case-converter.html
    │   ├── remove-whitespace.html
    │   └── text-reverse.html
    ├── konverter/
    │   ├── satuan-panjang.html ✅ READY
    │   ├── satuan-berat.html
    │   ├── suhu.html
    │   └── waktu.html
    ├── kalkulator/
    │   ├── bmi.html            ✅ READY
    │   ├── persen.html
    │   ├── cicilan.html
    │   └── umur.html
    └── generator/
        ├── password.html       ✅ READY
        ├── lorem-ipsum.html
        ├── uuid.html
        └── nama.html
```

## Cara Upload ke GitHub Pages

1. Buat repo baru: `toolkit`
2. Upload semua file
3. Settings → Pages → Branch: main / root
4. URL akan jadi: `https://[username].github.io/toolkit/`

## Checklist SEO

- [x] Meta title + description di setiap halaman
- [x] Canonical URL
- [ ] sitemap.xml
- [ ] Daftar Google Search Console
- [ ] robots.txt
