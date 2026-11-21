فوريرا PWA - جاهز لـ PWABuilder
================================
1) ارفع محتويات هذا المجلد كما هي (index.html في الجذر) على استضافة HTTPS:
   Netlify / Cloudflare Pages / GitHub Pages / Vercel ...
   (ملف _headers خاص بـ Netlify و Cloudflare Pages)
2) افتح https://www.pwabuilder.com والصق رابط موقعك واضغط Start.
3) اختر Package for stores لتحصل على Android (Google Play) / iOS / Windows.

ملاحظات:
- للاختبار محليًا: python3 -m http.server 8000 ثم http://localhost:8000
- لحزمة Android (TWA) ستحتاج لاحقًا إلى ملف /.well-known/assetlinks.json يولّده لك PWABuilder.
