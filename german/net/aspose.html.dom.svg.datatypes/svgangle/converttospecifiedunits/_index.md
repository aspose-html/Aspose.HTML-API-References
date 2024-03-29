---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: Aspose.HTML für .NET-API-Referenz
description: SVGAngle methode. Den gleichen zugrunde liegenden gespeicherten Wert beibehalten aber die gespeicherte Einheitenkennung auf den angegebenen unitType zurücksetzen. Die Objektattribute unitType valueInSpecifiedUnits und valueAsString können als Ergebnis dieser Methode geändert werden.
type: docs
weight: 50
url: /de/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Den gleichen zugrunde liegenden gespeicherten Wert beibehalten, aber die gespeicherte Einheitenkennung auf den angegebenen unitType zurücksetzen. Die Objektattribute unitType, valueInSpecifiedUnits und valueAsString können als Ergebnis dieser Methode geändert werden.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| unitType | UInt16 | Der Einheitentyp, zu dem gewechselt werden soll (z. B. SVG_ANGLETYPE_DEG). |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | -Code[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Wird ausgelöst, wenn unitType SVG_ANGLETYPE_UNKNOWN oder keine gültige Einheitstypkonstante ist (eine der anderen SVG_ANGLETYPE_*-Konstanten, die auf dieser Schnittstelle definiert sind). |
| [DOMException](../../../aspose.html.dom/domexception/) | -Code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Wird ausgelöst, wenn der Winkel einem schreibgeschützten Attribut entspricht oder wenn das Objekt selbst schreibgeschützt ist. |

### Siehe auch

* class [SVGAngle](../)
* namensraum [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* Montage [Aspose.HTML](../../../)


