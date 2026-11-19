---
id: data-processing
title: Oxirgi foydalanuvchilar maʼlumotlarini qayta ishlash shartlari
sidebar_label: Maʼlumotlarni qayta ishlash shartlari
sidebar_position: 5
slug: /legal/data-processing/
---

# Oxirgi foydalanuvchilar maʼlumotlarini qayta ishlash shartlari

Kuchga kirgan sana: 12.11.2026

Ushbu shartlar [Ommaviy oferta](./public-offer.md)ning ajralmas qismi bo‘lib, Integrator Verificahub API orqali yuboradigan Oxirgi foydalanuvchilar maʼlumotlariga qo‘llaniladi.

## 1. Rollar

1.1. Oxirgi foydalanuvchilar maʼlumotlariga nisbatan **Integrator** shaxsga doir maʼlumotlar mulkdori, **Verificahub** esa Integrator topshirig‘i bilan va faqat xizmatlarni ko‘rsatish uchun qayta ishlovchi operator hisoblanadi.

1.2. Verificahub bu maʼlumotlarni o‘z maqsadlari — reklama, profillash, sotish yoki uchinchi shaxslarga berish — uchun ishlatmaydi.

## 2. Maʼlumotlar

- Oxirgi foydalanuvchining telefon raqami (+998);
- OTP kod;
- Tasdiqlash seansi identifikatori, holatlari va vaqt belgilari;
- aloqa operatorlaridan olingan yetkazish holatlari;
- Integrator so‘rovi bilan birga yuborilgan texnik parametrlar.

Integrator so‘rov parametrlarida (masalan, metadata maydonlarida) ortiqcha shaxsga doir maʼlumotlarni yubormaydi.

## 3. Maqsadlar

- OTP kodni yuborish va tekshirish;
- holatlarni taqdim etish va webhook bildirishnomalarini yuborish;
- yuborilgan xabarlar hisobi va hisob-kitob;
- firibgarlik va suiisteʼmolning oldini olish;
- talabnomalar va nizolarni ko‘rib chiqish.

## 4. Qayta ishlash tartibi

4.1. Telefon raqami ochiq ko‘rinishda faqat SMS yuborish uchun zarur bo‘lgan vaqtda ishlatiladi va SMS-shlyuz provayderiga uzatiladi.

4.2. Maʼlumotlar bazasida telefon raqami xesh ko‘rinishida saqlanadi. Platforma jurnallarida raqam maskalanadi.

4.3. OTP kod ochiq ko‘rinishda saqlanmaydi va faqat Tasdiqlash seansining amal qilish muddati davomida tekshiriladi.

4.4. Integrator keyingi amallarni Tasdiqlash seansi identifikatori bo‘yicha bajaradi.

## 5. Jalb qilinadigan shaxslar

5.1. Verificahub xizmatlarni ko‘rsatish uchun xizmat ko‘rsatuvchilarni jalb qilishi mumkin: SMS-shlyuzlar, mobil aloqa operatorlari, serverlar va data-markazlar. Ular maʼlumotlarni faqat o‘z vazifasini bajarish uchun zarur hajmda qayta ishlaydi, ulardan o‘z maqsadlarida foydalanmaydi va maxfiylik hamda xavfsizlikni taʼminlash majburiyatini oladi.

5.2. Verificahub jalb qilingan shaxslarning harakatlari uchun Integrator oldida javobgar bo‘ladi.

## 6. Lokalizatsiya

Oxirgi foydalanuvchilar maʼlumotlari O‘zbekiston hududidagi serverlarda saqlanadi. Transchegaraviy uzatish faqat qonunchilik talablariga rioya qilgan holda amalga oshiriladi.

## 7. Saqlash muddatlari

| Maʼlumotlar | Muddat |
|---|---|
| OTP kod | Tasdiqlash seansining amal qilish muddati |
| Tasdiqlash seanslari yozuvlari (xeshlangan raqam, holatlar, vaqt, narx) | 12 (o‘n ikki) oy — hisob-kitob va talabnomalar uchun |
| Jurnallar (raqamlar maskalangan) | 90 (to‘qson) kun |

Muddat tugagach maʼlumotlar o‘chiriladi yoki shaxssizlantirilgan statistikaga aylantiriladi. Shartnoma tugaganda Integrator maʼlumotlarni muddatidan oldin o‘chirishni so‘rashi mumkin; hisob-kitob uchun zarur yozuvlar qonun talablariga muvofiq saqlanadi.

## 8. Xavfsizlik

Verificahub TLS shifrlash, xeshlash va maskalash, kirish huquqlarini cheklash, kirishlar monitoringi va xodimlarning maxfiylik majburiyatlarini qo‘llaydi.

## 9. Hodisalar

Oxirgi foydalanuvchilar maʼlumotlari bilan bog‘liq xavfsizlik hodisasi aniqlansa, Verificahub Integratorga asossiz kechiktirmasdan, iloji bo‘lsa 72 soat ichida xabar beradi va oqibatlarni bartaraf etish choralarini ko‘radi.

## 10. Subyektlarning murojaatlari

Oxirgi foydalanuvchilar o‘z maʼlumotlari bo‘yicha Integratorga murojaat qiladi. Murojaat Verificahubga kelsa, Verificahub uni Integratorga yo‘naltiradi va javob berishda yordam beradi.

## 11. Integratorning majburiyatlari

Integrator:

- Oxirgi foydalanuvchilar maʼlumotlarini qayta ishlash uchun qonuniy asosga ega bo‘ladi;
- Oxirgi foydalanuvchilarga tasdiqlash kodlari Verificahub orqali yuborilishini o‘z maxfiylik siyosatida ma’lum qiladi;
- faqat Oxirgi foydalanuvchining o‘zi kiritgan raqamlarni yuboradi;
- faqat zarur maʼlumotlarni yuboradi.
