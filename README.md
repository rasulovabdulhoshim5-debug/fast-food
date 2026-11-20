# FAST FUND — Fast food buyurtma sayti

## Fayllar
- `index.html` — mijozlar uchun asosiy sayt.
- `style.css` — responsive qora/sariq dizayn.
- `app.js` — menyu, 3 xil variant, savat, sevimlilar, checkout, viloyat/tuman tanlash.
- `admin.html` — alohida admin sahifasi.
- `admin.js` — demo admin boshqaruvi.
- `admin.css` — admin qo‘shimcha stillari (asosiy style.css bilan birga ishlaydi).

## Ishga tushirish
`index.html` faylini brauzerda oching. Internet yoqilgan bo‘lsa, Unsplash rasmlari va Google Fonts yuklanadi.

## Demo admin
Saytning pastki qismidagi **Admin panel** havolasini bosing.
Demo PIN: `2468`.

## GitHub Pages / Netlify
1. Ushbu papkadagi fayllarni GitHub repository'ga yuklang yoki ZIP ichidagilarni chiqarib yuklang.
2. Netlify'da **Add new site → Import an existing project** orqali GitHub repository'ni ulang.
3. Build command bo‘sh qolsin; publish directory sifatida `/` (repository root) tanlang.
4. Deploy qiling. Sayt `index.html` dan ochiladi, admin esa `/admin.html`.

## Muhim: demo va production farqi
Bu loyiha hozircha HTML/CSS/JavaScript frontend prototipi. Ma'lumotlar `localStorage` orqali ayni brauzer/qurilmada saqlanadi. Shuning uchun:
- Mijoz buyurtmasi kafe egasining boshqa qurilmasiga avtomatik bormaydi.
- Admin PIN `2468` faqat namuna; u haqiqiy xavfsiz autentifikatsiya emas.
- Mahsulotlar va buyurtmalar barcha mijozlar orasida sinxronlashmaydi.
- Haqiqiy ishga tushirishdan oldin Supabase/Firebase yoki o‘z backend API, server-side admin autentifikatsiyasi, rol/ruxsatlar, server validatsiyasi, spamdan himoya va maxfiy kalitlarni serverda saqlash kerak.
- Google Maps tugmasi xaritani ochadi; foydalanuvchi xarita ulashish havolasini o‘zi kiritadi. Saytda avtomatik GPS kuzatuv yo‘q.

## Eslatma
Kontakt raqami, email va taomlar narxlarini o‘zingizning haqiqiy ma'lumotlaringizga almashtiring.
