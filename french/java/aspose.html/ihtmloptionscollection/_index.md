---
title: "Interface IHTMLOptionsCollection"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.IHTMLOptionsCollection. Un HTMLOptionsCollection est une liste de nœuds représentant l'élément option HTML. Un nœud individuel peut être accédé soit par son indice ordinal, soit par le nom ou les attributs id du nœud. Les collections dans le DOM HTML sont supposées être dynamiques, ce qui signifie qu'elles sont automatiquement mises à jour lorsque le document sous-jacent est modifié."
type: docs

url: /fr/java/com.aspose.html/ihtmloptionscollection/
---
## IHTMLOptionsCollection interface

Un `HTMLOptionsCollection` est une liste de nœuds représentant l'élément d'option HTML. Un nœud individuel peut être accédé soit par son indice ordinal, soit par les attributs `name` ou `id` du nœud. Les collections dans le DOM HTML sont supposées être dynamiques, ce qui signifie qu'elles sont automatiquement mises à jour lorsque le document sous-jacent est modifié.

Voir également la [Spécification du modèle d'objet Document (DOM) Niveau 2 HTML](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109). @since DOM Niveau 2

```java
public interface IHTMLOptionsCollection : IEnumerable<Element>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getItem](../../com.aspose.html/ihtmloptionscollection/item/) Retourne l'élément d'indice index dans la collection. Si index est supérieur ou égal au nombre de nœuds dans la liste, cela retourne null. (2 indexeurs) |
| [getLength](../../com.aspose.html/ihtmloptionscollection/length/) Le nombre de nœuds dans la liste. |

## Méthodes

| Nom | Description |
| --- | --- |
| [namedItem](../../com.aspose.html/ihtmloptionscollection/nameditem/)(String) | La méthode retourne l'élément d'indice index dans la collection. http://www.w3.org/TR/DOM-Level-2-HTML/html.html#HTMLOptionsCollection-namedItem |

### Voir aussi

* class [Element](../../com.aspose.html.dom/element/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
