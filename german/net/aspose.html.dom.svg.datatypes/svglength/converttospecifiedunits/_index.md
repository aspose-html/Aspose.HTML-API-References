---
title: SVGLength.ConvertToSpecifiedUnits
second_title: Aspose.HTML für .NET-API-Referenz
description: SVGLength methode. Den gleichen zugrunde liegenden gespeicherten Wert beibehalten aber die gespeicherte Einheitenkennung auf den angegebenen unitType zurücksetzen. Die Objektattribute unitType valueInSpecifiedUnits und valueAsString können als Ergebnis dieser Methode geändert werden. Wenn der ursprüngliche Wert beispielsweise 05 cm war und die Methode aufgerufen wurde um ihn in Millimeter umzuwandeln würde der unitType in SVG_LENGTHTYPE_MM geändert valueInSpecifiedUnits würde in den numerischen Wert 5 geändert und valueAsString würde in 5 mm geändert.
type: docs
weight: 50
url: /de/net/aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Den gleichen zugrunde liegenden gespeicherten Wert beibehalten, aber die gespeicherte Einheitenkennung auf den angegebenen unitType zurücksetzen. Die Objektattribute unitType, valueInSpecifiedUnits und valueAsString können als Ergebnis dieser Methode geändert werden. Wenn der ursprüngliche Wert beispielsweise „0,5 cm“ war und die Methode aufgerufen wurde, um ihn in Millimeter umzuwandeln, würde der unitType in SVG_LENGTHTYPE_MM geändert, valueInSpecifiedUnits würde in den numerischen Wert 5 geändert und valueAsString würde in „5 mm“ geändert.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| unitType | UInt16 | Der Einheitentyp, zu dem gewechselt werden soll (z. B. SVG_LENGTHTYPE_MM). |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | -Code[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Wird ausgelöst, wenn unitType SVG_LENGTHTYPE_UNKNOWN oder keine gültige Einheitstypkonstante ist (eine der anderen SVG_LENGTHTYPE_*-Konstanten, die auf dieser Schnittstelle definiert sind). |
| [DOMException](../../../aspose.html.dom/domexception/) | -Code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Wird ausgelöst, wenn die Länge einem schreibgeschützten Attribut entspricht oder wenn das Objekt selbst schreibgeschützt ist. |

### Siehe auch

* class [SVGLength](../)
* namensraum [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* Montage [Aspose.HTML](../../../)


