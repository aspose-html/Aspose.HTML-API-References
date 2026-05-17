---
title: "HtmlRenderer.Render"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة HtmlRenderer. يعرّف طريقة لتصيير عدة HTMLDocuments في IDevice محدد"
type: docs

url: /ar/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

يعرّف طريقة لتصيير عدة [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s في [`IDevice`](../../idevice/) محدد.

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| مهلة | TimeSpan | TimeSpan يمثل عدد الملليثانية للانتظار، أو TimeSpan يمثل -1 ملليثانية للانتظار إلى أجل غير مسمى. |
| المصادر | HTMLDocument[] | مستندات HTML التي سيتم تصييرها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

يعرّف طريقة لتصيير عدة [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s في [`IDevice`](../../idevice/) محدد، باستخدام رمز إلغاء لطلب إلغاء العملية.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| cancellationToken | CancellationToken | رمز إلغاء CancellationToken للمراقبة أثناء انتظار إكمال المهمة. |
| المصادر | HTMLDocument[] | مستندات HTML التي سيتم تصييرها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
