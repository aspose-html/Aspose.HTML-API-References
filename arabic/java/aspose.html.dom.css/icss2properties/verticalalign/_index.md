---
title: "ICSS2Properties.VerticalAlign"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "خاصية ICSS2Properties. تؤثر هذه الخاصية على التموضع العمودي داخل صندوق السطر للمربعات التي يولدها عنصر على مستوى السطر. القيم التالية لا معنى لها إلا بالنسبة لعنصر أب على مستوى السطر أو لعنصر أب على مستوى الكتلة إذا كان ذلك العنصر يولد مربعات سطرية مجهولة؛ ولا يكون لها أي تأثير إذا لم يوجد مثل هذا العنصر الأب."
type: docs

url: /ar/java/com.aspose.html.dom.css/icss2properties/verticalalign/
---
## ICSS2Properties.VerticalAlign property

تؤثر هذه الخاصية على التموضع العمودي داخل صندوق السطر للمربعات التي يولدها عنصر على مستوى السطر. القيم التالية لا معنى لها إلا بالنسبة لعنصر أب على مستوى السطر، أو لعنصر أب على مستوى الكتلة، إذا كان ذلك العنصر يولد [مربعات سطرية مجهولة](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous)؛ ولا يكون لها أي تأثير إذا لم يوجد مثل هذا العنصر الأب.

ملاحظة. قيم هذه الخاصية لها معانٍ مختلفة قليلاً في سياق الجداول. يرجى الاطلاع على القسم المتعلق بـ [table height algorithms](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#height-layout) للحصول على التفاصيل. baseline - محاذاة خط القاعدة للمربع مع خط قاعدة العنصر الأب. إذا لم يكن للمربع خط قاعدة، يتم محاذاة أسفل المربع مع خط قاعدة الأب. middle - محاذاة منتصف المربع العمودي مع خط قاعدة العنصر الأب زائد نصف ارتفاع x للعنصر الأب. sub - خفض خط قاعدة المربع إلى الموضع المناسب للخطوط السفلية (subscripts) للعنصر الأب. (هذه القيمة لا تؤثر على حجم الخط لنص العنصر.) super - رفع خط قاعدة المربع إلى الموضع المناسب للخطوط العلوية (superscripts) للعنصر الأب. (هذه القيمة لا تؤثر على حجم الخط لنص العنصر.) text-top - محاذاة أعلى المربع مع أعلى خط الخط للعنصر الأب. text-bottom - محاذاة أسفل المربع مع أسفل خط الخط للعنصر الأب. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - رفع (قيمة موجبة) أو خفض (قيمة سالبة) المربع بهذه المسافة (نسبة مئوية من قيمة ['line-height'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-line-height)). القيمة '0%' تعني نفس 'baseline'. '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - رفع (قيمة موجبة) أو خفض (قيمة سالبة) المربع بهذه المسافة. القيمة '0cm' تعني نفس 'baseline'. top - محاذاة أعلى المربع مع أعلى صندوق السطر. bottom - محاذاة أسفل المربع مع أسفل صندوق السطر.

```java
public String VerticalAlign { get; set; }
```

### قيمة الإرجاع

خاصية vertical-align

### انظر أيضًا

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
