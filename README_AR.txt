ADCO Smart Daily Plan v13 - Android APK GitHub Build FINAL FIX

الإصلاحات:
- حذف appcompat لتجنب Duplicate Kotlin Classes.
- حذف androidx.annotation.Nullable لأن المشروع أصبح بدون AndroidX.
- التطبيق WebView مباشر ويحتوي على نسخة v13.

طريقة الاستخدام:
1. ارفع محتويات هذا الفولدر على GitHub بدل الملفات القديمة.
2. المهم تحدث هذه الملفات:
   app/src/main/java/com/adco/smartdailyplan/MainActivity.java
   app/build.gradle
   gradle.properties
3. افتح Actions.
4. شغل Build ADCO v13 APK.
5. بعد النجاح نزّل Artifact:
   ADCO-v13-Smart-Daily-Plan-APK
6. ستجد داخله app-debug.apk
