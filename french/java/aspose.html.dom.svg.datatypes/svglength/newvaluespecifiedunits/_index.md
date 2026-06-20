---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode SVGLength. Réinitialise la valeur en tant que nombre avec un unitType associé, remplaçant ainsi les valeurs de tous les attributs de l'objet"
type: docs

url: /fr/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Réinitialisez la valeur en tant que nombre avec un unitType associé, remplaçant ainsi les valeurs de tous les attributs de l'objet.

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| unitType | UInt16 | Le type d'unité pour la valeur. |
| valueInSpecifiedUnits | Single | La nouvelle valeur.. |

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Levé si unitType est SVG_LENGTHTYPE_UNKNOWN ou n'est pas une constante de type d'unité valide (l'une des autres constantes SVG_LENGTHTYPE_* définies sur cette interface). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Levé lorsque la longueur correspond à un attribut en lecture seule ou lorsque l'objet lui‑même est en lecture seule. |

### Voir aussi

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
