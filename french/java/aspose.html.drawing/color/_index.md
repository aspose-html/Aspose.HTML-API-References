---
title: "Classe Color"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.drawing.Color classe. La classe Color vous permet de spécifier des couleurs sous forme de valeurs Rouge-Vert-Bleu RGB, valeurs Teinte-Saturation-Luminosité HSL, valeurs Teinte-Saturation-Valeur HSV, valeurs Teinte-Blancheur-Noirceur HWB, valeurs clarté-A-B LAB, valeurs Luminance-Chroma-Teinte LCH, valeurs Cyan-Magenta-Jaune-Noir CMYK, valeurs Couleurs naturelles NCOL ou avec un nom de couleur. Un canal Alpha est également disponible pour indiquer la transparence"
type: docs

url: /fr/java/com.aspose.html.drawing/color/
---
## Color class

La classe Color vous permet de spécifier les couleurs sous forme de valeurs Rouge-Vert-Bleu (RGB), de valeurs Teinte-Saturation-Luminosité (HSL), de valeurs Teinte-Saturation-Valeur (HSV), de valeurs Teinte-Blancheur-Noirceur (HWB), de valeurs clarté-A-B (LAB), de valeurs Luminance-Chroma-Teinte (LCH), de valeurs Cyan-Magenta-Jaune-Clé (CMYK), de valeurs Couleurs naturelles (NCOL), ou avec un nom de couleur. Un canal Alpha est également disponible pour indiquer la transparence.

```java
public class Color
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Color](color/#constructor)() | Initialise une nouvelle instance de la classe `Color`. Par défaut, la couleur est noire. |
| [Color](color/#constructor_1)(byte, byte, byte) | Initialise une nouvelle instance de la classe `Color`. Tous les composants de couleur doivent être compris entre 0 et 255. |
| [Color](color/#constructor_5)(float, float, float) | Initialise une nouvelle instance de la classe `Color`. Tous les composants de couleur doivent être compris entre 0 et 1. |
| [Color](color/#constructor_3)(int, int, int) | Initialise une nouvelle instance de la classe `Color`. Tous les composants de couleur doivent être compris entre 0 et 255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Initialise une nouvelle instance de la classe `Color`. Tous les composants de couleur doivent être compris entre 0 et 255. |
| [Color](color/#constructor_6)(float, float, float, float) | Initialise une nouvelle instance de la classe `Color`. Tous les composants de couleur doivent être compris entre 0 et 1. |
| [Color](color/#constructor_4)(int, int, int, int) | Initialise une nouvelle instance de la classe `Color`. Tous les composants de couleur doivent être compris entre 0 et 255. |

## Propriétés

| Nom | Description |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) Représente le composant alpha de la couleur. |
| [getBlue](../../com.aspose.html.drawing/color/blue/) Représente le composant bleu de la couleur. |
| [getGreen](../../com.aspose.html.drawing/color/green/) Représente le composant vert de la couleur. |
| [getRed](../../com.aspose.html.drawing/color/red/) Représente le composant rouge de la couleur |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Retourne un nouveau Color avec les valeurs cyan, magenta, jaune, clé (noir) demandées. |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Retourne un nouveau Color avec les valeurs cyan, magenta, jaune, clé (noir), alpha demandées. |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | Retourne un nouveau Color avec la valeur de gris demandée. |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | Retourne un nouveau Color avec les valeurs de teinte, saturation, saturation demandées. |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Retourne un nouveau Color avec les valeurs de teinte, saturation, saturation, alpha demandées. |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | Retourne un nouveau Color avec les valeurs de teinte, saturation, valeur demandées. |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Retourne un nouveau Color avec les valeurs de teinte, saturation, valeur, alpha demandées. |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | Retourne un nouveau Color avec les valeurs de teinte, blancheur, noirceur demandées. |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Retourne un nouveau Color avec les valeurs de teinte, blancheur, noirceur demandées. |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | Retourne un nouveau Color avec la valeur ARGB demandée. |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | Retourne un nouveau Color avec les valeurs de clarté, A, B demandées. |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Renvoie un nouveau Color avec les valeurs de clarté, A, B et alpha demandées. |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | Renvoie un nouveau Color avec les valeurs de luminance, chroma et teinte demandées. |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Renvoie un nouveau Color avec les valeurs de luminance, chroma, teinte et alpha demandées. |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | Renvoie un nouveau Color avec les valeurs de clarté, A et B demandées pour le modèle OKLAB. |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Renvoie un nouveau Color avec les valeurs de clarté, A, B et alpha demandées pour le modèle OKLAB. |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | Renvoie un nouveau Color avec les valeurs de luminance, chroma et teinte demandées pour le modèle OKLAB. |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Renvoie un nouveau Color avec les valeurs de luminance, chroma, teinte et alpha demandées pour le modèle OKLAB. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Renvoie un nouveau Color avec les valeurs de ged, vert et bleu demandées. Tous les composants de couleur doivent être compris entre 0 et 255. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Renvoie un nouveau Color avec les valeurs de ged, vert et bleu demandées. Tous les composants de couleur doivent être compris entre 0 et 1. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Renvoie un nouveau Color avec les valeurs de ged, vert et bleu demandées. Tous les composants de couleur doivent être compris entre 0 et 255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Renvoie un nouveau Color avec les valeurs de ged, vert, bleu et alpha demandées. Tous les composants de couleur doivent être compris entre 0 et 255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Renvoie un nouveau Color avec les valeurs de ged, vert, bleu et alpha demandées. Tous les composants de couleur doivent être compris entre 0 et 1. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Renvoie un nouveau Color avec les valeurs de ged, vert, bleu et alpha demandées. Tous les composants de couleur doivent être compris entre 0 et 255. |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | Analyse la String contenant la couleur CSS et renvoie un nouveau Color. |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | Retourne un nouveau Color avec la valeur ARGB demandée. |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | Crée une copie du Color avec la somme de sa luminosité et de la valeur delta. |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | Renvoie les composants de couleur au format du modèle de couleur spécifié. |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | Détermine si le `Color` spécifié est égal à cette instance. |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | Renvoie une nouvelle couleur qui se trouve du côté opposé de la roue des couleurs par rapport à l'original. |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | Renvoie un code de hachage. |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | Renvoie la teinte du Color. |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | Renvoie la luminosité du Color. |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | Renvoie la saturation du Color. |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | Encode les composants ARGB du Color en int. |
| [toName](../../com.aspose.html.drawing/color/toname/)() | Renvoie le nom de la couleur si elle correspond à une couleur de la liste des couleurs nommées CSS, ou une String vide. |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | Renvoie une couleur naturelle (NCol) spécifiée en utilisant une lettre de couleur avec un nombre pour indiquer la distance (en pourcentage) par rapport à la couleur. |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | Renvoie une couleur hexadécimale spécifiée par : #RRGGBBAA. |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | Renvoie une String contenant la couleur RGBA spécifiée par : rgba(R, G, B, A). |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | Renvoie une couleur hexadécimale spécifiée avec : #RRGGBB. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | Renvoie une chaîne contenant la couleur RVB spécifiée par : rgb(R, G, B). |
| [toString](../../com.aspose.html.drawing/color/toString/)() | Renvoie une chaîne qui consiste des valeurs des composants RGBA. |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | Encode les composants ARGB de la couleur en entier non signé. |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | Crée une copie de la couleur avec le composant alpha spécifié. |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | Crée une copie de la couleur avec la teinte spécifiée. |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | Crée une copie de la couleur avec la luminosité spécifiée. |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | Crée une copie de la couleur avec la saturation spécifiée. |

### Voir aussi

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
