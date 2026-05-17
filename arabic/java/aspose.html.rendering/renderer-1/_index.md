---
title: "فئة RendererTSource"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "الفئة com.aspose.html.rendering.Renderer1TSource. تمثل فئةً تجريدية لجميع المُعالجين"
type: docs

url: /ar/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

يمثل فئة مجردة لجميع العارضات.

```java
public abstract class Renderer<TSource> : Renderer
```

| معامل | الوصف |
| --- | --- |
| TDocument | نوع المستند. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | يطلق الموارد غير المُدارة و - اختياريًا - الموارد المُدارة. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | يحدد طريقةً لتصوير !:TDocument إلى [`IDevice`](../idevice/) المحدد. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | يحدد طريقةً لتصوير !:TDocument إلى [`IDevice`](../idevice/) المحدد. سيتم تنفيذ التصوير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد أو مؤقتات نشطة أو مهام رسوم متحركة أو انتهاء المهلة المحددة. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | يحدد طريقةً لتصوير !:TDocument إلى [`IDevice`](../idevice/) المحدد. سيتم تنفيذ التصوير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد أو مؤقتات نشطة أو مهام رسوم متحركة أو انتهاء المهلة المحددة. |

### انظر أيضًا

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
