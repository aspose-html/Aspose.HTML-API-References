---
title: "ICSSStyleDeclaration.RemoveProperty"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة ICSSStyleDeclaration. واجهة طريقة CSSStyleDeclaration.removeProperty تُزيل خاصية من كائن إعلان نمط CSS."
type: docs

url: /ar/java/com.aspose.html.dom.css/icssstyledeclaration/removeproperty/
---
## ICSSStyleDeclaration.RemoveProperty method

واجهة طريقة CSSStyleDeclaration.removeProperty() تُزيل خاصية من كائن إعلان نمط CSS.

```java
public String RemoveProperty(String propertyName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| propertyName | String | propertyName هو سلسلة تمثل اسم الخاصية التي سيتم إزالتها. لاحظ أن أسماء الخصائص المتعددة الكلمات تُكتب بشرطة ولا تُكتب بصيغة camelCase. |

### قيمة الإرجاع

oldValue هو DOMString يساوي قيمة خاصية CSS قبل إزالتها.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| DOMException | NO_MODIFICATION_ALLOWED_ERR: إذا كانت الخاصية أو كتلة الإعلان للقراءة فقط. |

### انظر أيضًا

* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
