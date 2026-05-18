---
title: "Interface ITraversal"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Interface com.aspose.html.dom.traversal.ITraversal. Les itérateurs sont utilisés pour parcourir un ensemble de nœuds, par exemple l'ensemble des nœuds d'une NodeList, le sous‑arbre du document régi par un nœud particulier, les résultats d'une requête ou tout autre ensemble de nœuds. L'ensemble de nœuds à itérer est déterminé par l'implémentation du NodeIterator. DOM Level 2 spécifie une implémentation unique de NodeIterator pour le parcours en ordre de document d'un sous‑arbre du document. Les instances de ces itérateurs sont créées en appelant DocumentTraversal .createNodeIterator"
type: docs

url: /fr/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Les itérateurs sont utilisés pour parcourir un ensemble de nœuds, par exemple l'ensemble des nœuds d'une NodeList, le sous-arbre du document régi par un nœud particulier, les résultats d'une requête, ou tout autre ensemble de nœuds. L'ensemble de nœuds à itérer est déterminé par l'implémentation du NodeIterator. Le DOM Niveau 2 spécifie une implémentation unique de NodeIterator pour le parcours en ordre du document d'un sous-arbre du document. Les instances de ces itérateurs sont créées en appelant DocumentTraversal .createNodeIterator().

Voir également le [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) Le NodeFilter utilisé pour filtrer les nœuds. |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) Le nœud racine du NodeIterator, tel que spécifié lors de sa création. |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) Cet attribut détermine quels types de nœuds sont présentés via l'itérateur. L'ensemble disponible de constantes est défini dans l'interface NodeFilter. Les nœuds non acceptés par whatToShow seront ignorés, mais leurs enfants peuvent encore être pris en compte. Notez que cet omission a priorité sur le filtre, le cas échéant. |

### Voir aussi

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
