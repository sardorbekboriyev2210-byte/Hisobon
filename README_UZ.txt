# Hisobon — Android APK uchun tayyor loyiha

Bu paket Hisobon HTML/CSS/JS ilovasini Android APK ga o‘rash uchun tayyorlangan.

## iPhone'dan keyingi qadam
1. GitHub’da yangi repository yarating.
2. Shu paket ichidagi fayllarni repository'ga yuklang.
3. `.github/workflows/build-apk.yml` fayli saqlanganiga ishonch hosil qiling.
4. GitHub'dagi **Actions** bo‘limiga kiring.
5. `Build Hisobon APK` workflow ishga tushadi.
6. Tugagach, workflow ichidagi **Artifacts** dan `Hisobon-debug-apk` ni oling.

Bu debug APK. Android telefonda sinash uchun ishlatiladi.

App Store uchun esa alohida iOS build kerak bo‘ladi.
