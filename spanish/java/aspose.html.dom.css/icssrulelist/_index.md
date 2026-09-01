---
title: "ICSSRuleList Interfaz"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.css.ICSSRuleList interfaz. Un CSSRuleList representa una colección ordenada de objetos CSSRule de solo lectura"
type: docs

url: /es/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

Un CSSRuleList representa una colección ordenada de objetos [`CSSRule`](../icssrule/) de solo lectura.

Aunque el objeto CSSRuleList es de solo lectura y no puede modificarse directamente, se considera un objeto en vivo, ya que su contenido puede cambiar con el tiempo.

Para editar las reglas subyacentes devueltas por los objetos [`CSSRule`](../icssrule/), use CSSStyleSheet.insertRule() y CSSStyleSheet.deleteRule(), que son métodos de [`CSSStyleSheet`](../icssstylesheet/).

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) Se usa para recuperar una regla CSS mediante el método item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). El orden en esta colección representa el orden de las reglas en la hoja de estilo CSS. Si el índice es mayor o igual que el número de reglas en la lista, esto devuelve null. |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) La propiedad length de la interfaz `CSSRuleList` devuelve el número de objetos [`CSSRule`](../icssrule/) en la lista. |

### Ver también

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
