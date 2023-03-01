---
title: Enum PageLayoutOptions
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Rendering.PageLayoutOptions enumeración. Especifica indicadores que junto con otras opciones de PageSetup determinan los tamaños y diseños de las páginas. Estos indicadores se pueden combinar según sus descripciones.
type: docs
weight: 4380
url: /es/net/aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Especifica indicadores que, junto con otras opciones de PageSetup, determinan los tamaños y diseños de las páginas. Estos indicadores se pueden combinar según sus descripciones.

```csharp
[Flags]
public enum PageLayoutOptions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | Valor predeterminado que indica que PageLayoutOptions no afectará los tamaños y diseños de las páginas. |
| FitToContentWidth | `1` | Este indicador indica que el ancho de las páginas se determina a partir del tamaño del contenido en sí, no del ancho de página especificado. El ancho del contenido se calcula individualmente para cada página. |
| UseWidestPage | `2` | Cuando se combina conFitToContentWidth indica que el ancho de cada página será el mismo y será igual al tamaño de contenido más ancho entre todas las páginas. |
| FitToWidestContentWidth | `3` | Esta bandera indica que el ancho de la página está determinado por el tamaño del contenido en sí, no por el ancho de página especificado. El ancho de cada página será el mismo y será igual al tamaño de contenido más ancho entre todas las páginas. |
| FitToContentHeight | `10` | Esta marca indica que la altura de la página se determina a partir del tamaño del contenido en sí, no de la altura de página especificada. Todo el contenido de los documentos se ubicará en una sola página si se especifica esta marca. |
| ScaleToPageWidth | `100` | Esta bandera indica que el contenido del documento se escalará para ajustarse a la página donde la diferencia entre el ancho de página disponible y el contenido superpuesto es mayor. Choca conFitToContentWidth bandera y si ambas banderas se especifican solamenteScaleToPageWidth tendrá efecto. |
| ScaleToPageHeight | `1000` | Esta bandera indica que el contenido del documento se escalará para ajustarse a la altura de la primera página. Choca conFitToContentHeight bandera y si ambas banderas se especifican solamenteScaleToPageHeight surtirá efecto. Todo el contenido del documento se colocará en una sola página únicamente. |

### Ver también

* espacio de nombres [Aspose.Html.Rendering](../../aspose.html.rendering/)
* asamblea [Aspose.HTML](../../)


