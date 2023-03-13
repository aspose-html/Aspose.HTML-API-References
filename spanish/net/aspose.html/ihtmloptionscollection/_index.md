---
title: Interface IHTMLOptionsCollection
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.IHTMLOptionsCollection interfaz. UnHTMLOptionsCollection es una lista de nodos que representan el elemento de opción HTML . Se puede acceder a un nodo individual mediante el índice ordinal o el índice del nodo.nombre oidentificación atributos Se supone que las colecciones en HTML DOM están activas lo que significa que se actualizan automáticamente cuando se cambia el documento subyacente.
type: docs
weight: 3680
url: /es/net/aspose.html/ihtmloptionscollection/
---
## IHTMLOptionsCollection interface

Un`HTMLOptionsCollection` es una lista de nodos que representan el elemento de opción HTML . Se puede acceder a un nodo individual mediante el índice ordinal o el índice del nodo.`nombre` o`identificación` atributos Se supone que las colecciones en HTML DOM están activas, lo que significa que se actualizan automáticamente cuando se cambia el documento subyacente.

Véase también el[Especificación HTML de nivel 2 del modelo de objeto de documento (DOM)](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109). @desde DOM Nivel 2

```csharp
public interface IHTMLOptionsCollection : IEnumerable<Element>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Item](../../aspose.html/ihtmloptionscollection/item/) { get; } | Devuelve el elemento índice de la colección. Si el índice es mayor o igual que el número de nodos en la lista, esto devuelve nulo. (2 indexers) |
| [Length](../../aspose.html/ihtmloptionscollection/length/) { get; } | El número de nodos en la lista. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [NamedItem](../../aspose.html/ihtmloptionscollection/nameditem/)(string) | El método devuelve el elemento índice de la colección. http://www.w3.org/TR/DOM-Level-2-HTML/html.html#HTMLOptionsCollection-namedItem |

### Ver también

* class [Element](../../aspose.html.dom/element/)
* espacio de nombres [Aspose.Html](../../aspose.html/)
* asamblea [Aspose.HTML](../../)


