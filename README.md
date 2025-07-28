# Telegram Kino Bot

Bu Telegram bot foydalanuvchilarga kinolar yuklash, ulashish va kanallarga majburiy obuna funksiyalarini taqdim etadi. Bot adminlar uchun statistika, xabar yuborish va bot holatini boshqarish imkoniyatlarini ham o'z ichiga oladi.

## Imkoniyatlar
- 📽️ Kinolarni kod orqali yuklash va ulashish
- 📢 Majburiy obuna kanallarini sozlash
- 📊 Foydalanuvchi statistikasini ko'rish
- ✉️ Foydalanuvchilarga xabar yuborish
- 🤖 Bot holatini yoqish/o'chirish
- 🗄 Admin paneli orqali boshqarish

## O'rnatish

### Talablar
- PHP 7.0 yoki undan yuqori
- Telegram Bot API tokeni
- Railway yoki boshqa PHP-ni qo'llab-quvvatlovchi hosting platformasi
- Git va GitHub hisobi

### O'rnatish qadamlari
1. **Repository'ni klonlash**:
   ```bash
   git clone https://github.com/your-username/telegram-kino-bot.git
   cd telegram-kino-bot
   
   API_KEY=your_telegram_bot_token
ADMIN_ID=your_admin_id
PORT=3000

web: php -S 0.0.0.0:$PORT index.php

step/
kino/
*.txt
.env
*.log
.DS_Store

git add .
git commit -m "Initial commit"
git push origin main

/setwebhook url=https://your-railway-app.up.railway.app/
