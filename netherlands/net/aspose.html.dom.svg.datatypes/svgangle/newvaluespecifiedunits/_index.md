---
title: SVGAngle.NewValueSpecifiedUnits
second_title: Aspose.HTML voor .NET API-referentie
description: SVGAngle methode. Reset de waarde als een getal met een geassocieerd unitType waarbij de waarden voor alle kenmerken van het object worden vervangen.
type: docs
weight: 60
url: /nl/net/aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Reset de waarde als een getal met een geassocieerd unitType, waarbij de waarden voor alle kenmerken van het object worden vervangen.

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newUnitType | UInt16 | Het eenheidstype voor de waarde (bijv. SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | De hoekwaarde. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | -code[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Wordt verhoogd als unitType SVG_ANGLETYPE_UNKNOWN is of geen geldige eenheidstypeconstante is (een van de andere SVG_ANGLETYPE_*-constanten die op deze interface zijn gedefinieerd). |
| [DOMException](../../../aspose.html.dom/domexception/) | -code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Verhoogd wanneer de hoek overeenkomt met een alleen-lezen kenmerk of wanneer het object zelf alleen-lezen is. |

### Zie ook

* class [SVGAngle](../)
* naamruimte [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* montage [Aspose.HTML](../../../)


