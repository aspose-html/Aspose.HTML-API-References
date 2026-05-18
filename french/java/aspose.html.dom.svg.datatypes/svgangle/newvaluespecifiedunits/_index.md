---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode SVGAngle. Réinitialise la valeur en tant que nombre avec un unitType associé, remplaçant ainsi les valeurs de tous les attributs de l'objet"
type: docs

url: /fr/java/com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Réinitialisez la valeur en tant que nombre avec un unitType associé, remplaçant ainsi les valeurs de tous les attributs de l'objet.

```java
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| newUnitType | UInt16 | Le type d'unité pour la valeur (par ex., SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | La valeur de l'angle. |

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Levé si unitType est SVG_ANGLETYPE_UNKNOWN ou n'est pas une constante de type d'unité valide (l'une des autres constantes SVG_ANGLETYPE_* définies sur cette interface). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Levé lorsque l'angle correspond à un attribut en lecture seule ou lorsque l'objet lui‑même est en lecture seule. |

### Voir aussi

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
