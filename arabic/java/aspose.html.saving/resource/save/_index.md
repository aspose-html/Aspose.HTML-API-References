---
title: "Resource.Save"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Resource. تحفظ المورد إلى الدفق المقدم."
type: docs

url: /ar/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

يحفظ المورد إلى الدفق المقدم.

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | الدفق الذي سيتم حفظ المورد فيه. |
| السياق | ResourceHandlingContext | سياق معالجة الموارد. |

### قيمة الإرجاع

هذا المورد بحيث يمكنك ربط الاستدعاءات.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يتم رفع الاستثناء إذا كان [`OutputUrl`](../outputurl/) يساوي `null`. يجب تحديد [`OutputUrl`](../outputurl/) قبل حفظ المورد لأنه وإلا سيكون من المستحيل تحديد المرجع الصحيح في الموارد التي تشير إلى هذا المورد. |

### انظر أيضًا

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
