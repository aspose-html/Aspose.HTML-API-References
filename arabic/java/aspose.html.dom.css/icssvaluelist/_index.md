---
title: "واجهة ICSSValueList"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.css.ICSSValueList. تمثل واجهة CSSValueList واجهة CSSValue وتوفر تجريد مجموعة مرتبة من قيم CSS."
type: docs

url: /ar/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

تستمد واجهة CSSValueList من الواجهة [`CSSValue`](../cssvalue/) وتوفر تجريد مجموعة مرتبة من قيم CSS.

بعض الخصائص تسمح بقائمة فارغة في الصياغة. في هذه الحالة، تأخذ هذه الخصائص المعرف none. لذا، تعني القائمة الفارغة أن الخاصية لها القيمة none.

العناصر في CSSValueList يمكن الوصول إليها عبر فهرس عدد صحيح، يبدأ من 0.

```java
public interface ICSSValueList
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) تُستخدم هذه الطريقة لاسترجاع CSSValue حسب الفهرس الترتيبي. يمثل الترتيب في هذه المجموعة ترتيب القيم في خاصية نمط CSS. إذا كان الفهرس أكبر من أو يساوي عدد القيم في القائمة، تُعيد هذه القيمة null. |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) تمثل خاصية الطول للقراءة فقط في واجهة CSSValueList عدد قيم CSSValues في القائمة. النطاق القابل للقيم الصالحة للفهارس هو من 0 إلى length-1 شاملًا. |

## ملاحظات

كانت هذه الواجهة جزءًا من محاولة لإنشاء نموذج كائن CSS مكتوب بنوع. تم التخلي عن هذه المحاولة، ولا تُطبق معظم المتصفحات ذلك.

لتحقيق هدفك، يمكنك استخدام:

النموذج غير المكتوب [CSS Object Model](https://drafts.csswg.org/cssom/)، مدعوم على نطاق واسع، أو نموذج كائن CSS المكتوب بنوع الحديث [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects)، أقل دعمًا ويُعتبر تجريبيًا.

### انظر أيضًا

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
