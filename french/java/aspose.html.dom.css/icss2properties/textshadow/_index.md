---
title: "ICSS2Properties.TextShadow"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété ICSS2Properties. Cette propriété accepte une liste d'effets d'ombre séparés par des virgules à appliquer au texte de l'élément. Les effets d'ombre sont appliqués dans l'ordre spécifié et peuvent ainsi se superposer les uns aux autres, mais ils ne recouvriront jamais le texte lui‑même. Les effets d'ombre n'altèrent pas la taille d'une boîte mais peuvent dépasser ses limites. Le niveau d'empilement des effets d'ombre est le même que celui de l'élément lui‑même."
type: docs

url: /fr/java/com.aspose.html.dom.css/icss2properties/textshadow/
---
## ICSS2Properties.TextShadow property

Cette propriété accepte une liste d'effets d'ombre séparés par des virgules à appliquer au texte de l'élément. Les effets d'ombre sont appliqués dans l'ordre spécifié et peuvent ainsi se superposer, mais ils ne recouvriront jamais le texte lui‑même. Les effets d'ombre n'altèrent pas la taille d'une boîte, mais peuvent dépasser ses limites. Le [niveau d'empilement](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#stack-level) des effets d'ombre est le même que celui de l'élément lui‑même.

Chaque effet d'ombre doit spécifier un décalage d'ombre et peut éventuellement spécifier un rayon de flou ainsi qu'une couleur d'ombre.

Un décalage d'ombre est spécifié avec deux valeurs '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' qui indiquent la distance par rapport au texte. La première valeur de longueur indique la distance horizontale à droite du texte. Une valeur de longueur horizontale négative place l'ombre à gauche du texte. La deuxième valeur de longueur indique la distance verticale sous le texte. Une valeur de longueur verticale négative place l'ombre au-dessus du texte.

Un rayon de flou peut éventuellement être spécifié après le décalage d'ombre. Le rayon de flou est une valeur de longueur qui indique les limites de l'effet de flou. L'algorithme exact de calcul de l'effet de flou n'est pas spécifié.

Une valeur de couleur peut éventuellement être spécifiée avant ou après les valeurs de longueur de l'effet d'ombre. La valeur de couleur sera utilisée comme base pour l'effet d'ombre. Si aucune couleur n'est spécifiée, la valeur de la propriété ['color'](https://www.w3.org/TR/1998/REC-CSS2-19980512/colors.html#propdef-color) sera utilisée à la place.

```java
public String TextShadow { get; set; }
```

### Valeur de retour

propriété text-shadow

### Voir aussi

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
