# Untuk Azizah ❤️ — OLED Love Animation

**Deskripsi repository:** Untuk Azizah ❤️ Ada animasi cinta retro OLED spesial yang dibuatkan khusus untukmu! (Dari: Mr.Wijaya) "Untuk seseorang yang selalu spesial ❤️"

Aplikasi web animasi cinta bergaya retro pixel-art/OLED, dengan adegan animasi, tema warna, kontrol pemutaran, personalisasi pesan, dan opsi berbagi.

## Menjalankan secara lokal

Memerlukan Node.js 22 atau versi yang kompatibel.

```bash
npm install
npm run dev
```

Buka URL lokal yang ditampilkan oleh Vite/tsx di terminal.

## Deploy ke GitHub Pages

Workflow `.github/workflows/deploy.yml` membangun aplikasi dan menerbitkan folder `dist` setiap kali ada push ke branch `main`.

1. Buat repository **Public** bernama `oled-love-animation`.
2. Unggah semua isi ZIP ini ke root repository (bukan folder ZIP di dalam repository), lalu commit ke branch `main`.
3. Buka **Settings → Pages** dan pilih **GitHub Actions** sebagai source deployment.
4. Buka tab **Actions** dan tunggu workflow **Deploy OLED Love Animation to GitHub Pages** selesai dengan status hijau.
5. URL website yang diharapkan: `https://fatoniwijaya.github.io/oled-love-animation/`.

## Catatan

- Repository ini bersifat publik; jangan memasukkan API key, token, kata sandi, atau file `.env` yang berisi rahasia.
- GitHub Pages hanya menyajikan frontend statis. Fitur yang memerlukan server Express atau endpoint backend tidak akan berjalan di GitHub Pages tanpa backend terpisah.
- URL website baru dapat dibagikan setelah workflow deployment berhasil.
