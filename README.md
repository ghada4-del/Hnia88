طريقة رفع هاد الموقع على GitHub Pages (بسيطة):
1. فحساب GitHub دير repository جديد Public (مثلاً hnia77).
2. فالكومبيوتر: فك الضغط ديال site.zip و غادي تلقى index.html.
3. ارفع الملفات للمخزن (push) أو عن طريق رفع الملفات مباشرة في GitHub web UI.
4. فـ Settings ديال repository → Pages، اختار branch: main (أو gh-pages) و path: /(root)، وحفظ.
5. غادي يبان ليك رابط الموقع بعد شوية (gh-pages takes a minute).

ملاحظة: هاد النسخة ما كتحتاجش build tools بحال Vite/CRA: هو HTML ثابت مع Tailwind Play CDN.