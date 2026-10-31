# KONİ: kurulum dosyaları

Arkadaşlarla senkron video izleme uygulaması KONİ'nin kurulumları ve otomatik güncelleme dosyası (`latest.json`). Kaynak kod: [serkanqltun-hub/koni](https://github.com/serkanqltun-hub/koni).

**Windows:** [Releases → en son sürüm](https://github.com/Savas07/koni-releases/releases/latest) → `KONI_<sürüm>_x64-setup.exe`. Windows 10/11 x64, yönetici izni istemez. İmzasız: SmartScreen'de "Ek bilgi → Yine de çalıştır".

**macOS:** şu an yayınlanmıyor (yalnızca 0.0.32 ve 0.0.33'te deneme `.dmg`'si var).

**Güncelleme:** kurulu KONİ açılışta yeni sürümü buradan kendisi indirip kurar (imzalı; yalnızca KONİ anahtarıyla imzalanmış paket kabul edilir). Bu adres kurulu her kopyanın içine gömülü olduğu için repo silinmemeli. Taşınabilir zip kendini güncellemez.

**Lisans:** oynatıcı LGPL libmpv/FFmpeg; `NOTICE.md`, `LICENSES/` ve `source/` (mpv + FFmpeg kaynakları) kurulumun içinde.

Bu repo otomatik doldurulur: `incoming` dalı ve `.github/workflows/publish.yml`.
