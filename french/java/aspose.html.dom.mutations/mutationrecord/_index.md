---
title: "Classe MutationRecord"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.dom.mutations.MutationRecord class. Un MutationRecord représente une mutation DOM individuelle. C'est l'objet qui est transmis au MutationCallback des MutationObservers."
type: docs

url: /fr/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

Un MutationRecord représente une mutation DOM individuelle. C'est l'objet qui est transmis au [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/).

```java
public class MutationRecord : DOMObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) Retourne les nœuds ajoutés. |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) Retourne le nom local de l'attribut modifié, ou null sinon. |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) Retourne l'espace de noms de l'attribut modifié, ou null sinon. |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) Retourne le frère suivant des nœuds ajoutés ou supprimés, ou null. |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) La valeur de retour dépend du type. Pour "attributes", c'est la valeur de l'attribut modifié avant le changement. Pour "characterData", ce sont les données du nœud modifié avant le changement. Pour "childList", c'est null. |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) Retourne le frère précédent des nœuds ajoutés ou supprimés, ou null. |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) Retourne les nœuds supprimés. |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) Retourne le nœud affecté par la mutation, selon le type. Pour "attributes", c'est l'élément dont l'attribut a changé. Pour "characterData", c'est le nœud CharacterData. Pour "childList", c'est le nœud dont les enfants ont changé. |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) Retourne "attributes" si c'était une mutation d'attribut, "characterData" si c'était une mutation d'un nœud CharacterData et "childList" si c'était une mutation de l'arborescence des nœuds. |

## Méthodes

| Nom | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |

### Voir aussi

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
