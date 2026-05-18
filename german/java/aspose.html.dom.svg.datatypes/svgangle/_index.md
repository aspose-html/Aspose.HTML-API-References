---
title: "SVGAngle Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.svg.datatypes.SVGAngle Klasse. Das SVGAngle-Interface entspricht dem Grunddatentyp angle"
type: docs

url: /de/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

Das SVGAngle-Interface entspricht dem Grunddatentyp Winkel.

```java
public class SVGAngle : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) Der Typ des Wertes, wie durch eine der auf diesem Interface definierten SVG_ANGLETYPE_*-Konstanten angegeben. |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Behalte den gleichen zugrunde liegenden gespeicherten Wert bei, setze jedoch die gespeicherte Einheitkennung auf den angegebenen unitType zurück. Objektattribute unitType, valueInSpecifiedUnits und valueAsString können als Ergebnis dieser Methode geändert werden. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und - optional - verwaltete Ressourcen frei. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript‑Objekt abzurufen. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Setze den Wert als Zahl mit einem zugehörigen unitType zurück, wodurch die Werte aller Attribute des Objekts ersetzt werden. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | Der Einheitstyp wurde explizit auf Grad gesetzt. |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | Der Einheitstyp ist Radiant. |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | Der Einheitstyp ist Radiant. |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | Der Einheitstyp ist keiner der vordefinierten Einheitstypen. Es ist ungültig, zu versuchen, einen neuen Wert dieses Typs zu definieren oder einen bestehenden Wert zu diesem Typ zu wechseln. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | Es wurde kein Einheitstyp angegeben (d. h. ein einheitenloser Wert wurde spezifiziert). Für Winkel wird ein einheitenloser Wert genauso behandelt, als wären Grad angegeben. |

### Siehe auch

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
