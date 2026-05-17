---
title: "تعداد PageLayoutOptions"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "com.aspose.html.rendering.PageLayoutOptions enum. يحدد العلامات التي مع خيارات PageSetup الأخرى تحدد أحجام وتخطيطات الصفحات. يمكن دمج هذه العلامات معًا وفقًا لأوصافها"
type: docs

url: /ar/java/com.aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

يحدد العلامات التي مع خيارات PageSetup الأخرى تحدد أحجام وتخطيطات الصفحات. يمكن دمج هذه العلامات معًا وفقًا لأوصافها.

```java
[Flags]
public enum PageLayoutOptions
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | القيمة الافتراضية التي تشير إلى أن PageLayoutOptions لن تؤثر على أحجام وتخطيطات الصفحات. |
| FitToContentWidth | `1` | تشير هذه العلامة إلى أن عرض الصفحات يتم تحديده من حجم المحتوى نفسه، وليس من عرض الصفحة المحدد. يتم حساب عرض المحتوى بشكل فردي لكل صفحة. |
| UseWidestPage | `2` | عند الجمع مع FitToContentWidth تشير إلى أن عرض كل صفحة سيكون نفسه وسيكون مساويًا لأوسع حجم محتوى بين جميع الصفحات. |
| FitToWidestContentWidth | `3` | تشير هذه العلامة إلى أن عرض الصفحة يتم تحديده من حجم المحتوى نفسه، وليس من عرض الصفحة المحدد. سيكون عرض كل صفحة هو نفسه وسيكون مساويًا لأوسع حجم محتوى بين جميع الصفحات. |
| FitToContentHeight | `10` | تشير هذه العلامة إلى أن ارتفاع الصفحة يتم تحديده من حجم المحتوى نفسه، وليس من ارتفاع الصفحة المحدد. سيتم وضع محتوى جميع المستندات على صفحة واحدة إذا تم تحديد هذه العلامة. |
| ScaleToPageWidth | `100` | تشير هذه العلامة إلى أن محتوى المستند سيتم تحجيمه ليتناسب مع الصفحة حيث يكون الفرق بين عرض الصفحة المتاح والمحتوى المتداخل هو الأكبر. تتعارض مع علامة FitToContentWidth وإذا تم تحديد كلتا العلامتين سيؤثر فقط ScaleToPageWidth. |
| ScaleToPageHeight | `1000` | تشير هذه العلامة إلى أن محتوى المستند سيتم تحجيمه ليتناسب مع ارتفاع الصفحة الأولى. تتعارض مع علامة FitToContentHeight وإذا تم تحديد كلتا العلامتين سيؤثر فقط ScaleToPageHeight. سيتم وضع محتوى المستند على صفحة واحدة فقط. |

### انظر أيضًا

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
