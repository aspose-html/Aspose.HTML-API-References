---
title: "MhtmlRenderer.Render"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة MhtmlRenderer. تصيّر عدة مستندات MHTML في IDevice المحدد. سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد، مؤقتات نشطة، مهام رسوم متحركة أو انتهاء المهلة المحددة"
type: docs

url: /ar/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

يصيغ عدة مستندات MHTML في [`IDevice`](../../idevice/). سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد، مؤقتات نشطة، مهام رسوم متحركة أو انتهاء المهلة المحددة.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | الجهاز. |
| مهلة | TimeSpan | TimeSpan يمثل عدد الملليثانية للانتظار، أو TimeSpan يمثل -1 ملليثانية للانتظار إلى أجل غير مسمى. |
| المستندات | Stream[] | المستندات المراد عرضها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

يحدد طريقة لعرض مستندات MHTML متعددة في [`IDevice`](../../idevice/) محدد، باستخدام رمز إلغاء الطلب لإلغاء العملية.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| cancellationToken | CancellationToken | رمز إلغاء CancellationToken للمراقبة أثناء انتظار إكمال المهمة. |
| المصادر | Stream[] | مستندات MHTML المراد عرضها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

يعرض مستند MHTML في [`IDevice`](../../idevice/) المحدد.

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | الجهاز. |
| مستند | دفق | المستند. |
| الإعدادات | الإعدادات | الإعدادات. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

يعرض مستند MHTML في [`IDevice`](../../idevice/) المحدد. سيتم تنفيذ العرض بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد، أو مؤقتات نشطة، أو مهام رسوم متحركة، أو انتهاء المهلة المحددة.

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | الجهاز. |
| مستند | دفق | المستند. |
| الإعدادات | الإعدادات | الإعدادات. |
| مهلة | TimeSpan | TimeSpan يمثل عدد الملليثانية للانتظار، أو TimeSpan يمثل -1 ملليثانية للانتظار إلى أجل غير مسمى. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

يعرض مستندات MHTML متعددة في [`IDevice`](../../idevice/) المحدد.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | الجهاز. |
| المستندات | IList`1 | قائمة IList للمستندات المراد عرضها. |
| الإعدادات | الإعدادات | الإعدادات. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

يصيغ عدة مستندات MHTML في [`IDevice`](../../idevice/). سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد، مؤقتات نشطة، مهام رسوم متحركة أو انتهاء المهلة المحددة.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | الجهاز. |
| المستندات | IList`1 | قائمة IList للمستندات المراد عرضها. |
| الإعدادات | الإعدادات | الإعدادات. |
| مهلة | TimeSpan | TimeSpan يمثل عدد الملليثانية للانتظار، أو TimeSpan يمثل -1 ملليثانية للانتظار إلى أجل غير مسمى. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
