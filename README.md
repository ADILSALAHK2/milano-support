# Milano Rank — Support & Privacy

موقع عربي ثابت لصفحات الدعم والخصوصية، يتضمن البريد alhal.iraq@gmail.com ورقم الدعم الموجود في التطبيق.

## Hostinger
ارفع محتويات مجلد dist إلى مجلد الموقع المستهدف داخل public_html. استخدم مجلدًا أو نطاقًا فرعيًا مستقلًا إذا كان الموقع الحالي يحتوي ملفات بالفعل.

- صفحة الدعم: /support/
- سياسة الخصوصية: /privacy/

لا يحتاج المشروع Node أو PHP أو قاعدة بيانات. الخط والأيقونة محليان.

## المعاينة المحلية
```sh
python3 -m http.server 8765 --directory dist
```

## GitHub Pages
يمكن نشر مجلد dist عبر GitHub Actions أو رفع محتوياته إلى جذر الفرع المخصص للنشر. الروابط نسبية وتدعم مسار المستودع.

ملف .openai/hosting.json خاص بنسخة Sites ويُستبعد من حزمة GitHub وHostinger.
