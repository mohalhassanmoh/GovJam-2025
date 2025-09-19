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

├─ interim/                              🧪 Temporary / intermediate artifacts

│  ├─ meta_seed.csv                      🎲 Random seed + meta info for reproducible splits

│  ├─ processed_meta.csv                 🧾 Cleaned metadata (paths, sizes, labels)

│  └─ splits.json                        🔀 Train/val/test split mapping (filenames/IDs)
├─ processed/                            🛠️ Model-ready data
│  ├─ train/                             🎓 Training set
│  │  ├─ healthy/                        ✅ “Healthy” training images
│  │  └─ ulcer/                          🩹 “Ulcer” training images
│  ├─ val/                               🧪 Validation set (during training)
│  │  ├─ healthy/                        ✅ “Healthy” validation images
│  │  └─ ulcer/                          🩹 “Ulcer” validation images
│  └─ test/                              🧭 Final test set (no peeking)
│     ├─ healthy/                        ✅ “Healthy” test images
│     └─ ulcer/                          🩹 “Ulcer” test images
└─ raw/                                  📦 Raw, untouched source data
   ├─ images/                            🖼️ Primary raw image source
   │  ├─ healthy/                        ✅ Raw “healthy” images
   │  └─ ulcer/                          🩹 Raw “ulcer” images
   └─ images_test_final/                 📊 External/final test set for reporting only

- **models/** → المخرجات والنماذج المدربة.  
- **reports/** → صور ونتائج تجريبية (heatmaps, Grad-CAM, metrics).  

---

## 🚀 Quick Start
لتجربة النموذج مباشرة على Google Colab اضغط الزر:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mohalhassanmoh/GovJam-2025/blob/main/GovJam_2025.ipynb
)





data/                                   📂 Project data root
├─ interim/                              🧪 Temporary / intermediate artifacts
│  ├─ meta_seed.csv                      🎲 Random seed + meta info for reproducible splits
│  ├─ processed_meta.csv                 🧾 Cleaned metadata (paths, sizes, labels)
│  └─ splits.json                        🔀 Train/val/test split mapping (filenames/IDs)
├─ processed/                            🛠️ Model-ready data
│  ├─ train/                             🎓 Training set
│  │  ├─ healthy/                        ✅ “Healthy” training images
│  │  └─ ulcer/                          🩹 “Ulcer” training images
│  ├─ val/                               🧪 Validation set (during training)
│  │  ├─ healthy/                        ✅ “Healthy” validation images
│  │  └─ ulcer/                          🩹 “Ulcer” validation images
│  └─ test/                              🧭 Final test set (no peeking)
│     ├─ healthy/                        ✅ “Healthy” test images
│     └─ ulcer/                          🩹 “Ulcer” test images
└─ raw/                                  📦 Raw, untouched source data
   ├─ images/                            🖼️ Primary raw image source
   │  ├─ healthy/                        ✅ Raw “healthy” images
   │  └─ ulcer/                          🩹 Raw “ulcer” images
   └─ images_test_final/                 📊 External/final test set for reporting only



   data/                                   📂 Project data root
├─ interim/                              🧪 Temporary / intermediate artifacts
│  ├─ meta_seed.csv                      🎲 Random seed + meta info for reproducible splits
│  ├─ processed_meta.csv                 🧾 Cleaned metadata (paths, sizes, labels)
│  └─ splits.json                        🔀 Train/val/test split mapping (filenames/IDs)
├─ processed/                            🛠️ Model-ready data
│  ├─ train/                             🎓 Training set
│  │  ├─ healthy/                        ✅ "Healthy" training images
│  │  └─ ulcer/                          🩹 "Ulcer" training images
│  ├─ val/                               🧪 Validation set (during training)
│  │  ├─ healthy/                        ✅ "Healthy" validation images
│  │  └─ ulcer/                          🩹 "Ulcer" validation images
│  └─ test/                              🧭 Final test set (no peeking)
│     ├─ healthy/                        ✅ "Healthy" test images
│     └─ ulcer/                          🩹 "Ulcer" test images
└─ raw/                                  📦 Raw, untouched source data
   ├─ images/                            🖼️ Primary raw image source
   │  ├─ healthy/                        ✅ Raw "healthy" images
   │  └─ ulcer/                          🩹 Raw "ulcer" images
   └─ images_test_final/                 📊 External/final test set for reporting only


