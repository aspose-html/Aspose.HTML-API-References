---
title: "Clase TypeInfo"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.TypeInfo. El TypeInfo representa un tipo referenciado desde nodos Element o Attr especificados en los esquemas asociados con el documento."
type: docs

url: /es/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

El TypeInfo representa un tipo referenciado desde nodos Element o Attr, especificado en los esquemas asociados al documento.

```java
public class TypeInfo : DOMObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) El nombre de un tipo declarado para el elemento o atributo asociado, o null si es desconocido. |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) Obtiene el paquete del tipo. El paquete del tipo declarado para el elemento o atributo asociado o null si el elemento no tiene declaración o si no hay información de paquete disponible. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para obtener el objeto ECMAScript. |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | Este método devuelve si existe una derivación entre la definición de tipo de referencia, es decir, el TypeInfo sobre el cual se llama el método, y la otra definición de tipo, es decir, la que se pasa como parámetro. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | Si el esquema del documento es un XML Schema [XML Schema Part 1], esta constante representa la derivación por extensión. |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | Si el esquema del documento es un XML Schema [XML Schema Part 1], esta constante representa la lista. |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | Si el esquema del documento es un XML Schema [XML Schema Part 1], esta constante representa la derivación por restricción si están involucrados tipos complejos, o una restricción si están involucrados tipos simples. |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | Si el esquema del documento es un XML Schema [XML Schema Part 1], esta constante representa la unión si están involucrados tipos simples. |

### Ver también

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
