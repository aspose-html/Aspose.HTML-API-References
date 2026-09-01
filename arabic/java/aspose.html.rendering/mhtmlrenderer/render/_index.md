---
title: "MhtmlRenderer.Render"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة MhtmlRenderer. تصيّر عدة مستندات MHTML إلى IDevice المحدد. سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد، مؤقتات نشطة، مهام رسوم متحركة أو انتهاء المهلة المحددة."
type: docs

url: /ar/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

يصيّر عدة مستندات MHTML إلى [`IDevice`](../../idevice/) المحدد. سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد، مؤقتات نشطة، مهام رسوم متحركة أو انتهاء المهلة المحددة.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | الجهاز. |
| مهلة | TimeSpan | فترة زمنية (TimeSpan) تمثل عدد المللي ثانية للانتظار، أو فترة زمنية تمثل -1 مللي ثانية للانتظار إلى ما لا نهاية. |
| المستندات | Stream[] | المستندات المراد عرضها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

يحدد طريقة لعرض عدة مستندات MHTML إلى جهاز محدد [`IDevice`](../../idevice/)، باستخدام رمز إلغاء لطلب إلغاء العملية.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| cancellationToken | CancellationToken | CancellationToken للمراقبة أثناء انتظار إكمال المهمة. |
| المصادر | Stream[] | مستندات MHTML المراد عرضها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

يعرض مستند MHTML في الجهاز المحدد [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | الجهاز. |
| مستند | دفق | المستند. |
| التكوين | التكوين | التكوين. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

يعرض مستند MHTML في الجهاز المحدد [`IDevice`](../../idevice/). سيتم تنفيذ العرض بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد، أو مؤقتات نشطة، أو مهام رسوم متحركة، أو انتهاء المهلة المحددة.

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | الجهاز. |
| مستند | دفق | المستند. |
| التكوين | التكوين | التكوين. |
| مهلة | TimeSpan | فترة زمنية (TimeSpan) تمثل عدد المللي ثانية للانتظار، أو فترة زمنية تمثل -1 مللي ثانية للانتظار إلى ما لا نهاية. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

يعرض عدة مستندات MHTML في الجهاز المحدد [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | الجهاز. |
| المستندات | IList`1 | قائمة IList للمستندات المراد عرضها. |
| التكوين | التكوين | التكوين. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

يصيّر عدة مستندات MHTML إلى [`IDevice`](../../idevice/) المحدد. سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد، مؤقتات نشطة، مهام رسوم متحركة أو انتهاء المهلة المحددة.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | الجهاز. |
| المستندات | IList`1 | قائمة IList للمستندات المراد عرضها. |
| التكوين | التكوين | التكوين. |
| مهلة | TimeSpan | فترة زمنية (TimeSpan) تمثل عدد المللي ثانية للانتظار، أو فترة زمنية تمثل -1 مللي ثانية للانتظار إلى ما لا نهاية. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
