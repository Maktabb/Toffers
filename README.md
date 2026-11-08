# مشروع تأسيس شركات — نسخة الفريق (إنشاء وتعديل العروض + المعتمد بدون حسابات)
مكتب محمود سالم للمحاسبة والمراجعة وتأسيس الشركات

## تشغيله كموقع (GitHub Pages)
Settings ← Pages ← Source: Deploy from a branch ← Branch: main / (root) ← Save.
الرابط: `https://<اسم-الحساب>.github.io/<اسم-الريبو>/` — افتحيه من الموبايل واختاري «إضافة للشاشة الرئيسية».

## المجلدات
- `index.html` + `sw.js` + `manifest.webmanifest`: النسخة الجاهزة (تشتغل أوفلاين).
- `source/quote-generator.html`: الكود المصدر.
- `android/`: مشروع الـ APK (`bash build.sh` يحتاج Android SDK ومفتاح التوقيع `keystore.jks` — المفتاح **مش** مرفوع للأمان، احتفظي بنسخة منه).

## المزامنة
🗂️ أرشيف ← «مزامنة سحابية» ← رابط Apps Script وكلمة السر.

> خلّي الريبو **Private**.
