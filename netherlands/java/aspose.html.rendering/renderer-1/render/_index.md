---
title: "Renderer-1.Render"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Renderer-methode. Definieert een methode voor het renderen van TDocument naar een opgegeven IDevice"
type: docs

url: /nl/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

Definieert een methode voor het renderen van !:TDocument naar een opgegeven [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, TSource source)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| document | TSource | Het document. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

Definieert een methode voor het renderen van !:TDocument naar een opgegeven [`IDevice`](../../idevice/). Het renderen wordt uitgevoerd zodra er geen netwerkbewerkingen meer zijn voor het laden van bronnen, actieve timers, animatietaken of wanneer de opgegeven timeout is verstreken.

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| document | TSource | Het document. |
| time‑out | TimeSpan | Een TimeSpan die het aantal milliseconden aangeeft om te wachten, of een TimeSpan die -1 milliseconde aangeeft om onbeperkt te wachten. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

Definieert een methode voor het renderen van !:TDocument naar een opgegeven [`IDevice`](../../idevice/). Het renderen wordt uitgevoerd zodra er geen netwerkbewerkingen meer zijn voor het laden van bronnen, actieve timers, animatietaken of wanneer de opgegeven timeout is verstreken.

```java
public void Render(IDevice device, TSource source, int timeout)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| document | TSource | Het document. |
| time‑out | Int32 | Een aantal milliseconden dat het aantal milliseconden aangeeft om te wachten, of -1 milliseconde om onbeperkt te wachten. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### Zie ook

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### Zie ook

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### Zie ook

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

### Zie ook

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
