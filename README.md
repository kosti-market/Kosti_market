# 👜 Best Bags | عالم الأناقة النسائية

![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Best Bags** هو متجر إلكتروني عصري متكامل مخصص لعرض وبيع الحقائب النسائية الفاخرة. يجمع المشروع بين التصميم البصري المتناغم (UI) وتجربة المستخدم السلسة (UX) مع لوحة تحكم ذكية للإدارة.

---

## ✨ المميزات الرئيسية

* **🎨 هوية بصرية متسقة:** تصميم أنيق يعتمد على درجات الوردي والذهبي لضمان تجربة تسوق راقية.
* **📱 استجابة كاملة (Responsive):** تصميم "Mobile-First" يعرض المنتجات بشكل جذاب على الهواتف والأجهزة اللوحية.
* **🖼️ تجربة عرض تفاعلية:** معرض صور يدعم السحب (Swipe) لعرض تفاصيل الحقيبة من كافة الزوايا.
* **🔐 نظام إدارة متطور (Admin Dashboard):**
    * إضافة منتجات جديدة مع رفع الصور سحابياً.
    * تعديل الأسعار والمواصفات بشكل فوري.
    * حذف المنتجات من المتجر بضغطة زر.
* **💬 طلب سريع:** زر تواصل مباشر عبر واتساب يقوم بإنشاء طلب مفصل يحتوي على اسم المنتج وسعره تلقائياً.
* **🚀 أداء فائق:** استخدام **Supabase** كقاعدة بيانات خلفية لضمان سرعة استجابة البيانات وتخزين الصور.

---

## 🛠️ التقنيات المستخدمة

* **Frontend:** HTML5, CSS3, JavaScript (ES6+).
* **Styling:** [Tailwind CSS](https://tailwindcss.com/) للتنسيق السريع والمرن.
* **Database & Auth:** [Supabase](https://supabase.com/) لإدارة البيانات والمصادقة.
* **Animations:** [AOS.js](https://michalsnik.github.io/aos/) لإضافة حركات انسيابية عند التمرير.
* **Typography:** خطوط **Cairo** و **Reem Kufi** من Google Fonts لضمان وضوح النص وجمالية الخط العربي.

---

## ⚙️ إعداد المشروع

لتشغيل هذا المتجر على جهازك أو استضافته:

1.  **إعداد قاعدة البيانات:**
    * أنشئ مشروعاً جديداً على [Supabase](https://supabase.com/).
    * أنشئ جدولاً باسم `products` يحتوي على الأعمدة: `id, name, price, description, images (text array)`.
    * قم بتفعيل الـ `Storage` وأنشئ Bucket باسم `product-images` واجعله `Public`.

2.  **ربط الكود:**
    * قم بتعديل قيم `SUPABASE_URL` و `SUPABASE_KEY` داخل ملف الـ HTML ببيانات مشروعك الخاصة.

3.  **التشغيل:**
    * ببساطة افتح ملف `index.html` في أي متصفح حديث.

---
🤝 المساهمة (Contributing)
إذا كنت ترغب في تطوير المشروع:
1.	قم بعمل Fork للمستودع.
2.	أنشئ فرعاً جديداً (Branch).
3.	قم بعمل Commit لتغييراتك.
4.	أرسل Pull Request.
📞 التواصل (Contact)
تم تطوير هذا المشروع بكل ❤️ لـ Best Bags.
• المطور: [محمود عبدالله]
• واتساب المتجر: [+249900623733]
حقوق النشر © 2026 - Best Bags
---

## 📂 هيكل الملفات

```text
├── index.html          # كود الواجهة الأمامية والمنطق البرمجي
└── README.md           # توثيق المشروع (هذا الملف)


