---
title: "EpubRenderer.Render"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة EpubRenderer. تحدد طريقة لتصيير عدة تدفقات EPub إلى IDevice محدد. سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد أو مؤقتات نشطة أو مهام رسوم متحركة أو انتهاء المهلة المحددة"
type: docs

url: /ar/java/com.aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

تحدد طريقة لتصيير عدة تدفقات EPub إلى [`IDevice`](../../idevice/). سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد أو مؤقتات نشطة أو مهام رسوم متحركة أو انتهاء المهلة المحددة.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| مهلة | TimeSpan | فترة زمنية (TimeSpan) تمثل عدد المللي ثانية للانتظار، أو فترة زمنية تمثل -1 مللي ثانية للانتظار إلى ما لا نهاية. |
| المستندات | Stream[] | المستندات المراد عرضها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

تحدد طريقة لتصيير عدة مستندات EPub إلى [`IDevice`](../../idevice/) محدد، باستخدام رمز إلغاء لطلب إلغاء العملية.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| cancellationToken | CancellationToken | CancellationToken للمراقبة أثناء انتظار إكمال المهمة. |
| المصادر | Stream[] | مستندات EPub المراد تصييرها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

يصير مستند EPub إلى [`IDevice`](../../idevice/) المحدد.

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
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

يصير مستند EPub إلى [`IDevice`](../../idevice/) المحدد. سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد أو مؤقتات نشطة أو مهام رسوم متحركة أو انتهاء المهلة المحددة.

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
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

يصير عدة مستندات EPub إلى [`IDevice`](../../idevice/) المحدد.

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
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

يصير عدة مستندات EPub إلى [`IDevice`](../../idevice/) المحدد. سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد أو مؤقتات نشطة أو مهام رسوم متحركة أو انتهاء المهلة المحددة.

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
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
