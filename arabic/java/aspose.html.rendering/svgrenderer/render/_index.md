---
title: "SvgRenderer.Render"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة SvgRenderer. تُعرّف طريقة لتصوير عدة SVGDocuments في IDevice محدد. سيتم تنفيذ التصوير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد أو مؤقتات نشطة أو مهام رسوم متحركة أو انتهاء المهلة المحددة."
type: docs

url: /ar/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

تُعرّف طريقة لتصوير عدة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s في [`IDevice`](../../idevice/) محدد. سيتم تنفيذ التصوير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد أو مؤقتات نشطة أو مهام رسوم متحركة أو انتهاء المهلة المحددة.

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| مهلة | TimeSpan | TimeSpan يمثل عدد الملليثانية للانتظار، أو TimeSpan يمثل -1 ملليثانية للانتظار إلى أجل غير مسمى. |
| المستندات | SVGDocument[] | المستندات المراد عرضها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

تُعرّف طريقة لتصوير عدة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s في [`IDevice`](../../idevice/) محدد، باستخدام cancellation token لطلب إلغاء العملية.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| cancellationToken | CancellationToken | cancellation token لمراقبته أثناء انتظار إكمال المهمة. |
| المصادر | SVGDocument[] | مستندات SVG التي سيتم تصويرها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
