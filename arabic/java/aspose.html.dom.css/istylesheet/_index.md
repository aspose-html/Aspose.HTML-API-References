---
title: "واجهة IStyleSheet"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "واجهة com.aspose.html.dom.css.IStyleSheet. تُعد واجهة StyleSheet الواجهة الأساسية المجردة لأي نوع من أوراق الأنماط. تمثل ورقة نمط واحدة مرتبطة بمستند مُنظم. في HTML تمثل واجهة StyleSheet إما ورقة نمط خارجية مُضمنة عبر عنصر HTML LINK أو عنصر STYLE مضمّن. في XML تمثل هذه الواجهة ورقة نمط خارجية مُضمنة عبر تعليمات معالجة ورقة النمط. ستُنفّذ أوراق نمط CSS لاحقًا واجهة CSSStyleSheet المتخصصة أكثر."
type: docs

url: /ar/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

واجهة StyleSheet هي الواجهة الأساسية المجردة لأي نوع من أوراق الأنماط. تمثل ورقة نمط واحدة مرتبطة بمستند مُنظم. في HTML، تمثل واجهة StyleSheet إما ورقة نمط خارجية مُضمنة عبر عنصر HTML LINK، أو عنصر STYLE مضمّن. في XML، تمثل هذه الواجهة ورقة نمط خارجية مُضمنة عبر تعليمات معالجة ورقة النمط. ستُنفّذ أوراق نمط CSS لاحقًا واجهة [`CSSStyleSheet`](../icssstylesheet/) المتخصصة أكثر.

انظر أيضًا إلى [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface).

```java
public interface IStyleSheet
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) تُعيد خاصية href في واجهة `StyleSheet` موقع ورقة النمط. |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) تحدد خاصية media في واجهة `StyleSheet` وسائط الوجهة المقصودة لمعلومات النمط. إنها كائن [`MediaList`](../imedialist/) شبيه بالمصفوفة للقراءة فقط ويمكن إزالته باستخدام deleteMedium() وإضافته باستخدام appendMedium(). |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) العقدة التي تربط ورقة النمط هذه بالمستند. في HTML، قد تكون العنصر LINK أو STYLE المقابل. في XML، قد تكون تعليمات معالجة الربط. بالنسبة لأوراق الأنماط التي تُضمّن بواسطة أوراق أنماط أخرى، تكون قيمة هذه الخاصية null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) بالنسبة للغات أوراق الأنماط التي تدعم مفهوم تضمين أوراق الأنماط، تمثل هذه الخاصية ورقة النمط الشاملة إذا وجدت. إذا كانت ورقة النمط ورقة مستوى أعلى، أو إذا كانت لغة ورقة النمط لا تدعم التضمين، تكون قيمة هذه الخاصية null. |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) تُعيد خاصية title في واجهة `StyleSheet` العنوان الاستشاري لورقة النمط الحالية. |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) يحدد هذا لغة ورقة النمط لهذه ورقة النمط. تُحدد لغة ورقة النمط كنوع محتوى (مثال: \"text/css\"). |

## ملاحظات

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

المرجع

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### انظر أيضًا

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
