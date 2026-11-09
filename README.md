# LOLLY AI STUDIO — v0.3 MULTI CHARACTER

Studio produksi micro drama AI berbasis website statis dan PWA.

## Fitur v0.3
- **Perpustakaan karakter:** tambah, edit, dan hapus banyak profil pemeran.
- **Foto referensi per karakter:** unggah foto; aplikasi memperkecil gambar dan menyimpannya di browser perangkat.
- **Pemeran per shot:** pilih satu atau beberapa karakter yang tampil pada setiap adegan.
- **Prompt multi-karakter:** deskripsi karakter yang dipilih otomatis dimasukkan ke prompt shot.
- **Migrasi data v0.2:** profil karakter tunggal lama dipindahkan menjadi satu profil karakter; proyek dan shot lama tetap dipertahankan.
- Drama Creator: metadata serial dan episode.
- Storyboard: 12 shot awal, durasi, visual, kamera, dialog, audio, kontinuitas.
- Dialog & Voice: daftar dialog dan pratinjau suara browser jika tersedia.
- Produksi AI: pembuat prompt dan pelacakan status klip.
- Final Editor: timeline, ekspor CSV, edit plan TXT, backup/import JSON.
- Penyimpanan otomatis di browser melalui localStorage.

## Cara memperbarui GitHub Pages
1. Ekstrak ZIP ini di HP.
2. Buka repository GitHub → Code → Add file → Upload files.
3. Unggah semua isi folder hasil ekstrak ke root repository, bukan file ZIP.
4. Jika diminta, setujui penggantian file lama (`index.html`, `sw.js`, manifest, README, ikon).
5. Commit changes ke branch `main`.
6. Tunggu beberapa menit, lalu buka ulang URL GitHub Pages.

## Catatan penting
- Data dan foto karakter disimpan di browser/perangkat yang sama. Tidak ada sinkronisasi cloud atau database server.
- Sebaiknya ekspor backup JSON sebelum membersihkan data browser atau berganti perangkat.
- Generator gambar/video AI belum terhubung langsung. Aplikasi menyiapkan prompt; render dilakukan di layanan eksternal yang menyediakan kuota gratis.
- Foto referensi tersimpan di aplikasi dan membantu pengelolaan prompt, tetapi tidak otomatis dikirim ke layanan AI. Saat membuat gambar/video, unggah foto yang sama ke layanan eksternal yang digunakan.
- Konsistensi wajah tetap bergantung pada fitur reference/character consistency layanan generator eksternal.
- Pratinjau suara memakai Speech Synthesis browser, bukan file voice-over final.

## PWA
GitHub Pages perlu menggunakan HTTPS. Setelah situs diperbarui, buka di Chrome Android → menu ⋮ → Tambahkan ke layar utama / Install app.
