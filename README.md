# teachable-classifier-renad
مشروع لتصنيف الصور باستخدام Google Teachable Machine وتنفيذه على Google Colab باستخدام Keras، ضمن متطلبات التدريب في Smart Methods.
---
## 🧠 فكرة المشروع:
تم تدريب نموذج باستخدام Teachable Machine لتصنيف نوعين من الصور (أنواع الزهور)
بعد ذلك تم تصدير النموذج وتشغيله باستخدام Python على Google Colab
---
## 🗂️ محتويات المشروع:

| الملف | الوصف |
|-------|-------|
| keras_model.h5 | النموذج المدرب باستخدام Teachable Machine |
| labels.txt | أسماء الفئات المستخدمة في التدريب |
| test.jpg.jpg | صورة تم اختبار النموذج عليها |
| python_code.ipynb | كود بايثون لتشغيل النموذج داخل Google Colab |
| output.png | لقطة شاشة توضح نتيجة تشغيل النموذج |
| teachable_screenshot.jpg | لقطة شاشة من داخل Teachable Machine توضح إعدادات النموذج |
---
## ✅ نتيجة التصنيف:
![تصنيف الصورة](https://raw.githubusercontent.com/ibxzr/teachable-classifier-renad/main/output.png)
---
## 🖼️ صورة التجربة المستخدمة:

![test image](https://raw.githubusercontent.com/ibxzr/teachable-classifier-renad/main/test.jpg.jpg)
---
## 🧠 لقطة من Teachable Machine:

![Teachable Machine](https://raw.githubusercontent.com/ibxzr/teachable-classifier-renad/main/teachable_screenshot.jpg)

---
## 📌 خطوات التنفيذ:

1. تدريب نموذج باستخدام [Teachable Machine](https://teachablemachine.withgoogle.com/)
2. تصدير النموذج بصيغة Keras
3. تحميل النموذج إلى Google Colab وتشغيل كود التصنيف (`python_code.ipynb`)
4. عرض النتيجة والتأكد من عمل النموذج بشكل صحيح
---
## ✨ تم تنفيذ المشروع بواسطة:
رناد أمين فيض – ضمن تدريب الأساليب الذكيىة
