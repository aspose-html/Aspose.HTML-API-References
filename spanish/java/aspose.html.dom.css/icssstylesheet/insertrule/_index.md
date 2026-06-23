---
title: "ICSSStyleSheet.InsertRule"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método ICSSStyleSheet. El método CSSStyleSheet.insertRule inserta una nueva regla CSS en la hoja de estilo actual con algunas restricciones"
type: docs

url: /es/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

El método CSSStyleSheet.insertRule() inserta una nueva regla CSS en la hoja de estilo actual, con algunas restricciones.

Nota: Aunque insertRule() es exclusivamente un método de [`CSSStyleSheet`](../), en realidad inserta la regla en CSSStyleSheet.cssRules — su [`CSSRuleList`](../../icssrulelist/) interno.

```java
public long InsertRule(String rule, int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regla | Cadena | Una cadena que contiene la regla a insertar. Lo que la regla insertada debe contener depende de su tipo: |
| index | Int32 | Un entero positivo menor o igual que stylesheet.cssRules.length, que representa la posición de la regla recién insertada en CSSStyleSheet.cssRules. El valor predeterminado es 0. |

### Valor devuelto

El índice de la regla recién insertada dentro de la lista de reglas de la hoja de estilo.

## Observaciones

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referencia

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### Ver también

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
