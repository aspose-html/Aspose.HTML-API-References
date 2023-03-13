---
title: SVGAngle.NewValueSpecifiedUnits
second_title: Aspose.HTML für .NET-API-Referenz
description: SVGAngle methode. Setzt den Wert als Zahl mit einem zugeordneten unitType zurück und ersetzt dadurch die Werte für alle Attribute des Objekts.
type: docs
weight: 60
url: /de/net/aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Setzt den Wert als Zahl mit einem zugeordneten unitType zurück und ersetzt dadurch die Werte für alle Attribute des Objekts.

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newUnitType | UInt16 | Der Einheitentyp für den Wert (z. B. SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Der Winkelwert. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | -Code[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Wird ausgelöst, wenn unitType SVG_ANGLETYPE_UNKNOWN oder keine gültige Einheitstypkonstante ist (eine der anderen SVG_ANGLETYPE_*-Konstanten, die auf dieser Schnittstelle definiert sind). |
| [DOMException](../../../aspose.html.dom/domexception/) | -Code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Wird ausgelöst, wenn der Winkel einem schreibgeschützten Attribut entspricht oder wenn das Objekt selbst schreibgeschützt ist. |

### Siehe auch

* class [SVGAngle](../)
* namensraum [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* Montage [Aspose.HTML](../../../)


