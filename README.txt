طريق البرنابيو - مشروع Android Studio

1) افتح المجلد Bernabeu في Android Studio وسيبه يعمل Sync.
2) (اختياري للّعب بدون نت) نزّل الملف:
   https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js
   وحطه في app/src/main/assets/ جنب index.html
   من غيره اللعبة بتحمّل المكتبة من النت أول ما تفتح.
3) Build > Build Bundle(s) / APK(s) > Build APK(s)
4) الملف هيطلع في app/build/outputs/apk/debug/app-debug.apk
5) انقله للتليفون وثبّته (فعّل "تثبيت من مصادر غير معروفة").

على GitHub:
ارفع المجلد كله على ريبو، وروح تبويب Actions > Build APK > Run workflow.
بعد ما يخلص نزّل app-debug.apk من Artifacts (اسمه bernabeu-apk).
الـ workflow بينزّل three.js لوحده فاللعبة بتشتغل أوفلاين.
