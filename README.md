# BiznesHisob React

BiznesHisob ish haqi boshqaruvi ilovasi React va Vite asosida ishlaydi.

## Ishga tushirish

```bash
npm install
npm run dev
```

Birinchi marta ochilganda admin parolini yarating. Demo ma’lumotlari va parol xeshi shu brauzerning `localStorage` xotirasida saqlanadi. Xodimlar jadvalidagi ish haqi yonidagi qalam tugmasi orqali rahbar summani bevosita o‘zgartirib saqlashi mumkin; bu o‘zgarish keyingi hisob-kitobga qo‘llanadi. Ilova bank o‘tkazmalarini amalga oshirmaydi; “to‘landi” holati faqat demo belgisidir.

Ishlab chiqarish buildini yaratish uchun `npm run build` buyrug‘idan foydalaning.

Android APK uchun `npm run build:android` buyrug‘i React buildini Android assetlariga ko‘chiradi. Keyin `BiznesHisobAndroid` ichida `.\gradlew.bat assembleDebug` buyrug‘ini ishga tushiring.
