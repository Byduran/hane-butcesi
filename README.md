# Hane Bütçesi (prototip)

Gelir ve giderleri girip aylık artı/eksi durumunu, ay sonu tahminini, kredi kartı borcunu ve tasarruf önerilerini gösteren, telefonda da çalışan tek sayfalık web uygulaması prototipi.

## Özellikler
- Gelir ve gider ekleme, düzenleme, silme; her ay tekrarlayan kayıtlar
- Aylık net durum (artı/eksi) ve ay sonu tahmini
- Kategori raporu ve aylık karşılaştırma
- Kredi kartı takibi (limit, borç, hesap kesim ve son ödeme günü, tahmini faiz)
- CSV ekstre yükleme, otomatik kategori tahmini ve gelecek ay yorumu
- Kural tabanlı tasarruf önerileri; ayrı ve etiketli "Sponsorlu" fırsatlar sekmesi (örnek veriyle)

## Çalıştırma
`index.html` dosyasını tarayıcıda açmak yeterli. Veriler şimdilik yalnızca tarayıcıda (localStorage) saklanır.

## Yol haritası
1. Üyelik ve veritabanı (kalıcı, cihazlar arası kayıt)
2. PDF ve Excel ekstre desteği
3. Firma paneli ve gerçek kampanyalar
