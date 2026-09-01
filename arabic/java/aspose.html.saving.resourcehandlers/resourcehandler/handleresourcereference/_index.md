---
title: "ResourceHandler.HandleResourceReference"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة ResourceHandler. هذه الطريقة مسؤولة عن معالجة مرجع المورد. في هذه الطريقة يمكنك تحديد شكل المرجع إلى المورد الذي يتم معالجته."
type: docs

url: /ar/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

هذه الطريقة مسؤولة عن معالجة مرجع المورد. في هذه الطريقة، يمكنك تحديد الشكل الذي سيظهر به المرجع للمورد الذي يتم معالجته.

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resource | Resource | الـ[`Resource`](../../../com.aspose.html.saving/resource/) الذي سيتم معالجته. |
| السياق | ResourceHandlingContext | سياق معالجة الموارد. |

### قيمة الإرجاع

سلسلة نصية ستُكتب إلى المورد الأب وتمثل مرجعًا إلى المورد الذي يتم معالجته حاليًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يُرفع إذا كان الـ[`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) `null` وكان الـ[`Status`](../../../com.aspose.html.saving/resource/status/) محفوظًا. يجب تحديد الـ[`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) للمورد المحفوظ لأنه وإلا سيكون من المستحيل تحديد المرجع الصحيح في الموارد التي تشير إلى هذا المورد. |

### انظر أيضًا

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)
