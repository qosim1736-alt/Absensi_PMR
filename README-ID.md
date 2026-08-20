# PMR Digital Online — Gratis & Multi-HP

## Cara pemasangan paling mudah dari HP
1. Buka Firebase Console → Project `absesi-pmr-spajaone` → Project settings → Your apps → Web app → Firebase SDK configuration.
2. Salin nilai **apiKey** dan ganti `PASTE_API_KEY_ANDA_DI_SINI` pada `index.html`.
3. Buat repository GitHub baru, upload `index.html` dan `firestore.rules`.
4. Aktifkan GitHub Pages dari Settings → Pages → Deploy from branch → `main` / root.
5. Di Firebase Console → Authentication → Settings → Authorized domains, tambahkan domain GitHub Pages Anda (contoh `namauser.github.io`).
6. Buka URL GitHub Pages dan login memakai akun Firebase Authentication yang sudah dibuat.
7. Setelah berhasil diuji, ubah Firestore Rules dari test mode ke rules di file `firestore.rules`.

Catatan: Firebase Hosting standar biasanya dideploy lewat Firebase CLI; untuk penggunaan gratis dari HP, paket ini menggunakan GitHub Pages sebagai hosting statis dan Firebase Authentication/Firestore sebagai backend.
