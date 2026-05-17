---
title: "واجهة ICSSImportRule"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "com.aspose.html.dom.css.ICSSImportRule interface. تمثل واجهة CSSImportRule قاعدة استيراد داخل ورقة أنماط CSS. تُستخدم قاعدة الاستيراد لاستيراد قواعد الأنماط من أوراق أنماط أخرى."
type: docs

url: /ar/java/com.aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

تمثل واجهة CSSImportRule قاعدة @import داخل ورقة أنماط CSS. تُستخدم قاعدة @import لاستيراد قواعد الأنماط من أوراق أنماط أخرى.

```java
public interface ICSSImportRule : ICSSRule
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getHref](../../com.aspose.html.dom.css/icssimportrule/href/) تُعيد الخاصية href للقراءة فقط في واجهة CSSImportRule عنوان URL المحدد بواسطة قاعدة @import. |
| [getMedia](../../com.aspose.html.dom.css/icssimportrule/media/) تُعيد الخاصية media للقراءة فقط في واجهة CSSImportRule كائن MediaList يحتوي على قيمة سمة media للورقة المرتبطة. |
| [getStyleSheet](../../com.aspose.html.dom.css/icssimportrule/stylesheet/) تُشير ورقة الأنماط التي يشير إليها هذه القاعدة، إذا تم تحميلها. تكون قيمة هذه الخاصية null إذا لم تُحمَّل ورقة الأنماط بعد أو إذا لن يتم تحميلها (مثال: إذا كانت ورقة الأنماط لنوع وسائط غير مدعوم من قبل وكيل المستخدم). |

### انظر أيضًا

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
