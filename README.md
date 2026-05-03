# Debuff Run

Göze hitap eden UI'ya sahip, tek dosyada çalışan bir **web platform oyunu**.

## Çalıştırma

```bash
python3 -m http.server 8080
```

Tarayıcıdan aç:
- `http://localhost:8080`

## Kontroller

- `A / D` veya `← / →`: Hareket
- `Space`: Zıplama
- `R`: Yeniden başlat

## Oyun Akışı

- Oyun menüsünden başlatılır.
- İlk **3 saniye** normal oynanır.
- Sonrasında her **5 saniyede** rastgele debuff gelir.
- Debuff geçişinde ekranda büyük uyarı metni görünür.
- Düşersen veya dikene çarparsan ölürsün.
- Bitişe ulaşırsan süren skor olur.
- Bitiremezsen mesafe skor olarak takip edilir.

## Debuff'lar (v1)

- Ters Kontrol
- Kaygan Zemin
- Ağır Çekim
- Turbo Kaos
- Gecikmeli Tepki
