# فريدة جاليري | Farida Gallery

الموقع: https://faridagallery.github.io

## إضافة / تعديل المنتجات (من غير كود)

افتح لوحة التحكم:

**https://faridagallery.github.io/admin.html**

### أول مرة بس
1. اعمل GitHub Token من https://github.com/settings/tokens/new?scopes=repo&description=Farida%20Gallery%20Admin
2. اختار صلاحية **repo** واعمل Generate
3. الصق التوكن في لوحة التحكم واضغط **دخول**

التوكن بيتخزن في المتصفح بس، ومش بيتحفظ في الموقع.

### بعد كده
- **إضافة منتج**: اكتب الاسم والسعر والوصف، اختار القسم (أو اكتب قسم جديد)، واختار صورة → **حفظ المنتج**
- **تعديل**: دوس "تعديل" جنب المنتج
- **حذف**: دوس "حذف"
- **ترتيب**: أسهم ↑ ↓
- الصور بتتصغّر أوتوماتيك (أقصى عرض 1000 بكسل) قبل الرفع
- التحديث بيظهر على الموقع خلال دقيقة–دقيقتين

## الأقسام

الترتيب في `products.json` تحت `sections`. أي قسم جديد بيتضاف تلقائيًا آخر القائمة.

## رقم الواتساب

في `index.html`:

```js
const WHATSAPP = "201228052906";
```

## ملفات المشروع

- `index.html` — الصفحة الرئيسية
- `admin.html` — لوحة التحكم
- `products.json` — بيانات المنتجات والأقسام
- `images/` — صور المنتجات

## النشر

GitHub Pages من فرع `main` (root) — ريبو `Faridagallery/Faridagallery.github.io`.
