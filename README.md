# Araç Giderleri

Araç masraflarını kaydetmek ve özetlemek için çevrimdışı çalışan, kurulabilir (PWA) web uygulaması.
Veriler yalnızca telefonundaki tarayıcıda saklanır; hiçbir sunucuya gönderilmez.

## Dosyalar
- `index.html` – uygulamanın kendisi
- `manifest.webmanifest` – kurulum bilgileri
- `sw.js` – çevrimdışı çalışma (önbellek)
- `icons/` – uygulama simgeleri

## GitHub Pages ile yayınlama
1. Bu dosyaların hepsini bir GitHub deposunun ana dizinine yükle.
2. Depoda Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save.
3. Birkaç dakika sonra adres: `https://KULLANICI-ADIN.github.io/DEPO-ADI/`

## Telefona kurma (Chrome)
Adresi aç → ⋮ menüsü → "Ana ekrana ekle" / "Uygulamayı yükle".
Bir kez internetle açıldıktan sonra internetsiz de çalışır.

## Güncelleme
`index.html` değişirse `sw.js` içindeki `VERSION` değerini artır (v1 → v2).
