---
title: "Renderer-1.Render"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Renderer. Define un método para renderizar TDocument en un IDevice especificado."
type: docs

url: /es/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

Define un método para renderizar !:TDocument en un [`IDevice`](../../idevice/) especificado.

```java
public void Render(IDevice device, TSource source)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dispositivo | IDevice | El dispositivo de salida. |
| documento | TSource | El documento. |

### Ver también

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

Define un método para renderizar !:TDocument en un [`IDevice`](../../idevice/) especificado. El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o que haya transcurrido el tiempo de espera especificado.

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dispositivo | IDevice | El dispositivo de salida. |
| documento | TSource | El documento. |
| timeout | TimeSpan | Un TimeSpan que representa la cantidad de milisegundos a esperar, o un TimeSpan que representa -1 milisegundo para esperar indefinidamente. |

### Ver también

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

Define un método para renderizar !:TDocument en un [`IDevice`](../../idevice/) especificado. El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o que haya transcurrido el tiempo de espera especificado.

```java
public void Render(IDevice device, TSource source, int timeout)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dispositivo | IDevice | El dispositivo de salida. |
| documento | TSource | El documento. |
| timeout | Int32 | Una cantidad de milisegundos que representa la cantidad de milisegundos a esperar, o -1 milisegundo para esperar indefinidamente. |

### Ver también

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### Ver también

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### Ver también

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### Ver también

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

### Ver también

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
