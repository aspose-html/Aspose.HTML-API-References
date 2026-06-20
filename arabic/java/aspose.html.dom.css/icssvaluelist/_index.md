---
title: "واجهة ICSSValueList"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "واجهة com.aspose.html.dom.css.ICSSValueList. تُشتق واجهة CSSValueList من واجهة CSSValue وتوفر تجريد مجموعة مرتبة من قيم CSS."
type: docs

url: /ar/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

تُشتق واجهة CSSValueList من واجهة [`CSSValue`](../cssvalue/) وتوفر تجريد مجموعة مرتبة من قيم CSS.

بعض الخصائص تسمح بقائمة فارغة في بناء جملتها. في هذه الحالة، تتخذ هذه الخصائص المعرف none. لذا، تعني القائمة الفارغة أن الخاصية لها القيمة none.

يمكن الوصول إلى العناصر في CSSValueList عبر فهرس صحيح يبدأ من 0.

```java
public interface ICSSValueList
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) تُستخدم هذه الطريقة لاسترجاع CSSValue وفق فهرس ترتيبي. يمثل الترتيب في هذه المجموعة ترتيب القيم في خاصية نمط CSS. إذا كان الفهرس أكبر من أو يساوي عدد القيم في القائمة، تُعيد هذه القيمة null. |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) تمثل خاصية الطول للقراءة فقط في واجهة CSSValueList عدد قيم CSSValues في القائمة. نطاق القيم الصالحة للفهارس هو من 0 إلى length-1 شاملًا. |

## ملاحظات

كانت هذه الواجهة جزءًا من محاولة لإنشاء نموذج كائن CSS مكتوب بنوع. تم التخلي عن هذه المحاولة، ولا تُنفّذها معظم المتصفحات.

لتحقيق هدفك، يمكنك استخدام:

نموذج كائن CSS غير المكتوب بنوع [CSS Object Model](https://drafts.csswg.org/cssom/)، مدعوم على نطاق واسع، أو واجهة برمجة التطبيقات الحديثة لنموذج كائن CSS المكتوب بنوع [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects)، أقل دعمًا وتُعتبر تجريبية.

### انظر أيضًا

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
