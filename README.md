# KONİ: Windows ve macOS kurulumları

Arkadaşlarla senkron video izleme uygulaması KONİ'nin kurulum dosyaları. Kaynak kod burada değil.

**Windows:** [Releases → en son sürüm](https://github.com/Savas07/koni-releases/releases/latest) → `KONI_<sürüm>_x64-setup.exe`. Windows 10/11 x64, yönetici izni istemez. İmzasız: SmartScreen'de "Ek bilgi → Yine de çalıştır".

**macOS:** aynı sayfadan `KONI_<sürüm>_aarch64.dmg`. Apple Silicon (M1 ve sonrası), macOS 14+. Apple Developer imzası yok (ad-hoc imzalı, notarize edilmedi): ilk açılışta macOS engellerse Sistem Ayarları → Gizlilik ve Güvenlik → "Yine de Aç". "Hasarlı" uyarısı çıkarsa Terminal'de `xattr -cr /Applications/KONI.app`.

**Güncelleme:** kurulu KONİ açılışta yeni sürümü buradan kendisi indirip kurar (imzalı; yalnızca KONİ anahtarıyla imzalanmış paket kabul edilir). Taşınabilir zip kendini güncellemez.

**Lisans:** oynatıcı LGPL libmpv/FFmpeg; `NOTICE.md`, `LICENSES/` ve `source/` (mpv + FFmpeg kaynakları) kurulumun içinde (macOS: `KONI.app/Contents/Resources/libmpv`).

Bu repo otomatik doldurulur: `incoming` dalı ve `.github/workflows/publish.yml`.
