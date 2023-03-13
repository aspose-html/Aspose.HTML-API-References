---
title: Class SVGAngle
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Svg.DataTypes.SVGAngle klas. Die Schnittstelle SVGAngle entspricht dem Grunddatentyp Winkel.
type: docs
weight: 1060
url: /de/net/aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

Die Schnittstelle SVGAngle entspricht dem Grunddatentyp Winkel.

```csharp
public class SVGAngle : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svgangle/unittype/) { get; } | Der Typ des Werts, wie er von einer der auf dieser Schnittstelle definierten SVG_ANGLETYPE_*-Konstanten angegeben wird. |
| [Value](../../aspose.html.dom.svg.datatypes/svgangle/value/) { get; set; } | Der Winkelwert als Fließkommawert in Grad. Das Festlegen dieses Attributs bewirkt, dass valueInSpecifiedUnits und valueAsString automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svgangle/valueasstring/) { get; set; } | Der Winkelwert als Zeichenfolgenwert in den durch unitType ausgedrückten Einheiten. Das Festlegen dieses Attributs bewirkt, dass value, valueInSpecifiedUnits und unitType automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | Der Winkelwert als Fließkommawert in den Einheiten, ausgedrückt durch unitType. Das Festlegen dieses Attributs bewirkt, dass value und valueAsString automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Den gleichen zugrunde liegenden gespeicherten Wert beibehalten, aber die gespeicherte Einheitenkennung auf den angegebenen unitType zurücksetzen. Die Objektattribute unitType, valueInSpecifiedUnits und valueAsString können als Ergebnis dieser Methode geändert werden. |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und – optional – verwaltete Ressourcen frei. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Setzt den Wert als Zahl mit einem zugeordneten unitType zurück und ersetzt dadurch die Werte für alle Attribute des Objekts. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgangle/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | Der Einheitentyp wurde explizit auf Grad gesetzt. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | Der Einheitentyp ist Radiant. |
| const [SVG_ANGLETYPE_RAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | Der Einheitentyp ist Radiant. |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | Der Einheitentyp ist keiner der vordefinierten Einheitentypen. Es ist ungültig, einen neuen Wert dieses Typs zu definieren oder einen vorhandenen Wert auf diesen Typ umzustellen. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | Es wurde kein Einheitentyp angegeben (dh es wurde ein einheitenloser Wert angegeben). Bei Winkeln wird ein Wert ohne Einheit so behandelt, als ob Grad angegeben wäre. |

### Siehe auch

* class [SVGValueType](../svgvaluetype/)
* namensraum [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* Montage [Aspose.HTML](../../)


