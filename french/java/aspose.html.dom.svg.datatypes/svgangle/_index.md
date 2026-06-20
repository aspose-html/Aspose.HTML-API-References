---
title: "Classe SVGAngle"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.dom.svg.datatypes.SVGAngle. L’interface SVGAngle correspond au type de données de base angle"
type: docs

url: /fr/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

L'interface SVGAngle correspond au type de données de base angle.

```java
public class SVGAngle : SVGValueType
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) Le type de la valeur tel que spécifié par l’une des constantes SVG_ANGLETYPE_* définies sur cette interface. |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Méthodes

| Nom | Description |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Conservez la même valeur sous-jacente stockée, mais réinitialisez l'identifiant d'unité stocké sur le unitType donné. Les attributs d'objet unitType, valueInSpecifiedUnits et valueAsString peuvent être modifiés à la suite de cette méthode. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Réinitialisez la valeur en tant que nombre avec un unitType associé, remplaçant ainsi les valeurs de tous les attributs de l'objet. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | Le type d'unité a été explicitement défini sur degrés. |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | Le type d'unité est radians. |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | Le type d'unité est radians. |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | Le type d'unité ne fait pas partie des types d'unité prédéfinis. Il est invalide de tenter de définir une nouvelle valeur de ce type ou d'essayer de changer une valeur existante vers ce type. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | Aucun type d'unité n'a été fourni (c.-à-d. une valeur sans unité a été spécifiée). Pour les angles, une valeur sans unité est traitée de la même manière que si des degrés étaient spécifiés. |

### Voir aussi

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
