---
title: "فئة CSSValue"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.dom.css.CSSValue. تمثل قيمة بسيطة أو مركبة. يحدث كائن CSSValue فقط في سياق خاصية CSS."
type: docs

url: /ar/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

يمثل قيمة بسيطة أو مركبة. كائن CSSValue يظهر فقط في سياق خاصية CSS.

```java
public abstract class CSSValue : DOMObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | خاصية cssText في واجهة `CSSValue` تمثل القيمة الحالية المحسوبة لخاصية CSS. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) رمز يحدد نوع القيمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | يحدد ما إذا كان الكائن المحدد يساوي هذه المثيلة. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | يرجع رمز تجزئة لهذا الكائن. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | تُستخدم هذه الطريقة لاسترجاع نوع كائن ECMAScript. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | يرجع سلسلة تمثل هذا الكائن. |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | القيمة هي قيمة مخصصة. |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | القيمة موروثة وتحتوي خاصية cssText على \"inherit\". |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | القيمة هي قيمة بدائية ويمكن الحصول على نسخة من واجهة CSSPrimitiveValue باستخدام طرق التحويل الخاصة بالربط على هذه النسخة من واجهة CSSValue. |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | القيمة هي قائمة CSSValue ويمكن الحصول على نسخة من واجهة CSSValueList باستخدام طرق التحويل الخاصة بالربط على هذه النسخة من واجهة CSSValue. |

### انظر أيضًا

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
