---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode SVGLength. Conserve la même valeur sous-jacente stockée mais réinitialise l'identifiant d'unité stocké au unitType fourni. Les attributs d'objet unitType, valueInSpecifiedUnits et valueAsString peuvent être modifiés à la suite de cette méthode. Par exemple, si la valeur originale était 0,5 cm et que la méthode était invoquée pour convertir en millimètres, alors unitType serait changé en SVG_LENGTHTYPE_MM, valueInSpecifiedUnits serait changé en la valeur numérique 5 et valueAsString serait changé en 5mm."
type: docs

url: /fr/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Conservez la même valeur sous-jacente stockée, mais réinitialisez l'identifiant d'unité stocké au unitType donné. Les attributs d'objet unitType, valueInSpecifiedUnits et valueAsString peuvent être modifiés à la suite de cette méthode. Par exemple, si la valeur originale était "0.5cm" et que la méthode était invoquée pour convertir en millimètres, alors unitType serait changé en SVG_LENGTHTYPE_MM, valueInSpecifiedUnits serait changé en la valeur numérique 5 et valueAsString serait changé en "5mm".

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| unitType | UInt16 | Le type d'unité vers lequel basculer (par ex., SVG_LENGTHTYPE_MM). |

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Levé si unitType est SVG_LENGTHTYPE_UNKNOWN ou n'est pas une constante de type d'unité valide (l'une des autres constantes SVG_LENGTHTYPE_* définies sur cette interface). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Levé lorsque la longueur correspond à un attribut en lecture seule ou lorsque l'objet lui‑même est en lecture seule. |

### Voir aussi

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
