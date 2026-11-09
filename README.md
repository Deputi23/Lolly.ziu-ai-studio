# LOLLY AI STUDIO — v0.2

Studio produksi micro drama AI yang berjalan sebagai website statis dan PWA.

## Isi paket
- `index.html` — dashboard dan workspace drama interaktif.
- `manifest.webmanifest` — identitas PWA.
- `sw.js` — cache offline dasar.
- `icon-192.png`, `icon-512.png` — ikon aplikasi.

## Fitur yang sudah berjalan secara lokal
- Drama Creator: metadata serial dan episode.
- Character Studio: profil dan character-lock prompt.
- Storyboard: 12 shot awal, durasi, visual, kamera, dialog, audio, kontinuitas.
- Dialog & Voice: daftar dialog dan pratinjau suara browser jika tersedia.
- Produksi AI: pembuat prompt dan pelacakan status klip.
- Final Editor: timeline, ekspor CSV, edit plan TXT, backup/import JSON.
- Penyimpanan otomatis di browser melalui localStorage.

## Batasan yang perlu diketahui
- Tidak ada backend, login, sinkronisasi cloud, atau database server.
- Generator gambar/video AI belum terintegrasi; prompt harus disalin ke layanan eksternal.
- Pratinjau suara memakai Speech Synthesis browser dan bukan file voice-over final.
- PWA/offline membutuhkan hosting HTTPS dan semua file paket berada pada folder repository yang sama.

## Publikasi melalui GitHub Pages
1. Unggah/replace `index.html` dan tambahkan `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png` ke root repository.
2. Di repository, buka Settings → Pages.
3. Pada Build and deployment, pilih Deploy from a branch, branch `main`, folder `/(root)`, lalu Save.
4. Tunggu URL Pages muncul. Buka URL itu melalui Chrome Android.
5. Setelah halaman terbuka, gunakan menu browser → Install app / Tambahkan ke layar utama.

## Pengujian cepat
1. Buka `index.html` melalui hosting HTTPS.
2. Isi Drama Creator dan Character Studio, lalu refresh; data harus tetap ada pada browser yang sama.
3. Edit salah satu shot dan salin prompt.
4. Ubah status shot menjadi Selesai; progres dashboard harus bertambah.
5. Ekspor JSON, lalu impor kembali untuk menguji backup.
