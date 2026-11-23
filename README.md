# Bib Number Link Hub

Website satu halaman berisi tautan Shopee, TikTok, Instagram, dan Threads.

## Cara pakai
1. Upload `index.html` ke repository GitHub.
2. Buka **Settings → Pages**.
3. Pada **Build and deployment**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/ (root)`, lalu Save.
5. Setelah GitHub Pages aktif, buka URL website. QR Code dibuat otomatis dari URL halaman tersebut.

QR tidak mengarah langsung ke salah satu platform. QR mengarah ke halaman ini, lalu pengunjung memilih tombol platform.

## Mengubah tautan
Edit nilai `href` pada masing-masing elemen `<a class="link">` di `index.html`.

Catatan: QR generator menggunakan pustaka QRCode.js dari CDN, sehingga koneksi internet diperlukan saat halaman membuat QR.
