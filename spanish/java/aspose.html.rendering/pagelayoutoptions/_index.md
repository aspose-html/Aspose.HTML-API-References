---
title: "Enumeración PageLayoutOptions"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.rendering.PageLayoutOptions enum. Especifica banderas que, junto con otras opciones de PageSetup, determinan los tamaños y diseños de las páginas. Estas banderas pueden combinarse según sus descripciones."
type: docs

url: /es/java/com.aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Especifica banderas que, junto con otras opciones de PageSetup, determinan los tamaños y disposiciones de las páginas. Estas banderas pueden combinarse según sus descripciones.

```java
[Flags]
public enum PageLayoutOptions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | Valor predeterminado que indica que el PageLayoutOptions no afectará los tamaños y diseños de las páginas. |
| FitToContentWidth | `1` | Esta bandera indica que el ancho de las páginas se determina a partir del tamaño del contenido mismo, no del ancho de página especificado. El ancho del contenido se calcula individualmente para cada página. |
| UseWidestPage | `2` | Cuando se combina con FitToContentWidth indica que el ancho de cada página será el mismo y será igual al tamaño de contenido más ancho entre todas las páginas. |
| FitToWidestContentWidth | `3` | Esta bandera indica que el ancho de la página se determina a partir del tamaño del contenido mismo, no del ancho de página especificado. El ancho de cada página será el mismo y será igual al tamaño de contenido más ancho entre todas las páginas. |
| FitToContentHeight | `10` | Esta bandera indica que la altura de la página se determina a partir del tamaño del contenido mismo, no de la altura de página especificada. Todo el contenido del documento se ubicará en una sola página si se especifica esta bandera. |
| ScaleToPageWidth | `100` | Esta bandera indica que el contenido del documento se escalará para ajustarse a la página donde la diferencia entre el ancho de página disponible y el contenido superpuesto sea mayor. Entró en conflicto con la bandera FitToContentWidth y, si ambas banderas están especificadas, solo ScaleToPageWidth tendrá efecto. |
| ScaleToPageHeight | `1000` | Esta bandera indica que el contenido del documento se escalará para ajustarse a la altura de la primera página. Entró en conflicto con la bandera FitToContentHeight y, si ambas banderas están especificadas, solo ScaleToPageHeight tendrá efecto. Todo el contenido del documento se colocará únicamente en una sola página. |

### Ver también

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
