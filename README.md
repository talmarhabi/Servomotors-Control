# Servomotors-Control
في هذا المشروع محاولة محاكاة حركة الروبوت باستخدام 6 محركات من نوع servomotors موضحه بالخطوات التالية:

1- لكل قدم في الروبوت 3 مفاصل يتم محاكانها باستخدام محركات الservo باجمالي 6 محركات.

2- يتم توفير مصدر الطاقة للمحركات باستخدام بطارية بمصدر جهد 9V.

3- مصدر الجهد للبطارية غير متوافق مع المحركات التي تطلب 5V فقط: فالبتالي تم استخدام منظم جهد (Voltage Regulator) لجعل الجهد متوافق مع المحركات.

4- تم توصيل منظم الجهد مع المكثفات كما هو موصى في ورقة بيانات (datashhet) المنظم.

5- تم استخدام اردوينو وتوصيله بالمحركات للتحكم بها وتوصيله بالأرض الخاص بالبطارية.

6- تم تعريف كل محرك خلال برمجته بالأردوينو موقع توصيله.

7- تم تحديد زاوية الحركة لثلاثة محركات والعودة إلى موقعها لمحاكاة القدم الأولى.

8- تم تكرار نفس الخطوات للمحركات الثلاثة المتبقية لمحاكاة القدم الأخرى.

9- تم اضافة امر يعيد تكرار الخطوات للعودة مجدداً للقدم اليمنى.

![image](https://github.com/talmarhabi/Servomotors-Control/assets/173712776/bf6b3312-cfa6-4f13-bc2c-fc17f3ede5c2)
