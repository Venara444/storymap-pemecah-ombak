# Storymap Breakwater Larantuka

Website satu halaman (storymap) siap diupload ke GitHub Pages.

## Cara pakai
1. Upload seluruh isi folder ini (termasuk folder `assets/`) ke repo GitHub-mu.
2. Aktifkan GitHub Pages (Settings → Pages → source: branch utama, folder root).
3. Buka `index.html` — semua CSS & JS sudah menyatu di file itu, tidak perlu build step apa pun.

## Aset yang perlu kamu tambahkan ke folder `assets/`
Sudah tersedia:
- `mekanisme-batu.png` — infografis 6 mekanisme batu (dari gambar yang kamu kirim).

Masih perlu kamu tambahkan (nama file harus persis sama, semua sudah dirujuk di `index.html`):
- `abrasi1.jpg`
- `ambilbatu.jpg`
- `apo1.jpg`
- `pembangunanpupr1.jpg`
- `perubahangarispantai.mp4`

Selama file belum ada, halaman tetap tampil rapi — setiap slot foto/video otomatis menampilkan placeholder bertuliskan nama file yang dibutuhkan, jadi kamu tahu persis di mana harus menaruhnya.

## Catatan desain
- Font: Big Shoulders Display (judul), Public Sans (isi), IBM Plex Mono (data/tanggal) — dimuat dari Google Fonts.
- Grafik garis pantai 2008–2025 bergerak mengikuti scroll (scrollytelling), dua garis: sisi Barat (dekat breakwater & aspal 2019) dan sisi Timur (belum terlindungi).
- Semua warna & tipografi diatur lewat CSS variables di bagian atas `<style>` bila ingin kamu sesuaikan.
