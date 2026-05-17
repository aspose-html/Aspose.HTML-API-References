---
title: "واجهة ITrueTypeFont"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.drawing.ITrueTypeFont. تُعلن عن طرق للعمل مع خط TrueType."
type: docs

url: /ar/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

يعلن عن طرق للعمل مع خط TrueType.

```java
public interface ITrueTypeFont
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) يعيد حجم بيانات الخط بالبايت. |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) احصل على اسم عائلة الخط. |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) يجب أن يكون هذا مزيجًا من "FamilyName" و "SubFamilyName". استثناء: إذا كان الخط "Regular" كما هو موضح في "SubFamilyName"، فاستعمل فقط اسم العائلة الموجود في "FamilyName". استثناء آخر لتعريف اسم الخط الكامل هو لسلاسل منصة مايكروسوفت لخطوط CFF OpenType: في هذه الحالة، يجب أن تكون سلسلة اسم الخط الكامل مطابقة تمامًا لاسم الخط PostScript في فهرس CFF Name INDEX. |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) اسم الفئة الفرعية للخط يميز الخط ضمن مجموعة لها نفس اسم عائلة الخط. يُفترض أن يعالج النمط (مائل، مائل مائل) والوزن (خفيف، عريض، أسود، إلخ). الخط الذي لا يملك اختلافات ملحوظة في الوزن أو النمط (مثل وزن متوسط، غير مائل وتعيين البت 6 في fsSelection) يجب أن يحتوي على السلسلة "Regular" في هذا الموضع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | يعيد الصعود بالنقاط. |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | افتح الدفق ببيانات الخط. المتصل مسؤول عن تحرير الدفق. |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | يعيد النزول بالنقاط. |

### انظر أيضًا

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
