---
title: "ICSSValueList.Item"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad ICSSValueList. Este método se usa para obtener un CSSValue por índice ordinal. El orden en esta colección representa el orden de los valores en la propiedad de estilo CSS. Si el índice es mayor o igual que el número de valores en la lista, este devuelve null."
type: docs

url: /es/java/com.aspose.html.dom.css/icssvaluelist/item/
---
## ICSSValueList indexer

Este método se usa para obtener un CSSValue por índice ordinal. El orden en esta colección representa el orden de los valores en la propiedad de estilo CSS. Si el índice es mayor o igual que el número de valores en la lista, esto devuelve null.

Ver también el [CSSOM](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList)[#CSSValueList](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList).

```java
public CSSValue this[int index] { get; }
```

### Valor de retorno

El [`CSSValue`](../../cssvalue/) en la posición de índice en la [`CSSValueList`](../../cssvaluelist/), o null si no es un índice válido.

### Property Value

El índice en la colección.

## Observaciones

Esta característica se definió originalmente en la especificación [DOM Style Level 2](https://www.w3.org/TR/DOM-Level-2-Style), pero ha sido descartada de cualquier esfuerzo de estandarización desde entonces.

Ha sido reemplazada por una API moderna, pero incompatible, [CSS Typed Object Model API](https://developer.mozilla.org/en-US/docs/Web/API/CSS_Typed_OM_API) que ahora está en la vía estándar.

### Ver también

* class [CSSValue](../../cssvalue/)
* interface [ICSSValueList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
