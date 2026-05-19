---
title: "Clase CSSValue"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.css.CSSValue. Representa un valor simple o complejo. Un objeto CSSValue solo aparece en el contexto de una propiedad CSS."
type: docs

url: /es/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

Representa un valor simple o complejo. Un objeto CSSValue solo aparece en el contexto de una propiedad CSS.

```java
public abstract class CSSValue : DOMObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | La propiedad cssText de la interfaz `CSSValue` representa el valor actual calculado de la propiedad CSS. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Un código que define el tipo del valor. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Determina si el Object especificado es igual a esta instancia. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Devuelve un código hash para esta instancia. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Este método se usa para recuperar el Type del objeto ECMAScript. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Devuelve una cadena que representa esta instancia. |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | El valor es un valor personalizado. |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | El valor es heredado y el cssText contiene "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | El valor es un valor primitivo y se puede obtener una instancia de la interfaz CSSPrimitiveValue utilizando métodos de conversión específicos del enlace sobre esta instancia de la interfaz CSSValue. |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | El valor es una lista de CSSValue y se puede obtener una instancia de la interfaz CSSValueList utilizando métodos de casting específicos del enlace en esta instancia de la interfaz CSSValue. |

### Ver también

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
