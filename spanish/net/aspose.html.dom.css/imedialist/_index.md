---
title: Interface IMediaList
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Css.IMediaList interfaz. La interfaz MediaList proporciona la abstracción de una colección ordenada de medios sin definir ni restringir cómo se implementa esta colección. Una lista vacía es lo mismo que una lista que contiene el medio todos.
type: docs
weight: 580
url: /es/net/aspose.html.dom.css/imedialist/
---
## IMediaList interface

La interfaz MediaList proporciona la abstracción de una colección ordenada de medios, sin definir ni restringir cómo se implementa esta colección. Una lista vacía es lo mismo que una lista que contiene el medio "todos".

```csharp
public interface IMediaList : IEnumerable<string>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Item](../../aspose.html.dom.css/imedialist/item/) { get; } | Devuelve el índice de la lista. Si el índice es mayor o igual que el número de medios en la lista, esto devuelve nulo. El índice de medios. |
| [Length](../../aspose.html.dom.css/imedialist/length/) { get; } | El número de medios en la lista. El rango de medios válidos es de 0 a longitud-1 inclusive. |
| [MediaText](../../aspose.html.dom.css/imedialist/mediatext/) { get; } | La representación textual analizable de la lista de medios. Esta es una lista separada por comas de medios. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AppendMedium](../../aspose.html.dom.css/imedialist/appendmedium/)(string) | Agrega el medio newMedium al final de la lista. Si el nuevoMedio ya está en uso, primero se elimina. |
| [DeleteMedium](../../aspose.html.dom.css/imedialist/deletemedium/)(string) | Elimina el medio indicado por oldMedium de la lista. |

### Ver también

* espacio de nombres [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* asamblea [Aspose.HTML](../../)


