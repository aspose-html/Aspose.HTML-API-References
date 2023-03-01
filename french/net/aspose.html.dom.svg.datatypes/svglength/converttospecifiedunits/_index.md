---
title: SVGLength.ConvertToSpecifiedUnits
second_title: Référence de l'API Aspose.HTML pour .NET
description: SVGLength méthode. Préserve la même valeur stockée sousjacente mais réinitialise lidentifiant dunité stocké sur le type dunité donné. Les attributs dobjet unitType valueInSpecifiedUnits et valueAsString peuvent être modifiés suite à cette méthode. Par exemple si la valeur dorigine était 05 cm et que la méthode était invoquée pour convertir en millimètres alors le type dunité serait changé en SVG_LENGTHTYPE_MM valueInSpecifiedUnits serait changé en la valeur numérique 5 et valueAsString serait changé en 5mm.
type: docs
weight: 50
url: /fr/net/aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Préserve la même valeur stockée sous-jacente, mais réinitialise l'identifiant d'unité stocké sur le type d'unité donné. Les attributs d'objet unitType, valueInSpecifiedUnits et valueAsString peuvent être modifiés suite à cette méthode. Par exemple, si la valeur d'origine était "0,5 cm" et que la méthode était invoquée pour convertir en millimètres, alors le type d'unité serait changé en SVG_LENGTHTYPE_MM, valueInSpecifiedUnits serait changé en la valeur numérique 5 et valueAsString serait changé en "5mm".

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| unitType | UInt16 | Le type d'unité vers lequel basculer (par exemple, SVG_LENGTHTYPE_MM). |

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Levé si unitType est SVG_LENGTHTYPE_UNKNOWN ou n'est pas une constante de type d'unité valide (l'une des autres constantes SVG_LENGTHTYPE_* définies sur cette interface). |
| [DOMException](../../../aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Levé lorsque la longueur correspond à un attribut en lecture seule ou lorsque l'objet lui-même est en lecture seule. |

### Voir également

* class [SVGLength](../)
* espace de noms [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* Assemblée [Aspose.HTML](../../../)


