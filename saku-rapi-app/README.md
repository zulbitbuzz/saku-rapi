# Saku Rapi

Catatan keuangan pribadi yang dipasang ke layar utama HP tanpa App Store atau Play Store.

## Isi folder

| File | Fungsi |
|---|---|
| `index.html` | Seluruh aplikasi |
| `manifest.webmanifest` | Nama, warna, dan ikon aplikasi |
| `sw.js` | Membuat aplikasi tetap bisa dibuka tanpa internet |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | Ikon di layar utama |

## Memasang lewat GitHub Pages (gratis)

1. Buat akun di github.com kalau belum punya.
2. Ketuk **New repository**, beri nama `saku-rapi`, pilih **Public**, lalu **Create repository**.
3. Di halaman repo, pilih **uploading an existing file**, seret semua file di folder ini, lalu **Commit changes**.
4. Buka **Settings → Pages**. Di bagian **Branch** pilih `main` dan `/ (root)`, lalu **Save**.
5. Tunggu sekitar satu menit. Alamat aplikasinya: `https://NAMA-AKUN.github.io/saku-rapi/`

## Menaruh di layar utama

- **iPhone:** buka alamat itu di **Safari**, ketuk tombol Bagikan, pilih **Tambah ke Layar Utama**.
- **Android:** buka di **Chrome**, ketuk menu titik tiga, pilih **Instal aplikasi** atau **Tambahkan ke layar utama**.

Setelah itu buka selalu dari ikon di layar utama. Di iPhone, data di Safari dan data di ikon layar utama tersimpan terpisah.

## Yang perlu diketahui

- Data hanya tersimpan di HP itu. Buka tombol gembok, lalu **Simpan cadangan** secara berkala.
- Repo publik hanya berisi kode aplikasi. Data keuangan tidak pernah dikirim ke GitHub.
- Untuk memperbarui aplikasi, unggah ulang file yang berubah ke repo. HP mengambil versi baru saat dibuka dengan internet.
