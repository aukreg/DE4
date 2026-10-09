# Almanca Günlük

Sade, yeni uygulama. İçinde sadece bizim çalışma sistemimiz var; eski kelime/cümle listeleri yok.

- **Bugün:** günün akışı (10 kalıp → kitap bölümü → senaryo → günlük yazı → hatalar). Tek düğme: sıradakine götürür.
- **Kalıplar:** Notion'daki kalıplar; kart → seç → sesli söyle alıştırması. Yeni / Öğreniyorum / Oturdu.
- **Diyalog:** Atakan & Nisa kitabı (20 bölüm, her cümlenin Türkçesi) ve konuşma senaryoları. "Ben: Atakan" seçince senin repliklerin gizlenir, sesli oynatırken sıra sana gelince durur.
- **Yaz:** günün konusu, otomatik kayıt, "Kopyala ve Claude'a gönder". Düzeltmeler ve Hata Defteri buraya gelir.

## Dosyalar
`index.html` (uygulama), `data.js` (içerik; Claude günceller), `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`.

## Telefona kurmak
Klasörü GitHub'da bir repoya yükle → Settings → Pages → main branch. Sonra telefonda Chrome'da aç → ⋮ → **Ana ekrana ekle**.
İçerik güncellenince sadece `data.js` değişir; uygulama internete bağlanınca yenisini alır.
