# KONİ: Windows kurulumları

Arkadaşlarla senkron video izleme uygulaması KONİ'nin kurulum dosyaları. Kaynak kod burada değil.

**Kurulum:** [Releases → en son sürüm](https://github.com/Savas07/koni-releases/releases/latest) → `KONI_<sürüm>_x64-setup.exe`. Windows 10/11 x64, yönetici izni istemez. İmzasız: SmartScreen'de "Ek bilgi → Yine de çalıştır".

**Güncelleme:** kurulu KONİ açılışta yeni sürümü buradan kendisi indirip kurar (imzalı; yalnızca KONİ anahtarıyla imzalanmış kurulum kabul edilir). Taşınabilir zip kendini güncellemez.

**Lisans:** oynatıcı LGPL libmpv/FFmpeg; `NOTICE.md`, `LICENSES/` ve `source/` (mpv + FFmpeg kaynakları) kurulumun içinde.

Bu repo otomatik doldurulur: `incoming` dalı ve `.github/workflows/publish.yml`.
