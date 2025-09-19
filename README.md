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




data/ 📂 Project data root

interim/ 🧪 Temporary / intermediate artifacts

meta_seed.csv 🎲 Random seed + meta info

processed_meta.csv 🧾 Cleaned metadata

splits.json 🔀 Split mapping

processed/ 🛠️ Model-ready data

train/ 🎓 Training set

healthy/ ✅

ulcer/ 🩹

val/ 🧪 Validation set

healthy/ ✅

ulcer/ 🩹

test/ 🧭 Final test set

healthy/ ✅

ulcer/ 🩹

raw/ 📦 Raw, untouched source data

images/ 🖼️

healthy/ ✅

ulcer/ 🩹

images_test_final/ 📊

