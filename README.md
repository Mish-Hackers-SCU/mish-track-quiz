<div align="center">

# 🎯 Mish Hackers - Technical Tracks Quiz

**تطبيق ويب تفاعلي لاكتشاف المسار التقني الأنسب للطلاب باستخدام خوارزمية الـ Fuzzy Logic.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](#)

</div>

---

## 📌 عن المشروع (About The Project)

تم تطوير هذا التطبيق لصالح فرع **Mish Hackers**، وهو عبارة عن اختبار شخصية تقني (Personality Quiz) مصمم خصيصاً لفعاليات استقبال الطلاب (Orientation & Student Activities). 
يحتوي الاختبار على 30 سؤالاً مبسطاً يقيس طريقة تفكير المستخدم، ميوله، وطريقة حله للمشكلات (بدون تعقيدات برمجية)، ليوجهه في النهاية للمسار التقني الذي يتوافق مع شخصيته بنسبة مئوية دقيقة.

## ✨ المميزات (Features)

- **🧠 خوارزمية Fuzzy Logic:** تقييم دقيق لا يكتفي بإجابة واحدة (Crisp)، بل يوزع النقاط (Weights) على عدة مسارات متداخلة ليحسب نسبة التوافق المئوية لكل مسار.
- **📱 متجاوب بالكامل (Mobile-First):** تصميم احترافي وسريع مخصص للعمل بسلاسة على شاشات الهواتف عند مسح الـ QR Code في الفعاليات.
- **🎨 هوية بصرية مميزة:** واجهة مستخدم تعكس هوية "Mish Hackers" بطابع مستوحى من الفن الياباني والساموراي بألوان متناسقة وتأثيرات حركية (Animations) جذابة.
- **💾 حفظ التقدم (Auto-Save):** استخدام الـ `localStorage` لضمان عدم ضياع إجابات المستخدم إذا قام بتحديث الصفحة عن طريق الخطأ.
- **⚡ تطبيق Client-Side بالكامل:** لا يحتاج إلى خوادم خلفية (Backend)، مما يجعله فائق السرعة ومجانياً في الاستضافة.

---

## 🚀 المسارات التقنية المدعومة (The 10 Tracks)

يقوم الاختبار بحساب نسبة توافق المستخدم مع 10 مسارات تقنية رئيسية:

1. Front-end web developer
2. Back-end web developer
3. Data Scientist
4. Cloud Architect
5. Game Developer
6. Software Developer
7. AI Engineer
8. Cybersec Analyst
9. DevOps Specialist
10. Database Admin

---

## ⚙️ كيف يعمل الاختبار؟ (The Logic)

يعتمد التطبيق على نظام **Weighted Matrix Scoring System**:
1. يتكون الاختبار من 30 سؤالاً، كل سؤال يحتوي على 4 اختيارات.
2. كل اختيار لا يشير إلى مسار واحد، بل يحمل أوزاناً (Weights) موزعة على أقرب المسارات المتداخلة (مثال: اختيار معين قد يضيف 4 نقاط للـ Data Scientist و نقطتين للـ AI Engineer).
3. مع كل إجابة، يتم تجميع النقاط في الخلفية.
4. في النهاية، يتم عمل **Normalization** للنقاط لتتحول إلى نسبة مئوية (Percentage) تعرض مدى توافق المستخدم مع كل مسار من الـ 10.

---

## 🛠️ التقنيات المستخدمة (Tech Stack)

- **HTML5** & **CSS3**
- **Tailwind CSS** (عبر الـ CDN لتصميم الواجهة بشكل سريع وعصري).
- **Vanilla JavaScript** (لإدارة حالة التطبيق، خوارزمية الأوزان، والتنقل بين الأسئلة دون إعادة تحميل الصفحة).

---

لتجربة الاختبار اضغط على اللينك في GitHub Pages او قم بعمل Clone على جهازك وشغل index.html على اي متصفح من اختيارك
