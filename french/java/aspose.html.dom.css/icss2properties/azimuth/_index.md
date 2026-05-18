---
title: "ICSS2Properties.Azimuth"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété ICSS2Properties. L'audio spatial est une propriété stylistique importante pour la présentation auditive. Il offre un moyen naturel de distinguer plusieurs voix, comme dans la vie réelle les gens se tiennent rarement tous au même endroit dans une pièce."
type: docs

url: /fr/java/com.aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

L'audio spatial est une propriété stylistique importante pour la présentation auditive. Il offre un moyen naturel de distinguer plusieurs voix, comme dans la vie réelle (les gens se tiennent rarement tous au même endroit dans une pièce).

```java
public String Azimuth { get; set; }
```

### Valeur de retour

La propriété azimuth

### Property Value

Les valeurs ont les significations suivantes :

angle - La position est décrite en fonction d'un angle compris entre '-360deg' et '360deg'. La valeur '0deg' signifie directement devant, au centre de la scène sonore. '90deg' est à droite, '180deg' derrière, et '270deg' (ou, de façon équivalente et plus pratique, '-90deg') à gauche.

côté-gauche - Identique à '270deg'. Avec 'behind', '270deg'.

extrême-gauche - Identique à '300deg'. Avec 'behind', '240deg'.

gauche - Identique à '320deg'. Avec 'behind', '220deg'.

centre-gauche - Identique à '340deg'. Avec 'behind', '200deg'.

centre - Identique à '0deg'. Avec 'behind', '180deg'.

centre-droit - Identique à '20deg'. Avec 'behind', '160deg'.

droite - Identique à '40deg'. Avec 'behind', '140deg'.

extrême-droite - Identique à '60deg'. Avec 'behind', '120deg'.

côté-droit - Identique à '90deg'. Avec 'behind', '90deg'.

leftwards - Déplace le son vers la gauche, par rapport à l'angle actuel. Plus précisément, soustrait 20 degrés. Les calculs sont effectués modulo 360 degrés. Notez que 'leftwards' est plus précisément décrit comme « tourné dans le sens antihoraire », car il soustrait toujours 20 degrés, même si l'azimut hérité est déjà derrière l'auditeur (dans ce cas le son semble en fait se déplacer vers la droite).

rightwards - Déplace le son vers la droite, par rapport à l'angle actuel. Plus précisément, ajoute 20 degrés. Voir 'leftwards' pour les calculs.

### Voir aussi

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
