---
title: Class SVGLength
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Svg.DataTypes.SVGLength classe. Linterface SVGLength correspond au type de données de base de longueur. Un objet SVGLength peut être désigné comme étant en lecture seule ce qui signifie que les tentatives de modification de lobjet entraîneront la levée dune exception comme décrit cidessous.
type: docs
weight: 1200
url: /fr/net/aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

L'interface SVGLength correspond au type de données de base de longueur. Un objet SVGLength peut être désigné comme étant en lecture seule, ce qui signifie que les tentatives de modification de l'objet entraîneront la levée d'une exception, comme décrit ci-dessous.

```csharp
public class SVGLength : SVGValueType
```

## Propriétés

| Nom | La description |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svglength/unittype/) { get; } | Le type de la valeur tel que spécifié par l'une des constantes SVG_LENGTHTYPE_* définies sur cette interface. |
| [Value](../../aspose.html.dom.svg.datatypes/svglength/value/) { get; set; } | La valeur sous forme de valeur à virgule flottante, en unités utilisateur. La définition de cet attribut entraînera la mise à jour automatique de valueInSpecifiedUnits et valueAsString pour refléter ce paramètre. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svglength/valueasstring/) { get; set; } | La valeur sous forme de chaîne, dans les unités exprimées par unitType. La définition de cet attribut entraînera la mise à jour automatique de value, valueInSpecifiedUnits et unitType pour refléter ce paramètre. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | La valeur sous forme de valeur à virgule flottante, dans les unités exprimées par unitType. La définition de cet attribut entraînera la mise à jour automatique de value et valueAsString pour refléter ce paramètre. |

## Méthodes

| Nom | La description |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Préserve la même valeur stockée sous-jacente, mais réinitialise l'identifiant d'unité stocké sur le type d'unité donné. Les attributs d'objet unitType, valueInSpecifiedUnits et valueAsString peuvent être modifiés suite à cette méthode. Par exemple, si la valeur d'origine était "0,5 cm" et que la méthode était invoquée pour convertir en millimètres, alors le type d'unité serait changé en SVG_LENGTHTYPE_MM, valueInSpecifiedUnits serait changé en la valeur numérique 5 et valueAsString serait changé en "5mm". |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | Réinitialisez la valeur sous forme de nombre avec un type d'unité associé, remplaçant ainsi les valeurs de tous les attributs de l'objet. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svglength/tostring/)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | Une valeur a été spécifiée en utilisant les unités cm définies dans CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | Une valeur a été spécifiée en utilisant les unités em définies dans CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | Une valeur a été spécifiée en utilisant les unités ex définies dans CSS2. |
| const [SVG_LENGTHTYPE_IN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | Une valeur a été spécifiée en utilisant les unités définies dans CSS2. |
| const [SVG_LENGTHTYPE_MM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | Une valeur a été spécifiée en utilisant les unités mm définies dans CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | Aucun type d'unité n'a été fourni (c'est-à-dire qu'une valeur sans unité a été spécifiée), ce qui indique une valeur en unités utilisateur. |
| const [SVG_LENGTHTYPE_PC](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | Une valeur a été spécifiée en utilisant les unités pc définies dans CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | Une valeur en pourcentage a été spécifiée. |
| const [SVG_LENGTHTYPE_PT](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | Une valeur a été spécifiée en utilisant les unités pt définies dans CSS2. |
| const [SVG_LENGTHTYPE_PX](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | Une valeur a été spécifiée en utilisant les unités px définies dans CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | Le type d'unité ne fait pas partie des types d'unité prédéfinis. Il n'est pas valide de tenter de définir une nouvelle valeur de ce type ou de tenter de basculer une valeur existante vers ce type. |

### Voir également

* class [SVGValueType](../svgvaluetype/)
* espace de noms [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* Assemblée [Aspose.HTML](../../)


