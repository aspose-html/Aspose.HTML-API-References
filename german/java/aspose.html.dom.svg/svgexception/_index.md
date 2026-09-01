---
title: "SVGException Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.svg.SVGException Klasse. Diese Ausnahme wird ausgelöst, wenn eine bestimmte SVG-Operation nicht durchgeführt werden kann."
type: docs

url: /de/java/com.aspose.html.dom.svg/svgexception/
---
## SVGException class

Diese Ausnahme wird ausgelöst, wenn eine bestimmte SVG-Operation nicht ausgeführt werden kann.

```java
public class SVGException : PlatformException
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGException](svgexception/)(ushort) | Initialisiert eine neue Instanz der `SVGException` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getCode](../../com.aspose.html.dom.svg/svgexception/code/) Ein Code, der den Grund identifiziert, warum die angeforderte Operation nicht durchgeführt werden konnte. Der Wert dieses Members wird einer der Konstanten in der SVGException-Codegruppe sein. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_invalid_value_err/) | Wird ausgelöst, wenn ein ungültiger Wert an eine Operation übergeben oder einem Attribut zugewiesen wird. |
| const [SVG_MATRIX_NOT_INVERTABLE](../../com.aspose.html.dom.svg/svgexception/svg_matrix_not_invertable/) | Wird ausgelöst, wenn versucht wird, eine Matrix zu invertieren, die nicht invertierbar ist. |
| const [SVG_WRONG_TYPE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_wrong_type_err/) | Wird ausgelöst, wenn ein Objekt des falschen Typs an eine Operation übergeben wird. |

### Siehe auch

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
