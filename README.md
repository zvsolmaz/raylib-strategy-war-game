# 🛡️ War Strategy: Grid-Based Battle Simulation (Raylib + C)

**Programming II Term Project – Developed in C Language using Raylib**

A visually enhanced 2D grid-based strategy game built with Raylib. Two armies face off in a tactical battle using infantry, archers, cavalry, and catapults. Built with modular C code and rendered using the Raylib graphics library.

---

## 📌 Game Overview

**War Strategy** is a turn-based tactical simulation game where players strategically place and control units on a battlefield grid. Visuals are rendered using Raylib to create a more engaging and modern C game experience.

---

## 🕹️ Game Features

- 🎯 Turn-based grid combat system
- 🪖 Four unit types with different roles: Archer, Infantry, Cavalry, Catapult
- 💥 Each unit has its own HP and attack range
- 💡 Raylib-powered graphics: health bars, tile rendering, keyboard control
- 📡 Optional `libcurl` integration for networking (e.g., update or stats)
- 🧼 Clean UI with game states: menu, play, win/lose

---

## 🧮 Units Overview

| Unit     | Health | Ability                   |
|----------|--------|----------------------------|
| Archer   | 100    | Long-range attack          |
| Infantry | 100    | Melee combat               |
| Cavalry  | 100    | High mobility + attack     |
| Catapult | 100    | Long-range + AOE damage    |

---

## 💻 Technical Details

- Language: **C**
- Graphics: **[Raylib](https://www.raylib.com/)**  
- Networking: **[libcurl](https://curl.se/libcurl/)**
- Input: Keyboard (Arrow keys, Space, Enter)
- Structure:
  - `main.c`: game loop
  - `game.c/h`: state handling, input logic
  - `renderer.c/h`: Raylib rendering (sprites, grid, text)
  - `units.c/h`: unit logic
- Build: Use `gcc` or provided `Makefile`
- OS Support: Windows, Linux, macOS

---

## 🧩 Dependencies

Place these in the same directory as your `.exe`:

- `raylib.dll`
- `libcurl-x64.dll`

---

## 📁 Project Structure

```plaintext
war-strategy-game/
├── assets/                 
│   └── karekterpng/         # Unit sprites
├── bin/                    # Executables like koüpro.exe
├── obj/                    # Object files
├── src/
│   ├── main.c
│   ├── game.c / game.h
│   ├── units.c / units.h
│   ├── renderer.c / renderer.h
├── Makefile
├── .gitignore
├── LICENSE
├── README.md
```

---

## 🧪 Screenshots

![WhatsApp Image 2025-11-03 at 00 58 13](https://github.com/user-attachments/assets/e96780ab-c05a-4ea7-836a-a4d9673099d9)

![WhatsApp Image 2025-11-03 at 00 58 13 (1)](https://github.com/user-attachments/assets/08f1bf05-6978-4dc4-b49e-4bbf11b7dd2d)

---

## 🏗️ How to Build

### GCC (Linux/macOS):
```bash
gcc src/*.c -o war_game -lraylib -lcurl -lm -ldl -lGL -lpthread
./war_game
```

### Windows:
- Include `raylib.dll` and `libcurl-x64.dll` in the working directory
- Compile using `Makefile` or Code::Blocks `.cbp` project

---






---

## 🇹🇷 Türkçe – Savaş Stratejisi: Izgara Tabanlı Simülasyon (Raylib + C)

Raylib grafik kütüphanesi ile geliştirilen bu projede, iki ordu sırayla hamle yaparak birbirlerini yok etmeye çalışır. Oyunun tüm görselleştirmeleri Raylib ile yapılmıştır.

---

## 🎯 Oyun Özellikleri

- Sıra tabanlı savaş sistemi
- 4 farklı asker türü: Okçu, Piyade, Süvari, Mancınık
- Her birimin ayrı HP ve saldırı tipi vardır
- Raylib ile görsel sağlık barları, ızgara çizimi, arayüz
- Menü, oyun ve bitiş ekranı
- Klavye ile kontrol: ok tuşları, enter, space
- (Opsiyonel) libcurl ile ağ bağlantısı desteği (veri gönderme/çekme)

---

## ⚙️ Teknik Bilgiler

- Geliştirme Dili: C
- Grafik Motoru: Raylib
- Ağ Bağlantısı: libcurl
- Yapılandırma:
  - `main.c`: Ana oyun döngüsü
  - `game.c/h`: Oyun durumu ve input kontrolü
  - `renderer.c/h`: Raylib ile görselleştirme
  - `units.c/h`: Birim yönetimi
- Derleme:
  - GCC: `gcc src/*.c -o war_game -lraylib -lcurl -lm -ldl -lGL -lpthread`
  - veya Makefile kullanabilirsiniz
- Platform: Windows, Linux, macOS

---

## 📁 Proje Yapısı

```plaintext
war-strategy-game/
├── assets/             # Sprite ve görseller
├── karekterpng/        # Karakter görselleri
├── src/                # Kaynak kod
├── obj/, bin/          # Derleme çıktıları
├── README.md           # Proje açıklaması (İngilizce + Türkçe)
├── Makefile            # Derleyici komutları
├── LICENSE             # MIT lisansı
└── .gitignore          # Versiyon dışı bırakılanlar
```

---

## 🧩 Bağımlılıklar

`.exe` dosyasının yanında şu dosyaların da bulunması gerekir:

- `raylib.dll`
- `libcurl-x64.dll`

---

