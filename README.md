# Regl takvimim

Tek dosyalık (index.html) regl takip sayfası. Sunucu gerekmez.

## GitHub Pages ile yayınlama
1. github.com'da yeni bir repo aç (ör. `regl-takvimi`). Gizli (private) yapabilirsin; Pages için GitHub Pro gerekebilir, ücretsiz hesapta repo public olmalı. Kişisel veri repoda değil, sadece senin tarayıcında tutulur.
2. `index.html` ve `README.md` dosyalarını yükle (Add file > Upload files).
3. Settings > Pages > Source: `Deploy from a branch`, Branch: `main` / `/ (root)` > Save.
4. Birkaç dakika sonra `https://KULLANICIADIN.github.io/regl-takvimi/` adresinde açılır.
5. Telefonda adresi aç, Paylaş/Menü > "Ana ekrana ekle".

## Veriler nasıl korunuyor
- Kayıtlar tarayıcıda hem localStorage hem IndexedDB'ye yazılır; biri silinirse diğerinden geri gelir.
- Tarayıcıdan kalıcı depolama istenir (otomatik temizlenmesin diye).
- Sayfadaki "Yedek indir" ile JSON dosyası alabilir, "Yedekten yükle" ile geri getirebilirsin.
- Veriler GitHub'a gönderilmez, yalnızca cihazında durur. Telefon ve bilgisayar arasında taşımak için yedek dosyasını kullan.
