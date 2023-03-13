---
title: Class TypeInfo
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.TypeInfo clase. TypeInfo representa un tipo al que se hace referencia desde los nodos Element o Attr especificado en los esquemas asociados con el documento.
type: docs
weight: 2530
url: /es/net/aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo representa un tipo al que se hace referencia desde los nodos Element o Attr, especificado en los esquemas asociados con el documento.

```csharp
public class TypeInfo : DOMObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [TypeName](../../aspose.html.dom/typeinfo/typename/) { get; } | El nombre de un tipo declarado para el elemento o atributo asociado, o nulo si se desconoce. |
| [TypeNamespace](../../aspose.html.dom/typeinfo/typenamespace/) { get; } | Obtiene el espacio de nombres de tipo. El espacio de nombres del tipo declarado para el elemento o atributo asociado o nulo si el elemento no tiene declaración o si no hay información de espacio de nombres disponible. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [IsDerivedFrom](../../aspose.html.dom/typeinfo/isderivedfrom/)(string, string, ulong) | Este método devuelve si existe una derivación entre la definición de tipo de referencia, es decir, el TypeInfo sobre el que se llama al método, y la otra definición de tipo, es decir, la que se pasa como parámetros. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.html.dom/typeinfo/derivation_extension/) | Si el esquema del documento es un Esquema XML [Esquema XML Parte 1], esta constante representa la derivación por extensión. |
| const [DERIVATION_LIST](../../aspose.html.dom/typeinfo/derivation_list/) | Si el esquema del documento es un Esquema XML [Esquema XML Parte 1], esta constante representa la lista. |
| const [DERIVATION_RESTRICTION](../../aspose.html.dom/typeinfo/derivation_restriction/) | Si el esquema del documento es un Esquema XML [Esquema XML Parte 1], esta constante representa la derivación por restricción si se trata de tipos complejos, o una restricción si se trata de tipos simples. |
| const [DERIVATION_UNION](../../aspose.html.dom/typeinfo/derivation_union/) | Si el esquema del documento es un Esquema XML [Esquema XML Parte 1], esta constante representa la unión si se trata de tipos simples. |

### Ver también

* class [DOMObject](../domobject/)
* espacio de nombres [Aspose.Html.Dom](../../aspose.html.dom/)
* asamblea [Aspose.HTML](../../)


