---
title: EpubRenderer.Render
second_title: Referencia de API de Aspose.HTML para .NET
description: EpubRenderer método. Define el método para renderizar múltiples EPubStream s en específicoIDevice . El renderizado se realizará una vez que no haya ninguna operación de red para cargar recursos temporizadores activos tareas de animación o haya transcurrido el tiempo de espera especificado.
type: docs
weight: 20
url: /es/net/aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_9}

Define el método para renderizar múltiples EPubStream s en específico[`IDevice`](../../idevice/) . El renderizado se realizará una vez que no haya ninguna operación de red para cargar recursos, temporizadores activos, tareas de animación o haya transcurrido el tiempo de espera especificado.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Stream[] documents)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| device | IDevice | El dispositivo de salida. |
| timeout | TimeSpan | ATimeSpan que representa el número de milisegundos a esperar, o unTimeSpan eso representa -1 milisegundo para esperar indefinidamente. |
| documents | Stream[] | Los documentos a rendir. |

### Ver también

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* espacio de nombres [Aspose.Html.Rendering](../../epubrenderer/)
* asamblea [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Representa el documento EPub en el[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, Stream document, Configuration configuration)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| device | IDevice | El dispositivo. |
| document | Stream | El documento. |
| configuration | Configuration | La configuración. |

### Ver también

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* espacio de nombres [Aspose.Html.Rendering](../../epubrenderer/)
* asamblea [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Representa el documento EPub en el[`IDevice`](../../idevice/) . El renderizado se realizará una vez que no haya ninguna operación de red para cargar recursos, temporizadores activos, tareas de animación o haya transcurrido el tiempo de espera especificado.

```csharp
public void Render(IDevice device, Stream document, Configuration configuration, TimeSpan timeout)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| device | IDevice | El dispositivo. |
| document | Stream | El documento. |
| configuration | Configuration | La configuración. |
| timeout | TimeSpan | ATimeSpan que representa el número de milisegundos a esperar, o unTimeSpan eso representa -1 milisegundo para esperar indefinidamente. |

### Ver también

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* espacio de nombres [Aspose.Html.Rendering](../../epubrenderer/)
* asamblea [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Representa múltiples documentos EPub en[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| device | IDevice | El dispositivo. |
| documents | IList`1 | ElIList de documentos a rendir. |
| configuration | Configuration | La configuración. |

### Ver también

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* espacio de nombres [Aspose.Html.Rendering](../../epubrenderer/)
* asamblea [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Representa múltiples documentos EPub en[`IDevice`](../../idevice/) . El renderizado se realizará una vez que no haya ninguna operación de red para cargar recursos, temporizadores activos, tareas de animación o haya transcurrido el tiempo de espera especificado.

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration, 
    TimeSpan timeout)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| device | IDevice | El dispositivo. |
| documents | IList`1 | ElIList de documentos a rendir. |
| configuration | Configuration | La configuración. |
| timeout | TimeSpan | ATimeSpan que representa el número de milisegundos a esperar, o unTimeSpan eso representa -1 milisegundo para esperar indefinidamente. |

### Ver también

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* espacio de nombres [Aspose.Html.Rendering](../../epubrenderer/)
* asamblea [Aspose.HTML](../../../)


