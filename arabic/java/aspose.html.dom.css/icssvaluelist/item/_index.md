---
title: "ICSSValueList.Item"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "خاصية ICSSValueList. تُستخدم هذه الطريقة لاسترجاع CSSValue حسب الفهرس الترتيبي. يمثل الترتيب في هذه المجموعة ترتيب القيم في خاصية نمط CSS. إذا كان الفهرس أكبر من أو يساوي عدد القيم في القائمة فإنها تُعيد null."
type: docs

url: /ar/java/com.aspose.html.dom.css/icssvaluelist/item/
---
## ICSSValueList indexer

يتم استخدام هذه الطريقة لاسترجاع CSSValue حسب الفهرس الترتيبي. يمثل الترتيب في هذه المجموعة ترتيب القيم في خاصية نمط CSS. إذا كان الفهرس أكبر من أو يساوي عدد القيم في القائمة، فإنها تُعيد null.

انظر أيضًا إلى [CSSOM](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList)[#CSSValueList](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList).

```java
public CSSValue this[int index] { get; }
```

### قيمة الإرجاع

الـ[`CSSValue`](../../cssvalue/) في موضع الفهرس داخل الـ[`CSSValueList`](../../cssvaluelist/)، أو null إذا لم يكن فهرسًا صالحًا.

### Property Value

الفهرس داخل المجموعة.

## ملاحظات

تم تعريف هذه الميزة أصلاً في مواصفة [DOM Style Level 2](https://www.w3.org/TR/DOM-Level-2-Style)، ولكن تم إلغاؤها من أي جهود توحيد منذ ذلك الحين.

تم استبدالها بواجهة برمجة تطبيقات حديثة ولكن غير متوافقة، وهي [CSS Typed Object Model API](https://developer.mozilla.org/en-US/docs/Web/API/CSS_Typed_OM_API)، التي أصبحت الآن على المسار القياسي.

### انظر أيضًا

* class [CSSValue](../../cssvalue/)
* interface [ICSSValueList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
