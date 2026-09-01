---
title: "Renderer-1.Render"
second_title: "Aspose.HTML för Java API-referens"
description: "Renderarmetod. Definierar en metod för att rendera TDocument till angivet IDevice"
type: docs

url: /sv/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

Definierar en metod för att rendera !:TDocument till angivet [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, TSource source)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Utdataenheten. |
| dokument | TSource | Dokumentet. |

### Se även

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

Definierar en metod för att rendera !:TDocument till angivet [`IDevice`](../../idevice/). Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animation tasks eller när den angivna tidsgränsen har löpt ut.

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Utdataenheten. |
| dokument | TSource | Dokumentet. |
| timeout | TimeSpan | En TimeSpan som representerar antalet millisekunder att vänta, eller en TimeSpan som representerar -1 millisekund för att vänta oändligt. |

### Se även

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

Definierar en metod för att rendera !:TDocument till angivet [`IDevice`](../../idevice/). Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animation tasks eller när den angivna tidsgränsen har löpt ut.

```java
public void Render(IDevice device, TSource source, int timeout)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Utdataenheten. |
| dokument | TSource | Dokumentet. |
| timeout | Int32 | Ett antal millisekunder som representerar antalet millisekunder att vänta, eller -1 millisekund för att vänta oändligt. |

### Se även

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### Se även

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### Se även

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### Se även

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

### Se även

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
