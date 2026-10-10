اختارها - Android MVP 0.1

هذا مشروع Android حقيقي وليس ZIP للويب.
التطبيق يحتوي على واجهة WebView محلية، ولا يحتاج إنترنت لكي يفتح النسخة التجريبية.

البناء:
1) افتح المشروع في بيئة Android/IDE تدعم Gradle وAndroid SDK.
2) نفّذ Gradle task: :app:assembleDebug
3) ستجد APK في:
   app/build/outputs/apk/debug/app-debug.apk

مهم:
- هذه نسخة MVP محلية: التصويت محفوظ على نفس الجهاز.
- ليست النسخة الاجتماعية النهائية.
- للنشر على Google Play سنحتاج لاحقًا AAB موقّع + backend + حسابات + سياسة خصوصية + إشراف على المحتوى.
- لم أضع Gradle wrapper لأن وجود Android SDK/Gradle يختلف حسب بيئة البناء؛ يمكن للبيئة التي ستبني المشروع توليده/استخدام Gradle المثبت.
