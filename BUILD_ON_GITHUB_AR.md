# بناء اختارها من الموبايل عبر GitHub Actions

1. أنشئ Repository جديد على GitHub.
2. ارفع كل محتويات هذا المجلد إلى الفرع `main`.
3. افتح تبويب Actions.
4. شغّل workflow باسم Build Ekhtarha APK.
5. بعد نجاح البناء افتح صفحة الـworkflow ثم Artifacts.
6. حمّل `Ekhtarha-debug-apk` وفك الضغط للحصول على `app-debug.apk`.

ملاحظة:
هذا الـworkflow يستخدم Gradle المثبت على runner، لذلك لا يحتاج Gradle Wrapper في هذه النسخة.
الـAPK الناتج Debug للتجربة، وليس ملف الإنتاج النهائي للنشر على Google Play.
