---
title: Class SVGLength
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Svg.DataTypes.SVGLength klas. Die SVGLengthSchnittstelle entspricht dem Basisdatentyp length. Ein SVGLengthObjekt kann als schreibgeschützt gekennzeichnet werden was bedeutet dass Versuche das Objekt zu ändern dazu führen dass eine Ausnahme ausgelöst wird wie unten beschrieben.
type: docs
weight: 1200
url: /de/net/aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

Die SVGLength-Schnittstelle entspricht dem Basisdatentyp length. Ein SVGLength-Objekt kann als schreibgeschützt gekennzeichnet werden, was bedeutet, dass Versuche, das Objekt zu ändern, dazu führen, dass eine Ausnahme ausgelöst wird, wie unten beschrieben.

```csharp
public class SVGLength : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svglength/unittype/) { get; } | Der Typ des Werts, wie er von einer der auf dieser Schnittstelle definierten SVG_LENGTHTYPE_*-Konstanten angegeben wird. |
| [Value](../../aspose.html.dom.svg.datatypes/svglength/value/) { get; set; } | Der Wert als Fließkommawert in Benutzereinheiten. Das Festlegen dieses Attributs bewirkt, dass valueInSpecifiedUnits und valueAsString automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svglength/valueasstring/) { get; set; } | Der Wert als Zeichenfolgenwert in den durch unitType ausgedrückten Einheiten. Das Festlegen dieses Attributs bewirkt, dass value, valueInSpecifiedUnits und unitType automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | Der Wert als Fließkommawert in den durch unitType ausgedrückten Einheiten. Das Festlegen dieses Attributs bewirkt, dass value und valueAsString automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Den gleichen zugrunde liegenden gespeicherten Wert beibehalten, aber die gespeicherte Einheitenkennung auf den angegebenen unitType zurücksetzen. Die Objektattribute unitType, valueInSpecifiedUnits und valueAsString können als Ergebnis dieser Methode geändert werden. Wenn der ursprüngliche Wert beispielsweise „0,5 cm“ war und die Methode aufgerufen wurde, um ihn in Millimeter umzuwandeln, würde der unitType in SVG_LENGTHTYPE_MM geändert, valueInSpecifiedUnits würde in den numerischen Wert 5 geändert und valueAsString würde in „5 mm“ geändert. |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und – optional – verwaltete Ressourcen frei. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | Setzt den Wert als Zahl mit einem zugeordneten unitType zurück und ersetzt dadurch die Werte für alle Attribute des Objekts. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svglength/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | Ein Wert wurde mit den in CSS2 definierten cm-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | Ein Wert wurde mit den in CSS2 definierten em-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | Ein Wert wurde mit den in CSS2 definierten Ex-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_IN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | Ein Wert wurde mit den in CSS2 definierten in-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_MM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | Ein Wert wurde mit den in CSS2 definierten mm-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | Es wurde kein Einheitentyp angegeben (dh es wurde ein Wert ohne Einheit angegeben), was auf einen Wert in Benutzereinheiten hinweist. |
| const [SVG_LENGTHTYPE_PC](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | Ein Wert wurde mit den in CSS2 definierten PC-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | Es wurde ein Prozentwert angegeben. |
| const [SVG_LENGTHTYPE_PT](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | Ein Wert wurde mit den in CSS2 definierten pt-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_PX](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | Ein Wert wurde mit den in CSS2 definierten px-Einheiten angegeben. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | Der Einheitentyp ist keiner der vordefinierten Einheitentypen. Es ist ungültig, einen neuen Wert dieses Typs zu definieren oder einen vorhandenen Wert auf diesen Typ umzustellen. |

### Siehe auch

* class [SVGValueType](../svgvaluetype/)
* namensraum [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* Montage [Aspose.HTML](../../)


