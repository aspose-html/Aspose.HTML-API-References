---
title: "فئة EpubRenderer"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "فئة com.aspose.html.rendering.EpubRenderer. تمثّل مُصَّدّر مستند EPub"
type: docs

url: /ar/java/com.aspose.html.rendering/epubrenderer/
---
## EpubRenderer class

يمثل عارض مستند EPub.

```java
public class EpubRenderer : Renderer<Stream>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EpubRenderer](epubrenderer/)() | المنشئ الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | يطلق الموارد غير المُدارة - واختياريًا - المُدارة. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | يعرّف طريقة لتصيير عدة مستندات EPub في جهاز محدد [`IDevice`](../idevice/)، باستخدام رمز إلغاء لتقديم طلب إلغاء العملية. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | يصيّر عدة مستندات EPub في [`IDevice`](../idevice/) المحدد. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_4)(IDevice, Stream, Configuration) | يصيّر مستند EPub في [`IDevice`](../idevice/) المحدد. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | يعرّف طريقة لتصيير عدة تدفقات EPub في جهاز محدد [`IDevice`](../idevice/). سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد، أو مؤقتات نشطة، أو مهام رسوم متحركة، أو انتهاء المهلة المحددة. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | يصيّر عدة مستندات EPub في [`IDevice`](../idevice/) المحدد. سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد، أو مؤقتات نشطة، أو مهام رسوم متحركة، أو انتهاء المهلة المحددة. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | يصيّر مستند EPub في [`IDevice`](../idevice/) المحدد. سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد، أو مؤقتات نشطة، أو مهام رسوم متحركة، أو انتهاء المهلة المحددة. |

### انظر أيضًا

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
