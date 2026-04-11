# traffic-data-analysis
Traffic data analysis project using Python to explore congestion patterns, peak hours, busiest days, and vehicle distribution.

# تحليل بيانات المرور

## نظرة عامة على المشروع

يهدف هذا المشروع إلى تحليل بيانات المرور باستخدام Python لاكتشاف أنماط الحركة المرورية، وتحديد ساعات الذروة، وأكثر الأيام ازدحامًا، وأكثر أنواع المركبات استخدامًا، ومستويات الازدحام المختلفة.

## أهداف المشروع

* تحديد أكثر ساعات اليوم ازدحامًا.
* معرفة أكثر أيام الأسبوع ازدحامًا.
* تحليل مستويات المرور المختلفة.
* دراسة توزيع أنواع المركبات.
* تحديد أوقات الازدحام الشديد.
* مقارنة المرور بين أيام العمل وعطلة نهاية الأسبوع.

## الأدوات المستخدمة

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## 1. متوسط حركة المرور حسب الساعة

يوضح الرسم تغير الحركة المرورية خلال اليوم، حيث تظهر ذروة صباحية بين 6 صباحًا و8 صباحًا، وذروة مسائية أعلى بين 4 مساءً و6 مساءً.

![Average Traffic by Hour](https://github.com/HananAljaber/traffic-data-analysis/blob/main/output.png?raw=true)

---

## 2. متوسط حركة المرور حسب اليوم

يبين الرسم أن يوم السبت سجل أعلى متوسط للحركة المرورية، بينما كان يوم الأحد الأقل ازدحامًا.

![Average Traffic by Day](https://github.com/HananAljaber/traffic-data-analysis/blob/main/output9.png?raw=true)

---

## 3. إجمالي المركبات حسب النوع

تمثل السيارات العدد الأكبر بفارق واضح مقارنة ببقية المركبات، مما يدل على الاعتماد الكبير على المركبات الخاصة.

![Total Vehicles by Type](https://github.com/HananAljaber/traffic-data-analysis/blob/main/output3.png?raw=true)

---

## 4. متوسط عدد المركبات حسب اليوم

يوضح الرسم استقرار أعداد المركبات نسبيًا خلال أيام الأسبوع، مع استمرار السيارات كأكثر المركبات استخدامًا.

![Average Vehicle Count by Day](https://github.com/HananAljaber/traffic-data-analysis/blob/main/output4.png?raw=true)

---

## 5. عدد حالات المرور

تعد حالة المرور الطبيعية normal الأكثر تكرارًا، بينما تظهر حالات الازدحام الشديد heavy بنسبة أقل.

![Traffic Situation Count](https://github.com/HananAljaber/traffic-data-analysis/blob/main/output5.png?raw=true)

---

## 6. الازدحام الشديد حسب الساعة

يتركز الازدحام الشديد خلال فترات الذروة الصباحية والمسائية، خصوصًا بين 4 مساءً و6 مساءً.

![Heavy Traffic by Hour](https://github.com/HananAljaber/traffic-data-analysis/blob/main/output6.png?raw=true)

---

## 7. متوسط المركبات أثناء الازدحام الشديد

تشير النتائج إلى أن السيارات هي المساهم الأكبر في حالات الازدحام الشديد مقارنة ببقية المركبات.

![Average Vehicles During Heavy Traffic](https://github.com/HananAljaber/traffic-data-analysis/blob/main/output7.png?raw=true)

---

## 8. متوسط المركبات حسب حالة المرور

كلما ارتفعت حالة المرور من منخفض إلى شديد، ازداد متوسط عدد المركبات بشكل واضح.

![Average Vehicles by Traffic Situation](https://github.com/HananAljaber/traffic-data-analysis/blob/main/output8.png?raw=true)

---

## 9. أيام العمل مقابل عطلة نهاية الأسبوع

لا يظهر فرق كبير في متوسط الحركة المرورية بين أيام العمل وعطلة نهاية الأسبوع.

![Traffic Work Days vs Weekend](https://github.com/HananAljaber/traffic-data-analysis/blob/main/outpu2t.png?raw=true)

---

## أبرز النتائج

* أعلى ازدحام مروري بين 4 مساءً و6 مساءً.
* توجد ذروة صباحية بين 6 صباحًا و8 صباحًا.
* يوم السبت الأعلى حركة مرورية.
* يوم الأحد الأقل ازدحامًا.
* السيارات تمثل النسبة الأكبر من المركبات.
* الحالة الطبيعية normal هي الأكثر تكرارًا.
* لا يوجد فرق كبير بين أيام العمل وعطلة نهاية الأسبوع.

---

## الملفات

* Traffic.csv
* Untitled-1.ipynb
* README.md

---

## الكاتب

Hanan Aljaber
