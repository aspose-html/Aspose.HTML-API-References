---
title: "واجهة ICSSStyleDeclaration"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.css.ICSSStyleDeclaration. تمثل واجهة CSSStyleDeclaration كائنًا هو كتلة إعلان CSS وتكشف عن معلومات النمط ومجموعة متنوعة من الطرق والخصائص المتعلقة بالنمط."
type: docs

url: /ar/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

واجهة CSSStyleDeclaration تمثل كائنًا هو كتلة إعلان CSS، وتعرض معلومات النمط ومجموعة من الأساليب والخصائص المتعلقة بالنمط.

يمكن الكشف عن كائن CSSStyleDeclaration باستخدام ثلاث واجهات برمجة تطبيقات مختلفة:

من خلال HTMLElement.style، الذي يتعامل مع الأنماط المضمنة لعنصر واحد. عبر واجهة برمجة التطبيقات [`CSSStyleSheet`](../icssstylesheet/). على سبيل المثال، document.styleSheets[0].cssRules[0].style تُعيد كائن `CSSStyleDeclaration` للقاعدة CSS الأولى في ورقة الأنماط الأولى للمستند. عبر Window.getComputedStyle()، الذي يكشف عن كائن `CSSStyleDeclaration` كواجهة للقراءة فقط.

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) يُستخدم لاسترجاع الخصائص التي تم تعيينها صراحةً في كتلة الإعلان هذه. لا يجب أن يكون ترتيب الخصائص المسترجعة باستخدام هذه الطريقة هو نفس ترتيب تعيينها. يمكن استخدام هذه الطريقة للتكرار على جميع الخصائص في كتلة الإعلان هذه. |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) الخاصية للقراءة فقط تُعيد عددًا صحيحًا من الخصائص التي تم تعيينها صراحةً في كتلة إعلان CSS هذه. نطاق الفهارس الصالحة هو من 0 إلى length-1 شاملًا. |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) الخاصية للقراءة فقط CSSStyleDeclaration.parentRule تُعيد كائن CSSRule الذي هو الأصل لهذا كتلة النمط، مثلًا [`CSSStyleRule`](../icssstylerule/) الذي يمثل النمط لمحدد CSS. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | يُستخدم لاسترجاع تمثيل الكائن لقيمة خاصية CSS إذا تم تعيينها صراحةً داخل كتلة الإعلان هذه. تُعيد هذه الطريقة null إذا كانت الخاصية اختصارًا. لا يمكن الوصول إلى قيم خصائص الاختصار وتعديلها إلا كسلاسل نصية، باستخدام طريقتي getPropertyValue و setProperty. |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | يُستخدم لاسترجاع أولوية خاصية CSS (مثل محدد \"important\") إذا تم تعيين الخاصية صراحةً في كتلة الإعلان هذه. |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | واجهة طريقة CSSStyleDeclaration.getPropertyValue() تُعيد سلسلة نصية تحتوي على قيمة خاصية CSS محددة. |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | واجهة طريقة CSSStyleDeclaration.removeProperty() تُزيل خاصية من كائن إعلان نمط CSS. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | واجهة طريقة CSSStyleDeclaration.setProperty() تُستخدم لتعيين قيمة خاصية بأولوية افتراضية داخل كتلة الإعلان هذه. الأولوية الافتراضية ليست \"important\" أي String.Empty. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | واجهة طريقة CSSStyleDeclaration.setProperty() تُستخدم لتعيين قيمة خاصية بأولوية افتراضية داخل كتلة الإعلان هذه. الأولوية الافتراضية ليست \"important\" أي String.Empty. |

## ملاحظات

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

المرجع

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### انظر أيضًا

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
