---
title: HtmlRenderer.Render
second_title: Referencia de API de Aspose.HTML para .NET
description: HtmlRenderer método. Define el método para renderizar múltiplesDocument s en específicoIDevice . El renderizado se realizará una vez que no haya ninguna operación de red para cargar recursos temporizadores activos tareas de animación o haya transcurrido el tiempo de espera especificado.
type: docs
weight: 20
url: /es/net/aspose.html.rendering/htmlrenderer/render/
---
## HtmlRenderer.Render method

Define el método para renderizar múltiples[`Document`](../../../aspose.html.dom/document/) s en específico[`IDevice`](../../idevice/) . El renderizado se realizará una vez que no haya ninguna operación de red para cargar recursos, temporizadores activos, tareas de animación o haya transcurrido el tiempo de espera especificado.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Document[] documents)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| device | IDevice | El dispositivo de salida. |
| timeout | TimeSpan | ATimeSpan que representa el número de milisegundos a esperar, o unTimeSpan eso representa -1 milisegundo para esperar indefinidamente. |
| documents | Document[] | Los documentos a rendir. |

### Ver también

* interface [IDevice](../../idevice/)
* class [Document](../../../aspose.html.dom/document/)
* class [HtmlRenderer](../)
* espacio de nombres [Aspose.Html.Rendering](../../htmlrenderer/)
* asamblea [Aspose.HTML](../../../)


