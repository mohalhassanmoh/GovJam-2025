# GovJam-2025
AI prototype for diabetic foot ulcer triage – GovJam 2025 Innovation Challenge


<div align="center">
  <img src="data/Saudi.jpeg"  width="500">
</div>

# GovJam 2025 – AI Prototype for Diabetic Foot Ulcer Triage

🚀 **نموذج أولي** (Prototype) تم تطويره للمشاركة في **تحدي الابتكار GovJam 2025**.  
الهدف هو تسريع عملية **تحديد أولوية العلاج للمرضى المصابين بالقدم السكري** باستخدام تقنيات الذكاء الاصطناعي، مما يساهم في تقليل التأخير وتجنب المضاعفات الخطيرة.

---

## 📂 مكونات المشروع
- **GovJam_2025.ipynb** → لتجربة النموذج مباشرة على Google Colab  
- **data/** →                            📂 Project data root
- **models/** → المخرجات والنماذج المدربة.  
- **reports/** → صور ونتائج تجريبية (heatmaps, Grad-CAM, metrics).  

---

## 🚀 Quick Start
لتجربة النموذج مباشرة على Google Colab اضغط الزر:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mohalhassanmoh/GovJam-2025/blob/main/GovJam_2025.ipynb
)


---
---

# GovJam 2025 — AI Prototype for Diabetic Foot Ulcer Triage

نموذج أولي يستخدم الذكاء الاصطناعي لتسريع **تحديد أولوية العلاج** لمرضى **القدم السكري**. يقدّم النظام تصنيفًا فوريًا لمستوى الخطورة مع شرح بصري (Grad-CAM) واقتراحات أولية للإجراء التالي، بهدف تقليل التأخير في تقديم الرعاية وتجنب المضاعفات الخطيرة.

---

## 🎯 الهدف
- تقليل زمن الفرز (Triage) عبر تنبؤ آلي بمستوى الخطورة من صور القدم.
- دعم القرار السريري بإظهار مناطق الاشتباه بصريًا وملخص توصيات أولية.
- تمهيد الطريق لدمج الذكاء الاصطناعي في مسارات العمل السريرية الواقعية.

---

## ✨ المزايا الرئيسية
- **تصنيف ثنائي للمخاطر**: (High / Medium / Low) مع احتمال p(ulcer).
- **Grad-CAM**: إبراز المناطق الأكثر إسهامًا في القرار لزيادة الشفافية.
- **تقدير تقريبي للمساحة المتأثرة** من خريطة التفعيل (للدعم وليس للتشخيص).
- **واجهة تفاعلية Gradio**: رفع الصورة → نتيجة فورية → حفظ تقرير بصيغة PNG/PDF.
- **سجلّات تشغيل**: CSV للنتائج والكمون (latency) وضبط الإعدادات من YAML.
- **تشغيل مرن**: على Colab أو محليًا (Python/PyTorch).

---

## 🧱 البنية التقنية (Tech Stack)
- Python, PyTorch, Torchvision
- EfficientNet-B0 (قابلة للاستبدال بنماذج أخرى مثل ResNet-18)
- Gradio لواجهة المستخدم
- Grad-CAM للتفسير البصري
- YAML لإدارة الإعدادات

---

## 🗂️ هيكل المستودع (مختصر)
