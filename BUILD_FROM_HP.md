# Build APK dari HP

Project ini sudah dilengkapi GitHub Actions. Workflow akan menjalankan Gradle 8.9 + Java 17 dan menghasilkan `app-debug.apk`.

1. Upload folder project ini ke repository GitHub.
2. Pastikan file `.github/workflows/build-apk.yml` ikut ter-upload.
3. Buka tab **Actions** pada repository.
4. Pilih **Build AI Host TikTok V10 APK** lalu jalankan **Run workflow** jika belum otomatis berjalan.
5. Setelah selesai, buka hasil workflow dan bagian **Artifacts**.
6. Download `AIHostTikTok-V10-debug`, ekstrak ZIP, lalu install `app-debug.apk` di HP.

Project Android berada di folder `android`.
