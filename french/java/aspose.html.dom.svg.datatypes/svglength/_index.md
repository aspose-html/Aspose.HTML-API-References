---
title: "SVGLength Classe"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.dom.svg.datatypes.SVGLength classe. L'interface SVGLength correspond au type de données de base longueur. Un objet SVGLength peut être désigné en lecture seule, ce qui signifie que les tentatives de modification de l'objet entraîneront le lancement d'une exception comme décrit ci-dessous."
type: docs

url: /fr/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

L'interface SVGLength correspond au type de données de base length. Un objet SVGLength peut être désigné comme lecture seule, ce qui signifie que toute tentative de modification de l'objet entraînera le lancement d'une exception, comme décrit ci-dessous.

```java
public class SVGLength : SVGValueType
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) Le type de la valeur tel que spécifié par l'une des constantes SVG_LENGTHTYPE_* définies sur cette interface. |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Méthodes

| Nom | Description |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Conservez la même valeur sous-jacente stockée, mais réinitialisez l'identifiant d'unité stocké au unitType donné. Les attributs d'objet unitType, valueInSpecifiedUnits et valueAsString peuvent être modifiés à la suite de cette méthode. Par exemple, si la valeur originale était "0.5cm" et que la méthode était invoquée pour convertir en millimètres, alors unitType serait changé en SVG_LENGTHTYPE_MM, valueInSpecifiedUnits serait changé en la valeur numérique 5 et valueAsString serait changé en "5mm". |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | Réinitialisez la valeur en tant que nombre avec un unitType associé, remplaçant ainsi les valeurs de tous les attributs de l'objet. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | Une valeur a été spécifiée en utilisant les unités cm définies dans CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | Une valeur a été spécifiée en utilisant les unités em définies dans CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | Une valeur a été spécifiée en utilisant les unités ex définies dans CSS2. |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | Une valeur a été spécifiée en utilisant les unités in définies dans CSS2. |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | Une valeur a été spécifiée en utilisant les unités mm définies dans CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | Aucun type d'unité n'a été fourni (c'est-à-dire qu'une valeur sans unité a été spécifiée), ce qui indique une valeur en unités utilisateur. |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | Une valeur a été spécifiée en utilisant les unités pc définies dans CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | Une valeur en pourcentage a été spécifiée. |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | Une valeur a été spécifiée en utilisant les unités pt définies dans CSS2. |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | Une valeur a été spécifiée en utilisant les unités px définies dans CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | Le type d'unité ne fait pas partie des types d'unité prédéfinis. Il est invalide de tenter de définir une nouvelle valeur de ce type ou d'essayer de changer une valeur existante vers ce type. |

### Voir aussi

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
