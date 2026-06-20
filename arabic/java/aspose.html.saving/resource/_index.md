---
title: "فئة Resource"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.saving.Resource. تصف هذه الفئة موردًا وتوفر طرقًا لمعالجته"
type: docs

url: /ar/java/com.aspose.html.saving/resource/
---
## Resource class

هذه الفئة تصف موردًا وتوفر طرقًا لمعالجته.

```java
public class Resource
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) تُرجع [`MimeType`](../../com.aspose.html/mimetype/) لهذا المورد. يمكن أن تكون `null` إذا لم يُعثر على المورد. |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) تُرجع سلسلة تحتوي على المرجع الأصلي لهذا المورد. |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) تُرجع عنوان URL يوضح مكان وجود هذا المورد. |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) يرجع الحالة الحالية للمورد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | يضمّن هذا المورد داخل العنصر الأصلي عن طريق ترميزه كـ Base64. سيتم كتابة نتيجة الترميز إلى [`OutputUrl`](./outputurl/). |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | يحفظ المورد إلى الدفق المقدم. |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | يحدد عنوان URL الجديد الذي يوضح مكان وجود المورد بعد المعالجة. |

### انظر أيضًا

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
