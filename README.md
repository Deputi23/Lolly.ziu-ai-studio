# LOLLY AI DRAMA STUDIO v1.1 FIX

## Perbaikan
- Navigasi tab dan tombol menggunakan event listener JavaScript yang konsisten.
- Generate storyboard 8 adegan dengan durasi target 60/90/120 detik.
- Impor proyek JSON lama, termasuk format project `meta`, `characters`, dan `shots`.
- Impor 12 shot dari DI BALIK SENYUMAN Episode 1; aplikasi membagi tampilan menjadi 60 detik tanpa membuang isi shot.
- Salin prompt, unduh TXT/JSON, simpan dan pulihkan proyek lokal.
- PWA Android dan cache offline.

## Cara memperbarui GitHub Pages lewat HP
1. Unduh ZIP ini lalu ekstrak.
2. Buka repository GitHub `lolly-ai-studio`.
3. Hapus/ganti file lama di folder utama repository.
4. Unggah `index.html`, `manifest.webmanifest`, dan `sw.js` dari ZIP ini ke folder utama.
5. Commit perubahan. Tunggu GitHub Pages selesai deploy.
6. Buka situs di Chrome Android. Jika masih menampilkan versi lama, buka menu Chrome > Setelan > Setelan situs > Penyimpanan, hapus data situs LOLLY, lalu buka ulang URL GitHub Pages.
7. Impor `lolly-ai-studio-project (2).json` melalui tombol Impor proyek JSON.

## Batasan gratis
Aplikasi ini membuat naskah, dialog, storyboard, prompt, dan file proyek secara lokal. Aplikasi tidak merender video AI secara langsung. Generator video eksternal dapat memiliki batas kuota, watermark, atau syarat berbayar; tidak ada jaminan render tanpa batas dan tanpa watermark dengan biaya Rp0.
