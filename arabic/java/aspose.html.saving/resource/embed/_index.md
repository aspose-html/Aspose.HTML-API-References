---
title: "Resource.Embed"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Resource. تُضمّن هذا المورد داخل العنصر الأب عن طريق ترميزه كـBase64. سيتم كتابة نتيجة الترميز إلى OutputUrl"
type: docs

url: /ar/java/com.aspose.html.saving/resource/embed/
---
## Resource.Embed method

تُضمّن هذا المورد داخل العنصر الأب عن طريق ترميزه كـBase64. سيتم كتابة نتيجة الترميز إلى [`OutputUrl`](../outputurl/).

```java
public Resource Embed(ResourceHandlingContext context)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| السياق | ResourceHandlingContext | سياق معالجة الموارد. |

### قيمة الإرجاع

هذا المورد بحيث يمكنك ربط الاستدعاءات.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يتم رفع الاستثناء إذا لم يكن هناك [`ParentResource`](../../resourcehandlingcontext/parentresource/) لأنه لا يوجد مكان لتضمين النتيجة. |

### انظر أيضًا

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
