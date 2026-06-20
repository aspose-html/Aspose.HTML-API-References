---
title: "SVGLength Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.svg.datatypes.SVGLength Klasse. Das SVGLength Interface entspricht dem Grunddatentyp Länge. Ein SVGLength-Objekt kann als schreibgeschützt gekennzeichnet werden, was bedeutet, dass Versuche, das Objekt zu ändern, eine Ausnahme auslösen, wie unten beschrieben."
type: docs

url: /de/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

Das SVGLength-Interface entspricht dem Grunddatentyp Länge. Ein SVGLength-Objekt kann als schreibgeschützt deklariert werden, was bedeutet, dass Versuche, das Objekt zu ändern, eine Ausnahme auslösen, wie unten beschrieben.

```java
public class SVGLength : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) Der Typ des Werts, wie durch eine der auf diesem Interface definierten SVG_LENGTHTYPE_* Konstanten angegeben. |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Behalte denselben zugrunde liegenden gespeicherten Wert bei, setze jedoch den gespeicherten Einheit-Identifikator auf den angegebenen unitType zurück. Die Objektattribute unitType, valueInSpecifiedUnits und valueAsString können durch diese Methode geändert werden. Zum Beispiel, wenn der ursprüngliche Wert "0.5cm" war und die Methode aufgerufen wurde, um in Millimeter zu konvertieren, dann würde unitType zu SVG_LENGTHTYPE_MM geändert, valueInSpecifiedUnits würde auf den numerischen Wert 5 geändert und valueAsString würde zu "5mm" geändert. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und - optional - verwaltete Ressourcen frei. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | Setze den Wert als Zahl mit einem zugehörigen unitType zurück, wodurch die Werte aller Attribute des Objekts ersetzt werden. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | Ein Wert wurde unter Verwendung der in CSS2 definierten cm-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | Ein Wert wurde unter Verwendung der in CSS2 definierten em-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | Ein Wert wurde unter Verwendung der in CSS2 definierten ex-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | Ein Wert wurde unter Verwendung der in CSS2 definierten in-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | Ein Wert wurde unter Verwendung der in CSS2 definierten mm-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | Es wurde kein Einheitstyp angegeben (d. h. ein einheitenloser Wert wurde angegeben), was einen Wert in Benutzereinheiten bedeutet. |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | Ein Wert wurde unter Verwendung der in CSS2 definierten pc-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | Ein Prozentwert wurde angegeben. |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | Ein Wert wurde unter Verwendung der in CSS2 definierten pt-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | Ein Wert wurde unter Verwendung der in CSS2 definierten px-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | Der Einheitstyp ist keiner der vordefinierten Einheitstypen. Es ist ungültig, zu versuchen, einen neuen Wert dieses Typs zu definieren oder einen bestehenden Wert zu diesem Typ zu wechseln. |

### Siehe auch

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
