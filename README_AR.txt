تحديثات PageSpeed لموقع Together Photographer

استبدل الملفات الموجودة بنفس المسارات:
1) public/index.html
2) server.js
3) data/db.json
4) public/assets/hero-concept.webp
5) public/uploads/logo-public.webp

مهم:
- لا تحذف ملفات المشروع الأصلية الآن.
- لا تحذف hero-concept.png أو صور اللوجو الأصلية؛ تم إبقاؤها كنسخ احتياطية.
- بعد الاستبدال افتح GitHub Desktop، راجع التغييرات، ثم Commit وPush.
- بعد نجاح Railway، نعيد اختبار PageSpeed.

أهم الإصلاحات:
- ضغط hero-concept إلى WebP.
- إنشاء نسخة WebP صغيرة للوجو.
- إضافة main landmark.
- تحسين تباين زر/رابط الهاتف.
- إزالة preload المكرر للصورة الرئيسية.
- إضافة caching للملفات الثابتة.
- تأجيل analytics إلى وقت الخمول لتقليل ضغط JavaScript أثناء التحميل.
