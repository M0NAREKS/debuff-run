# Debuff Run: Endless Mode

Polished, competitive, browser-playable **2D endless runner**.

## Run
# Debuff Run

Göze hitap eden UI'ya sahip, tek dosyada çalışan bir **web platform oyunu**.

## Çalıştırma

```bash
python3 -m http.server 8080
```

Open: `http://localhost:8080`

## Controls

- `A / D` or `← / →` : minor horizontal correction
- `Space / W / ↑` : jump
- `R` : restart run

## Features

- Endless side-view runner with auto-forward movement
- 3s normal intro, then random debuff every 5s
- 0.5s glitch transition between debuffs
- No same debuff twice in a row
- Active debuff + next-debuff countdown on HUD
- Procedural terrain generation (platforms, gaps, spikes)
- Progressive difficulty scaling (speed, spacing, hazard density)
- Particles + screen shake for impact
- Game over screen + restart loop
- Local Top 10 leaderboard via `localStorage`
- Fixed random seed for competition fairness
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
