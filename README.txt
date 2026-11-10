KEY CLOUD Test App - Build via GitHub Actions

1. Buat repository GitHub baru (mis. key-cloud-test-app).
2. Upload seluruh isi folder proyek ini ke root repository, termasuk folder .github.
3. Buka tab Actions pada repository.
4. Jika diminta, aktifkan GitHub Actions.
5. Workflow "Build KEY CLOUD Test APK" akan berjalan otomatis setelah push ke main.
   Bisa juga pilih workflow tersebut lalu klik Run workflow.
6. Setelah selesai berstatus hijau, buka run tersebut, cari bagian Artifacts,
   lalu unduh key-cloud-test-apk.zip.
7. Ekstrak ZIP artifact. Di dalamnya ada app-debug.apk.

Catatan:
- APK ini adalah aplikasi tes sederhana, bukan Roblox.
- Build dilakukan di runner GitHub Actions.
- Jangan masukkan API key SpawnDroid ke repository.
