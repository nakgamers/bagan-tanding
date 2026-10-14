# Bagan Tanding

Aplikasi web pembuat bagan pertandingan sistem gugur — dari daftar atlet sampai bagan final yang siap cetak. Satu file, tanpa server, tanpa proses build.

Dikembangkan untuk **PORTINA DKI Jakarta** (Persatuan Olahraga Tradisional Indonesia DKI Jakarta) dan dipakai pada Kejuaraan Olahraga Tradisional Hadang 2026.

## Fitur

- **Pendaftaran atlet** — hingga 64 atlet per kejuaraan
- **Undian fleksibel** — acak otomatis atau urutan manual (nomor undian 1 mendapat bye)
- **Bagan otomatis** — sistem gugur penuh dari 64 besar hingga final
- **Editor kanvas** — node bisa digeser dengan drag-and-drop, garis konektor bisa disesuaikan manual
- **Update hasil** — input menang/kalah per pertandingan, pemenang maju otomatis ke babak berikut
- **Watermark logo** — logo kejuaraan tampil sebagai watermark di bagan
- **Ekspor & cetak** — unduh bagan sebagai SVG, siap untuk publikasi dan cetak
- **Tanpa backend** — seluruh logika berjalan di browser; data tidak dikirim ke mana pun
- **Mode terang & gelap** mengikuti preferensi perangkat

## Cara Pakai

1. Buka `index.html` langsung di browser, atau serve folder ini via HTTP server apa pun:
   ```bash
   npx serve .
   # atau
   python3 -m http.server 8080
   ```
2. Masukkan daftar atlet.
3. Pilih undian acak atau susun manual, lalu buat bagan.
4. Klik setiap pertandingan untuk mencatat pemenang.
5. Unduh SVG atau cetak bagan final.

## Teknologi

- HTML + CSS + JavaScript murni — single file, nol dependency build
- Rendering bagan berbasis SVG
- Font: Barlow Condensed & IBM Plex Sans (via Google Fonts, dengan fallback sistem)

## Klien

Proyek ini dikembangkan untuk **PORTINA DKI Jakarta** — portinadkijakarta.id — untuk kebutuhan bagan tanding Kejuaraan Olahraga Tradisional Hadang 2026.

---

*Butuh tool serupa untuk kejuaraan atau event Anda? Silakan hubungi via informasi kontak di profil.*
