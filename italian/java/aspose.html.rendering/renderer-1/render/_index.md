---
title: "Renderer-1.Render"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Renderer. Definisce un metodo per il rendering di TDocument nel IDevice specificato"
type: docs

url: /it/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

Definisce un metodo per il rendering di !:TDocument nel [`IDevice`](../../idevice/) specificato.

```java
public void Render(IDevice device, TSource source)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dispositivo | IDevice | Il dispositivo di output. |
| documento | TSource | Il documento. |

### Vedi anche

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

Definisce un metodo per il rendering di !:TDocument nel [`IDevice`](../../idevice/) specificato. Il rendering verrà eseguito una volta che non vi sono operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o il timeout specificato è trascorso.

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dispositivo | IDevice | Il dispositivo di output. |
| documento | TSource | Il documento. |
| timeout | TimeSpan | Un TimeSpan che rappresenta il numero di millisecondi da attendere, oppure un TimeSpan che rappresenta -1 millisecondo per attendere indefinitamente. |

### Vedi anche

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

Definisce un metodo per il rendering di !:TDocument nel [`IDevice`](../../idevice/) specificato. Il rendering verrà eseguito una volta che non vi sono operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o il timeout specificato è trascorso.

```java
public void Render(IDevice device, TSource source, int timeout)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dispositivo | IDevice | Il dispositivo di output. |
| documento | TSource | Il documento. |
| timeout | Int32 | Un numero di millisecondi che rappresenta il numero di millisecondi da attendere, oppure -1 millisecondo per attendere indefinitamente. |

### Vedi anche

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### Vedi anche

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### Vedi anche

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### Vedi anche

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

### Vedi anche

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
