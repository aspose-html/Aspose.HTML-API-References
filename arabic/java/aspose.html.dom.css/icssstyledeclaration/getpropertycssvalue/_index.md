---
title: "ICSSStyleDeclaration.GetPropertyCSSValue"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة ICSSStyleDeclaration. تُستخدم لاسترجاع تمثيل الكائن لقيمة خاصية CSS إذا تم تعيينها صراحةً داخل كتلة الإعلان هذه. تُعيد هذه الطريقة null إذا كانت الخاصية خاصية مختصرة. لا يمكن الوصول إلى قيم الخصائص المختصرة وتعديلها إلا كسلاسل نصية باستخدام طريقتي getPropertyValue و setProperty."
type: docs

url: /ar/java/com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

يُستخدم لاسترجاع تمثيل الكائن لقيمة خاصية CSS إذا تم تعيينها صراحةً داخل هذه الكتلة الإعلانية. تُعيد هذه الطريقة null إذا كانت الخاصية اختصارًا. لا يمكن الوصول إلى قيم الخصائص المختصرة وتعديلها إلا كسلاسل نصية، باستخدام أساليب getPropertyValue و setProperty.

```java
public CSSValue GetPropertyCSSValue(String propertyName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| propertyName | String | propertyName هو String يمثل اسم الخاصية المراد استرجاعها. |

### قيمة الإرجاع

value هو CSSValue يحتوي على قيمة CSS لخاصية. إذا لم توجد، تُعيد null.

### انظر أيضًا

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
