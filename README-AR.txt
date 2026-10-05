TaskMate - مشروع GitHub (تطبيق ويب + بناء APK)
================================================
1) افتح github.com وأنشئ مستودعاً جديداً (New repository)، اسمه مثلاً taskmate، واجعله Public.
2) افتح المستودع: Add file > Upload files، واختر كل ملفات هذا المجلد، ثم Commit changes.
3) أنشئ ملف الـ APK: Add file > Create new file، اكتب الاسم بالضبط:
      .github/workflows/android.yml
   والصق داخله محتوى الملف android.yml المرفق، ثم Commit.
4) لبناء APK: تبويب Actions > Build Android APK > Run workflow. انتظر حوالي 5-10 دقائق.
   عند النجاح افتح التشغيل (run) ونزّل TaskMate-APK من أسفل الصفحة (Artifacts).
5) لنشر رابط ويب: Settings > Pages > Source: Deploy from a branch > Branch: main / (root) > Save.
   يظهر الرابط بعد دقيقة: https://اسم-المستخدم.github.io/taskmate/

ملاحظات:
- لم أجرّب البناء على GitHub فعلياً. إن فشل أرسل لي صورة سجل الخطأ وأصلحه.
- ملف الـ APK الناتج موقّع بمفتاح اختبار (debug)، يصلح للتثبيت المباشر على الجوال، وقد لا تقبله بعض المتاجر.
