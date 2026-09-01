---
title: "Interfaz ICSSStyleDeclaration"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.css.ICSSStyleDeclaration interface. La interfaz CSSStyleDeclaration representa un objeto que es un bloque de declaración CSS y expone información de estilo y varios métodos y propiedades relacionados con el estilo."
type: docs

url: /es/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

La interfaz CSSStyleDeclaration representa un objeto que es un bloque de declaración CSS, y expone información de estilo y varios métodos y propiedades relacionados con el estilo.

Un objeto CSSStyleDeclaration puede exponerse usando tres APIs diferentes:

Mediante HTMLElement.style, que maneja los estilos inline de un solo elemento. Mediante la API [`CSSStyleSheet`](../icssstylesheet/). Por ejemplo, document.styleSheets[0].cssRules[0].style devuelve un objeto `CSSStyleDeclaration` en la primera regla CSS del primer stylesheet del documento. Mediante Window.getComputedStyle(), que expone el objeto `CSSStyleDeclaration` como una interfaz de solo lectura.

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) Se usa para recuperar las propiedades que han sido establecidas explícitamente en este bloque de declaración. El orden de las propiedades recuperadas con este método no tiene que coincidir con el orden en que fueron establecidas. Este método puede usarse para iterar sobre todas las propiedades en este bloque de declaración. |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) La propiedad de solo lectura devuelve un número entero de propiedades que han sido establecidas explícitamente en este bloque de declaración CSS. El rango de índices válidos es de 0 a length‑1 inclusive. |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) La propiedad de solo lectura CSSStyleDeclaration.parentRule devuelve un CSSRule que es el padre de este bloque de estilo, p. ej. un [`CSSStyleRule`](../icssstylerule/) que representa el estilo para un selector CSS. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | Se usa para obtener la representación de objeto del valor de una propiedad CSS si ha sido establecida explícitamente dentro de este bloque de declaración. Este método devuelve null si la propiedad es una propiedad abreviada. Los valores de propiedades abreviadas solo pueden accederse y modificarse como cadenas, usando los métodos getPropertyValue y setProperty. |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | Se usa para obtener la prioridad de una propiedad CSS (p. ej. el calificador "important") si la propiedad ha sido establecida explícitamente en este bloque de declaración. |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | La interfaz del método CSSStyleDeclaration.getPropertyValue() devuelve una cadena que contiene el valor de una propiedad CSS especificada. |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | La interfaz del método CSSStyleDeclaration.removeProperty() elimina una propiedad de un objeto de declaración de estilo CSS. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | La interfaz del método CSSStyleDeclaration.setProperty() se usa para establecer el valor de una propiedad con prioridad predeterminada dentro de este bloque de declaración. La prioridad predeterminada no es "important", es decir, String.Empty. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | La interfaz del método CSSStyleDeclaration.setProperty() se usa para establecer el valor de una propiedad con prioridad predeterminada dentro de este bloque de declaración. La prioridad predeterminada no es "important", es decir, String.Empty. |

## Observaciones

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referencia

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### Ver también

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
