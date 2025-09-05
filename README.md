# Surat Desa APK (Final Version)

✅ Struktur sudah dirapikan ke root (pubspec.yaml, lib/, android/, .github/).  
✅ MainActivity pakai Flutter Embedding V2.  
✅ Workflow GitHub Actions siap build APK otomatis.

## Cara pakai
1. Upload isi folder ini langsung ke repo GitHub kamu (branch `main`).  
   Struktur repo harus seperti ini:
   ```
   pubspec.yaml
   lib/
   android/
   .github/
   ```
2. Buka tab **Actions** → workflow **Android APK CI** akan muncul otomatis.  
3. Jalankan workflow → tunggu selesai.  
4. Download artifact `surat-debug-apk` → extract → install `app-debug.apk` di HP Android. 🚀
