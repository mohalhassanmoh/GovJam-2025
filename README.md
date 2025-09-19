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
- **notebooks/** → يحتوي على ملفات Colab للتجارب.  
- **data/** → بيانات التدريب (مجلد فارغ مع روابط للتحميل).  
- **models/** → المخرجات والنماذج المدربة.  
- **reports/** → صور ونتائج تجريبية (heatmaps, Grad-CAM, metrics).  

---

## ⚙️ طريقة التشغيل
1. **استنساخ المستودع:**
   ```bash
!git clone  https://github.com/mohalhassanmoh/GovJam-2025
!mv /content/GovJam-2025/configs /content/
!mv /content/GovJam-2025/data /content/
!mv /content/GovJam-2025/models /content/
!mv /content/GovJam-2025/reports /content/
!rm -r /content/GovJam-2025

## 🚀 Quick Start
لتجربة النموذج مباشرة على Google Colab اضغط الزر:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<username>/<repo-name>/blob/main/notebook.ipynb)
