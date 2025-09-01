# ورشة عمل المبادئ والتطبيقات في المعلوماتية الصحية والحيوية: تحليل الطفرات الجينية وربطها بالبيانات الإكلينيكية باستخدام لغة R 🧬💻
### ورشة ستٌقام يوم 2-3 سبتمبر 2025. بالتعاون بين منصة [دَالة](https://www.linkedin.com/company/dalah/) مع منصة [مواهب معلوماتية](https://informatalents.com/).
---
<br><br>

## ✍🏻 نبذة
هذه الورشة عبارة عن **يومين** سنتحدث فيها عن:

- **اليوم الأول:** مقدمة للغة R مع تنظيف البيانات وترتيبها واستكشافها بصريًا.
- 
- **اليوم الثاني:** تحليل بيانات الطفرات الجينية بصيغة **MAF** باستخدام **maftools**، ودمجها مع البيانات الإكلينيكية، وإجراء تحليلات إحصائية وتحليلات البقاء، إلى جانب استكشاف **الأدوية** المناسبة.

جميع الأكواد مُضمّنة في ملفات R Markdown وقابلة للتشغيل مباشرةً.

---
<br><br>

## 💡 مخرجات التعلّم
بنهاية الورشة ستكون قادرًا على:
1. تهيئة بيئة عمل R وتحميل الحزم اللازمة.
2. قراءة بيانات وصفية (Metadata) واستكشافها وتنظيفها باستخدام **skimr** و**dplyr**.
3. إنشاء ملخصات ورسوم بيانية (barplot, ggplot2) لأنواع المتغيرات السريرية.
4. قراءة ملفات **MAF** واستكشاف بنية بيانات الطفرات.
5. إنتاج مخططات **plotmafSummary** و**oncoplot** وتفسيرها.
6. إجراء **Clinical Enrichment** وربط الطفرات بخصائص مثل الجنس والعلاج الإشعاعي.
7. تنفيذ **تحليل البقاء** عبر ربط طفرة واحدة أو أكثر بمدة عيش المصاب.
8. استخراج العلاقة بين **الأدوية والجينات**، واكتشاف المسارات الورمية المتأثرة بالطفرات.
---
<br><br>


## 🚀 المتطلبات المسبقة
إذا كنت مهتما بالتطبيق العملي أثناء الورشة، فيُقضل تحميل برنامج R studio للتمكن من تشغيل الأكواد أثناء عرضها. يمكنك معرفة تفاصيل التحميل من هنا:
[تثبيت R و RStudio - شرح الواجهة](https://www.dalah.info/%D8%AF%D8%B1%D9%88%D8%B3/%D8%B3%D9%84%D8%B3%D8%A9-%D8%AA%D8%B9%D9%84%D9%85-%D9%84%D8%BA%D8%A9-r-%D8%A7%D9%84%D8%A8%D8%B1%D9%85%D8%AC%D9%8A%D8%A9/%D8%A7%D9%84%D8%AF%D8%B1%D8%B3-%D8%A7%D9%84%D8%AB%D8%A7%D9%86%D9%8A-%D8%AA%D8%AB%D8%A8%D9%8A%D8%AA-r-%D9%88-r-studio-%D8%B4%D8%B1%D8%AD-%D9%88%D8%A7%D8%AC%D9%87%D8%A9-rstudio)

---
<br><br>




## 📚 المراجع

- Data: The ICGC/TCGA Pan-Cancer Analysis of Whole Genomes Consortium. Pan-cancer analysis of whole genomes. Nature 578, 82–93 (2020). https://doi.org/10.1038/s41586-020-1969-6
- maftools: https://github.com/PoisonAlien/maftools
- ggplot2: https://ggplot2.tidyverse.org/
- skimr: https://docs.ropensci.org/skimr
- dplyr: https://dplyr.tidyverse.org
- tidyverse: https://www.tidyverse.org


---
<br><br>


  ## 😊 التواصل:
  لأي ملاحظة أو استفسار تخص ورشة العمل هذه، يمكنك التواصل مع الدعم الفني لفريق دَالة: support@dalah.org
<img src="sc/dallah_logo_circle.png" alt="logo" width="60" align="left" />

<br><br>
<br><br>
<p align="center">
  <a href="https://x.com/Dalah_Info">
    <img src="https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white" alt="X" />
  </a>
  <a href="https://www.linkedin.com/company/dalah/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://www.youtube.com/@Dalah-info">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white" alt="YouTube" />
  </a>
  <a href="https://www.dalah.info">
    <img src="https://img.shields.io/badge/Website-21759B?style=flat&logo=google-chrome&logoColor=white" alt="Website" />
  </a>
</p>



  
  
  





