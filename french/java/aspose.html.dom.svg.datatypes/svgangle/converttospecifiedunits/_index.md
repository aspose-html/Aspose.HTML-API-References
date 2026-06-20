---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode SVGAngle. Conserve la même valeur sous-jacente stockée mais réinitialise l'identifiant d'unité stocké au unitType donné. Les attributs d'objet unitType, valueInSpecifiedUnits et valueAsString peuvent être modifiés à la suite de cette méthode."
type: docs

url: /fr/java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Conservez la même valeur sous-jacente stockée, mais réinitialisez l'identifiant d'unité stocké sur le unitType donné. Les attributs d'objet unitType, valueInSpecifiedUnits et valueAsString peuvent être modifiés à la suite de cette méthode.

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| unitType | UInt16 | Le type d'unité vers lequel basculer (par ex., SVG_ANGLETYPE_DEG). |

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Levé si unitType est SVG_ANGLETYPE_UNKNOWN ou n'est pas une constante de type d'unité valide (l'une des autres constantes SVG_ANGLETYPE_* définies sur cette interface). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Levé lorsque l'angle correspond à un attribut en lecture seule ou lorsque l'objet lui‑même est en lecture seule. |

### Voir aussi

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
