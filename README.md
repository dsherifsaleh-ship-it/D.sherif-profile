# بطاقة د. شريف صالح الرقمية

## الملفات
- `index.html` — البطاقة كاملة (عربي / English، حفظ جهة الاتصال، QR).
- `profile.jpg` — الصورة الشخصية (أيقونة الصفحة ومعاينة الرابط في واتساب).

## خطوات الرفع على GitHub Pages
1. أنشئ مستودعًا جديدًا عامًا (Public) باسم `card`.
2. ارفع الملفين `index.html` و`profile.jpg` كما هما (Add file ← Upload files ← Commit).
3. من Settings ← Pages: اختر Branch = `main` والمجلد `/ (root)` ثم Save.
4. بعد دقيقة تقريبًا تعمل البطاقة على:
   `https://USERNAME.github.io/card/`

## تعديل واحد ضروري
افتح `index.html` واستبدل كلمة `USERNAME` باسم حسابك على GitHub (استخدم «بحث واستبدال» لتغييرها في كل مكان):
في `cardUrl` وفي سطري `og:image` و`og:url`.
بهذا يصبح رمز QR ثابتًا، وتظهر صورتك عند مشاركة الرابط.

## روابط جاهزة لكروت NFC
- عربي: `https://USERNAME.github.io/card/`
- English: `https://USERNAME.github.io/card/?lang=en`
