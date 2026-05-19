---
title: "MhtmlRenderer.Render"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método MhtmlRenderer. Renderiza múltiples documentos MHTML en el IDevice especificado. El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o que haya transcurrido el tiempo de espera especificado."
type: docs

url: /es/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Renderiza múltiples documentos MHTML en el [`IDevice`](../../idevice/) especificado. El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o que haya transcurrido el tiempo de espera especificado.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dispositivo | IDevice | El dispositivo. |
| tiempo de espera | TimeSpan | Un TimeSpan que representa la cantidad de milisegundos a esperar, o un TimeSpan que representa -1 milisegundo para esperar indefinidamente. |
| documentos | Stream[] | Los documentos a renderizar. |

### Ver también

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Define un método para renderizar múltiples documentos MHTML en un [`IDevice`](../../idevice/) específico, utilizando un token de cancelación para solicitar la cancelación de la operación.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dispositivo | IDevice | El dispositivo de salida. |
| cancellationToken | CancellationToken | Un CancellationToken para observar mientras se espera que la tarea se complete. |
| fuentes | Stream[] | Los documentos MHTML a renderizar. |

### Ver también

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Renderiza el documento MHTML en el [`IDevice`](../../idevice/) especificado.

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dispositivo | IDevice | El dispositivo. |
| documento | Flujo | El documento. |
| configuración | Configuración | La configuración. |

### Ver también

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Renderiza el documento MHTML en el [`IDevice`](../../idevice/) especificado. El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o haya transcurrido el tiempo de espera especificado.

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dispositivo | IDevice | El dispositivo. |
| documento | Flujo | El documento. |
| configuración | Configuración | La configuración. |
| tiempo de espera | TimeSpan | Un TimeSpan que representa la cantidad de milisegundos a esperar, o un TimeSpan que representa -1 milisegundo para esperar indefinidamente. |

### Ver también

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Renderiza múltiples documentos MHTML en el [`IDevice`](../../idevice/) especificado.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dispositivo | IDevice | El dispositivo. |
| documentos | IList`1 | La IList de documentos a renderizar. |
| configuración | Configuración | La configuración. |

### Ver también

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Renderiza múltiples documentos MHTML en el [`IDevice`](../../idevice/) especificado. El renderizado se realizará una vez que no haya operaciones de red para cargar recursos, temporizadores activos, tareas de animación o que haya transcurrido el tiempo de espera especificado.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dispositivo | IDevice | El dispositivo. |
| documentos | IList`1 | La IList de documentos a renderizar. |
| configuración | Configuración | La configuración. |
| tiempo de espera | TimeSpan | Un TimeSpan que representa la cantidad de milisegundos a esperar, o un TimeSpan que representa -1 milisegundo para esperar indefinidamente. |

### Ver también

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
