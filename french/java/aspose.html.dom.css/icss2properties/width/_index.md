---
title: "ICSS2Properties.Width"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété ICSS2Properties. Cette propriété spécifie la largeur du contenu des boîtes générées par des éléments de type bloc et des éléments remplacés."
type: docs

url: /fr/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

Cette propriété spécifie la [largeur du contenu](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) des boîtes générées par des éléments de type bloc et des éléments [remplacés](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element).

Cette propriété ne s'applique pas aux éléments non remplacés de type [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level). La largeur des boîtes d'un élément en ligne non remplacé est celle du contenu rendu à l'intérieur (avant tout décalage relatif des enfants). Rappelez‑vous que les boîtes en ligne s'écoulent dans les [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box). La largeur des boîtes de ligne est donnée par leur [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block), mais peut être réduite par la présence de [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats).

La largeur de la boîte d'un élément remplacé est [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic) et peut être mise à l'échelle par l'agent utilisateur si la valeur de cette propriété est différente de 'auto'.

Les valeurs ont les significations suivantes :

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Spécifie une largeur fixe.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Spécifie une largeur en pourcentage. Le pourcentage est calculé par rapport à la largeur du [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) de la boîte générée. auto - La largeur dépend des valeurs des autres propriétés. Voir les sections ci‑dessous. Note : les valeurs négatives pour ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) sont illégales.

```java
public String Width { get; set; }
```

### Valeur de retour

propriété width

### Voir aussi

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
