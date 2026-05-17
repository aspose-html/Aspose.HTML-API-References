---
title: "Renderer-1.Render"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Renderer. يحدد طريقة لتصيير TDocument في IDevice المحدد"
type: docs

url: /ar/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

يحدد طريقة لتصيير !:TDocument في [`IDevice`](../../idevice/) المحدد.

```java
public void Render(IDevice device, TSource source)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| مستند | TSource | المستند. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

يحدد طريقة لتصيير !:TDocument في [`IDevice`](../../idevice/) المحدد. سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد، أو مؤقتات نشطة، أو مهام رسوم متحركة، أو انتهاء المهلة المحددة.

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| مستند | TSource | المستند. |
| مهلة | TimeSpan | TimeSpan يمثل عدد الملليثانية للانتظار، أو TimeSpan يمثل -1 ملليثانية للانتظار إلى أجل غير مسمى. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

يحدد طريقة لتصيير !:TDocument في [`IDevice`](../../idevice/) المحدد. سيتم تنفيذ التصيير بمجرد عدم وجود أي عمليات شبكة لتحميل الموارد، أو مؤقتات نشطة، أو مهام رسوم متحركة، أو انتهاء المهلة المحددة.

```java
public void Render(IDevice device, TSource source, int timeout)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| مستند | TSource | المستند. |
| مهلة | Int32 | عدد من الملليثواني يمثل عدد الملليثانية للانتظار، أو -1 ملليثانية للانتظار إلى أجل غير مسمى. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params TSource[]) {#render_1}

```java
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
