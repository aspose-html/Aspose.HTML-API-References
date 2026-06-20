---
title: "Classe RGBColor"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.dom.css.RGBColor. L'interface RGBColor est utilisée pour représenter toute valeur de couleur RVB. Cette interface reflète les valeurs dans la propriété de style sous-jacente. Ainsi, les modifications apportées aux objets CSSPrimitiveValue modifient la propriété de style."
type: docs

url: /fr/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

L'interface RGBColor est utilisée pour représenter toute valeur de couleur RVB. Cette interface reflète les valeurs de la propriété de style sous-jacente. Ainsi, les modifications apportées aux objets CSSPrimitiveValue modifient la propriété de style.

Une couleur RVB spécifiée n'est pas tronquée (même si le nombre est hors de la plage 0-255 ou 0%-100%). Une couleur RVB calculée est tronquée en fonction de l'appareil.

Même si une feuille de style ne peut contenir qu'un entier pour une valeur de couleur, le stockage interne de cet entier est un flottant, et celui‑ci peut être utilisé comme flottant dans le style spécifié ou calculé.

Une valeur de couleur exprimée en pourcentage peut toujours être convertie en nombre et vice‑versa.

```java
public class RGBColor : DOMObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) Obtient la valeur du composant alpha de cette structure Color. |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) Obtient la valeur du composant bleu de cette structure Color. |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) Obtient la valeur du composant vert de cette structure Color. |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) Obtient la valeur du composant rouge de cette structure Color. |

## Méthodes

| Nom | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | Convertit en l'objet couleur natif. |

## Remarques

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Référence

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Voir aussi

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
