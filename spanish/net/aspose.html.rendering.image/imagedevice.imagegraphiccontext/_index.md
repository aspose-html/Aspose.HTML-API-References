---
title: Class ImageDevice.ImageGraphicContext
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Rendering.Image.ImageDeviceImageGraphicContext clase. Contiene los parámetros de control de gráficos actuales para elImageDevice . Estos parámetros definen el marco global dentro del cual se ejecutan los operadores gráficos.
type: docs
weight: 4310
url: /es/net/aspose.html.rendering.image/imagedevice.imagegraphiccontext/
---
## ImageDevice.ImageGraphicContext class

Contiene los parámetros de control de gráficos actuales para el[`ImageDevice`](../imagedevice/) . Estos parámetros definen el marco global dentro del cual se ejecutan los operadores gráficos.

```csharp
public class ImageGraphicContext : GraphicContext
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageGraphicContext](imagegraphiccontext/)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Establece u obtiene el espacio entre caracteres. |
| virtual [FillBrush](../../aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Establece u obtiene el objeto de pincel que se usa para rellenar el interior de los caminos. |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | Establece u obtiene el objeto de fuente de tipo verdadero que se utiliza para representar texto. |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Establece u obtiene el tamaño de fuente del texto. |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Establece u obtiene el estilo de fuente del texto. |
| virtual [LineCap](../../aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Establece u obtiene el código que especifica la forma de los puntos finales para cualquier ruta abierta que se trazo. |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Establece u obtiene el desplazamiento de fase del patrón de trazos de línea actual. |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Establece u obtiene la descripción del patrón de guiones que se usará cuando se trazan trazos. |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | Conjuntos de obtiene el estilo de las líneas discontinuas de un trazo trazado. |
| virtual [LineJoin](../../aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Establece u obtiene el código que especifica la forma de las uniones entre los segmentos conectados de un trazado trazado. |
| virtual [LineWidth](../../aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Establece u obtiene el grosor de los trazos a trazar. |
| virtual [MiterLimit](../../aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Establece u obtiene la longitud máxima de las uniones de líneas a inglete para trayectos trazados. Este parámetro limita la longitud de los "picos" producidos cuando los segmentos de línea se unen en ángulos agudos. |
| virtual [StrokeBrush](../../aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Establece u obtiene el objeto de pincel que se utiliza para trazos trazados. |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | Obtiene un[`TextInfo`](../../aspose.html.rendering/textinfo/) objeto que contiene información sobre el texto renderizado. |
| override [TransformationMatrix](../../aspose.html.rendering.image/imagegraphiccontext/transformationmatrix/) { get; set; } | Establece u obtiene la matriz de transformación. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../aspose.html.rendering.image/imagegraphiccontext/clone/)() | Crea una nueva instancia de una clase GdiGraphicContext con los mismos valores de propiedad que una instancia existente. |
| override [Transform](../../aspose.html.rendering.image/imagegraphiccontext/transform/)(Matrix) | Modifica la matriz de transformación actual multiplicando la matriz especificada. |

### Ver también

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [ImageDevice](../imagedevice/)
* espacio de nombres [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* asamblea [Aspose.HTML](../../)


