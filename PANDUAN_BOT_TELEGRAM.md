# Panduan Pemasangan & Pengoperasian Bot Telegram Al-Awaiq (العوائق)

Bot Telegram pintar untuk rujukan pantas kitab **Al-‘Awā’iq (Batu-Batu Penghalang di Sepanjang Jalan Dakwah)** karya As-Syeikh Muhammad Ahmad ar-Rasyid *rahimahullah*.

---

## 🚀 Langkah 1: Dapatkan Token Bot dari @BotFather

1. Buka aplikasi Telegram dan cari **@BotFather**.
2. Hantar arahan `/newbot`.
3. Berikan nama untuk bot (contoh: `Al-Awaiq Fiqh Haraki`).
4. Berikan username bot (contoh: `AwaiqHaraki_bot` atau `AwaiqKu_bot`).
5. Salin token API yang diberikan (contoh: `123456789:ABCdefGhIJKlmNoPQRsTUVwxyZ`).

---

## ⚙️ Langkah 2: Masukkan Token ke Dalam `config.json`

Buka fail `config.json` dan gantikan:
```json
{
  "bot_token": "MASUKKAN_TOKEN_TELEGRAM_DI_SINI",
  "bot_name": "AwaiqKu_bot",
  "description": "Bot Rasmi Halangan Dakwah Al-Awaiq"
}
```

---

## ▶️ Langkah 3: Lancarkan Bot

Klik dua kali pada fail `start_bot.bat` untuk menjalankan bot di komputer anda.

---

## 🌐 Perintah-Perintah Utama Bot

- `/start` : Memaparkan menu utama interaktif
- `/menu`  : Membuka senarai 24 Bab Al-Awaiq
- `/hikmah`: Memaparkan mutiara kata hikmah & fiqh haraki secara rawak (daripada 220 mutiara kata)
- `/cari [kata kunci]`: Carian pantas bagi sebarang topik, hadis, atau kalam tokoh dalam kitab
