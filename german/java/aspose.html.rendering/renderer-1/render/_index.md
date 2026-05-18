---
title: "Renderer-1.Render"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Renderer‑Methode. Definiert eine Methode zum Rendern von TDocument in ein angegebenes IDevice"
type: docs

url: /de/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

Definiert eine Methode zum Rendern von !:TDocument in ein angegebenes [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, TSource source)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Ausgabegerät. |
| Dokument | TSource | Das Dokument. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

Definiert eine Methode zum Rendern von !:TDocument in ein angegebenes [`IDevice`](../../idevice/). Das Rendering wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben mehr laufen oder die angegebene Zeitüberschreitung abgelaufen ist.

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Ausgabegerät. |
| Dokument | TSource | Das Dokument. |
| timeout | TimeSpan | Ein TimeSpan, das die Anzahl der Millisekunden angibt, die gewartet werden soll, oder ein TimeSpan, das -1 Millisekunde für unbegrenztes Warten darstellt. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

Definiert eine Methode zum Rendern von !:TDocument in ein angegebenes [`IDevice`](../../idevice/). Das Rendering wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben mehr laufen oder die angegebene Zeitüberschreitung abgelaufen ist.

```java
public void Render(IDevice device, TSource source, int timeout)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Ausgabegerät. |
| Dokument | TSource | Das Dokument. |
| timeout | Int32 | Eine Anzahl von Millisekunden, die die zu wartende Zeit in Millisekunden angibt, oder -1 Millisekunde für unbegrenztes Warten. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### Siehe auch

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

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
