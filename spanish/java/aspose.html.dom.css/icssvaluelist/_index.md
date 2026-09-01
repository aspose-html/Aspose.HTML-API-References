---
title: "Interfaz ICSSValueList"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.dom.css.ICSSValueList. La interfaz CSSValueList deriva de la interfaz CSSValue y proporciona la abstracción de una colección ordenada de valores CSS."
type: docs

url: /es/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

La interfaz CSSValueList deriva de la interfaz [`CSSValue`](../cssvalue/) y proporciona la abstracción de una colección ordenada de valores CSS.

Algunas propiedades permiten una lista vacía en su sintaxis. En ese caso, estas propiedades toman el identificador none. Por lo tanto, una lista vacía significa que la propiedad tiene el valor none.

Los elementos en CSSValueList son accesibles mediante un índice entero, comenzando en 0.

```java
public interface ICSSValueList
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) Este método se usa para obtener un CSSValue por índice ordinal. El orden en esta colección representa el orden de los valores en la propiedad de estilo CSS. Si el índice es mayor o igual que el número de valores en la lista, devuelve null. |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) La propiedad de solo lectura length de la interfaz CSSValueList representa el número de CSSValues en la lista. El rango de valores válidos de los índices es de 0 a length-1 inclusive. |

## Observaciones

Esta interfaz formó parte de un intento de crear un Modelo de Objetos CSS tipado. Ese intento ha sido abandonado, y la mayoría de los navegadores no lo implementan.

Para lograr su objetivo, puede usar:

el [CSS Object Model](https://drafts.csswg.org/cssom/), sin tipado, ampliamente soportado, o el moderno [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects), menos soportado y considerado experimental.

### Ver también

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
