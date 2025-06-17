## 📱 Contact Book

---

### 📝 Loyihaning tavsifi

`Contact Book` — bu Python dasturlash tilida yozilgan konsol ilovasi bo‘lib, foydalanuvchiga kontaktlar bilan quyidagi funksiyalarni bajarish imkonini beradi:

* ➕ Yangi kontakt qo‘shish
* 📄 Barcha kontaktlarni ko‘rish
* 🔍 Ism bo‘yicha qidirish
* 📧 Faqat `@gmail.com` domenli kontaktlarni ko‘rish

Kontaktlar `list[str]` ko‘rinishida `"name|phone|email"` formatda saqlanadi.

---

### 📂 Foydalanish

#### 🛠️ Dastur qanday ishga tushiriladi:

```bash
python main.py
```

---

### 📋 Menyu imkoniyatlari:

| Raqam | Amaliyot                              |
| ----- | ------------------------------------- |
| 1     | Yangi kontakt qo‘shish                |
| 2     | Barcha kontaktlarni ko‘rish           |
| 3     | Kontaktni ism bo‘yicha qidirish       |
| 4     | Faqat @gmail.com kontaktlarni ko‘rish |
| 5     | Dasturni yakunlash                    |

---

### 📌 Texnologiyalar

* **Til:** Python 3.9+
* **Typing:** `List[str]`
* **Uslub:** Google docstring style
* **Xavfsizlik:** `try-except` ishlatilmagan — inputlar if orqali tekshiriladi

---

### 📚 Namuna kontaktlar

```text
Ali|998901234567|ali@gmail.com
Vali|998911112233|vali@yahoo.com
Sami|998939998877|sami@gmail.com
```

---

### 🚫 Xatoliklar oldini olish

* Foydalanuvchi noto‘g‘ri tanlov kiritsa ogohlantiriladi
* Har bir kontakt kiritish paytida ism, telefon va email bo‘sh qolmasligi shart
* `"|"` belgisi orqali bo‘linmagan noto‘g‘ri formatdagi kontaktlar aniqlanadi

---

### ✅ Kelajakdagi imkoniyatlar (rejalashtirilgan)

* [ ] Faylga saqlash (`save to .txt` yoki `.json`)
* [ ] Fayldan o‘qish (`load on startup`)
* [ ] Kontaktni tahrirlash
* [ ] Kontaktni o‘chirish
* [ ] Foydalanuvchi interfeysi uchun GUI (Tkinter yoki PyQt)

---

### 📄 Litsenziya

Bu loyiha ochiq kodli va o‘rganish maqsadida yaratilgan. Xohlagan tarzda foydalanishingiz mumkin.
