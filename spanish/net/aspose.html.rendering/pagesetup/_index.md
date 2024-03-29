---
title: Class PageSetup
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Rendering.PageSetup clase. Representa un objeto de configuración de página que se utiliza para el conjunto de páginas de salida de configuración.
type: docs
weight: 4390
url: /es/net/aspose.html.rendering/pagesetup/
---
## PageSetup class

Representa un objeto de configuración de página que se utiliza para el conjunto de páginas de salida de configuración.

```csharp
public class PageSetup
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AdjustToWidestPage](../../aspose.html.rendering/pagesetup/adjusttowidestpage/) { get; set; } | Obtiene o establece el indicador que determina el caso en que el tamaño de la página se ajustará a la página más ancha del documento. Esta opción requiere mucho tiempo, por lo que el tiempo de procesamiento del documento se puede aumentar dos veces. El ajuste tendrá lugar solo si la página más ancha del documento es más ancha que el tamaño de página determinado en`PageSetup` . Se utilizará el tamaño de página ajustado para todas las páginas del documento. |
| [AnyPage](../../aspose.html.rendering/pagesetup/anypage/) { get; set; } | Obtiene o establece la configuración de todas las páginas en la secuencia de páginas. |
| [AtPagePriority](../../aspose.html.rendering/pagesetup/atpagepriority/) { get; set; } | Obtiene o establece[`AtPagePriority`](../atpagepriority/) que determinará el orden de aplicación de las declaraciones de tamaño de página. Por defecto, las opciones anularán css`@página` normas . |
| [FirstPage](../../aspose.html.rendering/pagesetup/firstpage/) { get; set; } | Obtiene o establece la configuración de la primera página. |
| [LeftPage](../../aspose.html.rendering/pagesetup/leftpage/) { get; } | Obtiene la configuración de la página impar. |
| [PageLayoutOptions](../../aspose.html.rendering/pagesetup/pagelayoutoptions/) { get; set; } | Obtiene o establece el[`PageLayoutOptions`](../pagelayoutoptions/) . El valor predeterminado esNone , cualquier otro valor anulará el[`AdjustToWidestPage`](./adjusttowidestpage/) comportamiento. Funciona solo con documentos HTML. |
| [RightPage](../../aspose.html.rendering/pagesetup/rightpage/) { get; } | Obtiene la configuración de página par. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetLeftRightPage](../../aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Establece la configuración de página izquierda/derecha. |

### Ver también

* espacio de nombres [Aspose.Html.Rendering](../../aspose.html.rendering/)
* asamblea [Aspose.HTML](../../)


