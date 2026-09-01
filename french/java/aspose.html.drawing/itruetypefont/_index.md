---
title: "Interface ITrueTypeFont"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.drawing.ITrueTypeFont. Déclare les méthodes pour travailler avec la police TrueType"
type: docs

url: /fr/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Déclare des méthodes pour travailler avec la police TrueType.

```java
public interface ITrueTypeFont
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) Renvoie la taille des données de la police en octets |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) Obtient le nom de la famille de police. |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) Cela doit être une combinaison de "FamilyName" et "SubFamilyName". Exception : si la police est "Regular" comme indiqué dans "SubFamilyName", alors n'utilisez que le nom de famille contenu dans "FamilyName". Une exception à la définition ci‑dessus du nom complet de la police concerne les chaînes de la plateforme Microsoft pour les polices CFF OpenType : dans ce cas, la chaîne du nom complet de la police doit être identique au PostScript FontName dans le CFF Name INDEX. |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) Le nom de sous‑famille de la police distingue la police dans un groupe portant le même nom de famille de police. Cela est censé couvrir le style (italique, oblique) et le poids (léger, gras, noir, etc.). Une police sans différences particulières de poids ou de style (p. ex. poids moyen, pas italique et bit fsSelection 6 activé) doit avoir la chaîne "Regular" stockée à cet emplacement. |

## Méthodes

| Nom | Description |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | Renvoie l'ascension, en points. |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | Ouvrez le flux contenant les données de la police. L'appelant est responsable de la libération du flux. |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | Renvoie la descente, en points. |

### Voir aussi

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
