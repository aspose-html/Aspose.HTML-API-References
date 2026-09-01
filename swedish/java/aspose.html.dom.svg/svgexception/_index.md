---
title: "SVGException-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.svg.SVGException klass. Detta undantag kastas när en specifik SVG‑operation är omöjlig att utföra"
type: docs

url: /sv/java/com.aspose.html.dom.svg/svgexception/
---
## SVGException class

Detta undantag kastas när en specifik SVG‑operation är omöjlig att utföra.

```java
public class SVGException : PlatformException
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGException](svgexception/)(ushort) | Initierar en ny instans av `SVGException`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getCode](../../com.aspose.html.dom.svg/svgexception/code/) En kod som identifierar orsaken till att den begärda operationen inte kunde utföras. Värdet för detta medlemskap kommer att vara en av konstanterna i SVGException-kodgruppen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_invalid_value_err/) | Kastas när ett ogiltigt värde skickas till en operation eller tilldelas ett attribut. |
| const [SVG_MATRIX_NOT_INVERTABLE](../../com.aspose.html.dom.svg/svgexception/svg_matrix_not_invertable/) | Kastas när ett försök görs att invertera en matris som inte är inverterbar. |
| const [SVG_WRONG_TYPE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_wrong_type_err/) | Kastas när ett objekt av fel typ skickas till en operation. |

### Se även

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
