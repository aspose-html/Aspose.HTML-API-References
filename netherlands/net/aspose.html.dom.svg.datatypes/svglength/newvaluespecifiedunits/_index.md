---
title: SVGLength.NewValueSpecifiedUnits
second_title: Aspose.HTML voor .NET API-referentie
description: SVGLength methode. Reset de waarde als een getal met een geassocieerd unitType waarbij de waarden voor alle kenmerken van het object worden vervangen.
type: docs
weight: 60
url: /nl/net/aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Reset de waarde als een getal met een geassocieerd unitType, waarbij de waarden voor alle kenmerken van het object worden vervangen.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| unitType | UInt16 | Het eenheidstype voor de waarde. |
| valueInSpecifiedUnits | Single | De nieuwe waarde.. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | -code[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Wordt verhoogd als unitType SVG_LENGTHTYPE_UNKNOWN is of geen geldige eenheidstypeconstante is (een van de andere SVG_LENGTHTYPE_*-constanten die op deze interface zijn gedefinieerd). |
| [DOMException](../../../aspose.html.dom/domexception/) | -code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Verhoogd wanneer de lengte overeenkomt met een alleen-lezen kenmerk of wanneer het object zelf alleen-lezen is. |

### Zie ook

* class [SVGLength](../)
* naamruimte [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* montage [Aspose.HTML](../../../)


