# فريدة جاليري | Farida Gallery

موقع بسيط (ملف `index.html` واحد + فولدر `images`).

## تعديل المنتجات

افتح `index.html` وعدّل مصفوفة `PRODUCTS`:

```js
{
  name: "اسم المنتج",
  price: "350 جنيه",
  desc: "وصف قصير للمنتج",
  img: "images/1.jpg",
  cat: "عروض"
}
```

## رقم الواتساب

في أول الـ `script` داخل `index.html`:

```js
const WHATSAPP = "201000000000"; // ← بالكود الدولي بدون +
```

## الصور

- الصور في فولدر `images/`
- الأفضل عرض 1000 بكسل وحجم أقل من 200 كيلوبايت
- الضغط على صورة المنتج بيفتحها بحجم كبير
- لو الصورة مش موجودة هيظهر مربع بوردو بدالها

## النشر

GitHub Pages من فرع `main` (root).

الرابط: https://abdelrhamanadel4-Flutter.github.io/farida-gallery/
