---
title: "PageSetup Clase"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.rendering.PageSetup clase. Representa un objeto de configuración de página que se utiliza para la configuración de salida del conjunto de páginas"
type: docs

url: /es/java/com.aspose.html.rendering/pagesetup/
---
## PageSetup class

Representa un objeto de configuración de página que se utiliza para la configuración de la salida del conjunto de páginas.

```java
public class PageSetup
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getAdjustToWidestPage]
[setAdjustToWidestPage] Gets or sets flag that determines case when page size will be adjusted to widest page in document. This options is time-consuming so time of document processing can be increased in two times. Adjustment will take place only if widest page in document is wider than page size determined in `PageSetup`. Adjusted page size will be used for all pages in document. |
[getAnyPage]
[setAnyPage] Gets or sets all pages configuration in the the page-sequence. |
[getAtPagePriority]
[setAtPagePriority] Gets or sets [`AtPagePriority`](../atpagepriority/) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
[getFirstPage]
[setFirstPage] Gets or sets the first page configuration. |
| [getLeftPage](../../com.aspose.html.rendering/pagesetup/leftpage/) Obtiene la configuración de página impar. |
[getPageLayoutOptions]
[setPageLayoutOptions] Gets or sets the [`PageLayoutOptions`](../pagelayoutoptions/). Default value is None, any other value will override the [`AdjustToWidestPage`](./adjusttowidestpage/) behaviour. Works only with HTML documents. |
| [getRightPage](../../com.aspose.html.rendering/pagesetup/rightpage/) Obtiene la configuración de página par. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [setLeftRightPage](../../com.aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Establece la configuración de página Izquierda/Derecha. |

### Ver también

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
