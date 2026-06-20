---
title: "Node.Normalize"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Node method. Place tous les nœuds Text à toutes les profondeurs du sous‑arbre sous ce Node, y compris les nœuds d'attribut, dans une forme normale où seule la structure (par ex. éléments, commentaires, instructions de traitement, sections CDATA et références d'entité) sépare les nœuds Text, c’est‑à‑dire qu’il n’y a ni nœuds Text adjacents ni nœuds Text vides. Cela peut être utilisé pour garantir que la vue DOM d’un document est identique à celle d’un document enregistré puis rechargé et est utile lorsque des opérations telles que les recherches XPointer qui dépendent d’une structure d’arbre de document particulière doivent être utilisées. Si le paramètre normalize-characters de l’objet DOMConfiguration attaché à Node.ownerDocument est vrai, cette méthode normalisera également complètement les caractères des nœuds Text."
type: docs

url: /fr/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

Place tous les [`Text`](../../text/) nœuds à toutes les profondeurs du sous‑arbre sous ce Node, y compris les nœuds d'attribut, dans une forme « normale » où seule la structure (par ex. [`elements`](../../element/), [`comments`](../../comment/), [`processing instructions`](../../processinginstruction/), [`CDATA sections`](../../cdatasection/), et [`entity references`](../../entityreference/)) sépare les [`Text`](../../text/) nœuds, c’est‑à‑dire qu’il n’y a ni nœuds Text adjacents ni nœuds Text vides. Cela peut être utilisé pour garantir que la vue DOM d’un document est identique à celle d’un document enregistré puis rechargé, et est utile lorsque des opérations (telles que les recherches XPointer [XPointer]) qui dépendent d’une structure d’arbre de document particulière doivent être utilisées. Si le paramètre « normalize-characters » de l’objet [`DOMConfiguration`](../../../com.aspose.html/configuration/) attaché à [`Node.ownerDocument`](../ownerdocument/) est vrai, cette méthode normalisera également complètement les caractères des nœuds Text.

```java
public void Normalize()
```

### Voir aussi

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
