---
title: "SvgRenderer.Render"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة SvgRenderer. تعرف طريقة لعرض عدة SVGDocuments في IDevice محدد. سيتم تنفيذ العرض بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد أو مؤقتات نشطة أو مهام رسوم متحركة أو انتهاء المهلة المحددة."
type: docs

url: /ar/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

تعرف طريقة لعرض عدة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s في [`IDevice`](../../idevice/) محدد. سيتم تنفيذ العرض بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد أو مؤقتات نشطة أو مهام رسوم متحركة أو انتهاء المهلة المحددة.

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| مهلة | TimeSpan | فترة زمنية (TimeSpan) تمثل عدد المللي ثانية للانتظار، أو فترة زمنية تمثل -1 مللي ثانية للانتظار إلى ما لا نهاية. |
| المستندات | SVGDocument[] | المستندات المراد عرضها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

تعرف طريقة لعرض عدة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s في [`IDevice`](../../idevice/) محدد، باستخدام رمز إلغاء (cancellation token) لطلب إلغاء العملية.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| cancellationToken | CancellationToken | رمز إلغاء لمراقبته أثناء انتظار إكمال المهمة. |
| المصادر | SVGDocument[] | مستندات SVG المراد عرضها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
