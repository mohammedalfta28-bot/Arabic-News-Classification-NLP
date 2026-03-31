# تصنيف النصوص الإخبارية العربية باستخدام AraBERT
# Arabic News Classification using AraBERT

## 📝 وصف المشروع (Project Description)
هذا المشروع عبارة عن نظام "تصنيف نصوص" (Text Classification) مبني باستخدام نموذج **BERT** (تحديداً **AraBERT**) لتصنيف الأخبار العربية إلى أربع فئات رئيسية:
1. **سياسة**
2. **اقتصاد**
3. **رياضة**
4. **طقس**

تم تطوير المشروع كجزء من تكليف مادة معالجة اللغات الطبيعية (NLP).

## 🚀 التقنيات المستخدمة (Tech Stack)
* **Python**
* **Hugging Face Transformers** (Library for BERT)
* **AraBERT** (Pre-trained Arabic Language Model)
* **Google Colab** (GPU Acceleration)
* **Farasa Segmenter** (For Arabic Preprocessing)

## 📂 هيكل المشروع (Project Structure)
* `notebooks/`: يحتوي على ملف الكود الكامل مع الشرح.
* `README.md`: ملف التعريف بالمشروع.

## ⚙️ كيفية التشغيل (How to Run)
1. قم برفع ملف الـ `.ipynb` إلى Google Colab.
2. تأكد من تفعيل الـ **GPU** من إعدادات الـ Runtime.
3. قم بتشغيل الخلايا بالترتيب.

## 📊 النتائج (Results)
النموذج قادر على التنبؤ بالفئات بنسبة دقة عالية جداً بفضل عملية الـ Fine-tuning التي تمت على بيانات إخبارية عربية متنوعة.
