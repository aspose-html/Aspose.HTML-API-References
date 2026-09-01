---
title: "com.aspose.html.dom.traversal"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Le package com.aspose.html.dom.traversal contient des méthodes qui créent des itérateurs et des tree-walkers pour naviguer entre les éléments et parcourir un nœud ainsi que ses enfants dans l'ordre du document."
type: docs

url: /fr/java/com.aspose.html.dom.traversal/
---
Le package **com.aspose.html.dom.traversal** contient des méthodes qui créent des itérateurs et des parcours d'arbre pour naviguer entre les éléments et parcourir un nœud et ses enfants dans l'ordre du document.

## Interfaces

| Interface | Description |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal contient des méthodes qui créent des itérateurs et des tree-walkers pour parcourir un nœud et ses enfants dans l'ordre du document (parcours en profondeur, pré-ordre, qui est équivalent à l'ordre dans lequel les balises d'ouverture apparaissent dans la représentation textuelle du document). Dans les DOM qui prennent en charge la fonctionnalité Traversal, DocumentTraversal sera implémenté par les mêmes objets qui implémentent l'interface Document. |
| [IElementTraversal](./ielementtraversal/) | L'interface ElementTraversal est un ensemble d'attributs en lecture seule qui permettent à un auteur de naviguer facilement entre les éléments d'un document. Dans les implémentations conformes de Element Traversal, tous les objets qui implémentent Element doivent également implémenter l'interface ElementTraversal. |
| [INodeFilter](./inodefilter/) | Les filtres sont des objets qui savent comment « filtrer » les nœuds. Si un NodeIterator ou un TreeWalker reçoit un NodeFilter, il applique le filtre avant de renvoyer le nœud suivant. Si le filtre indique d'accepter le nœud, la logique de parcours le renvoie ; sinon, le parcours recherche le nœud suivant et fait comme si le nœud rejeté n'existait pas. |
| [INodeIterator](./inodeiterator/) | Les itérateurs sont utilisés pour parcourir un ensemble de nœuds, par exemple l'ensemble des nœuds d'une NodeList, le sous-arbre du document régi par un nœud particulier, les résultats d'une requête, ou tout autre ensemble de nœuds. L'ensemble de nœuds à itérer est déterminé par l'implémentation du NodeIterator. Le DOM Niveau 2 spécifie une implémentation unique de NodeIterator pour le parcours en ordre du document d'un sous-arbre du document. Les instances de ces itérateurs sont créées en appelant DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Les itérateurs sont utilisés pour parcourir un ensemble de nœuds, par exemple l'ensemble des nœuds d'une NodeList, le sous-arbre du document régi par un nœud particulier, les résultats d'une requête, ou tout autre ensemble de nœuds. L'ensemble de nœuds à itérer est déterminé par l'implémentation du NodeIterator. Le DOM Niveau 2 spécifie une implémentation unique de NodeIterator pour le parcours en ordre du document d'un sous-arbre du document. Les instances de ces itérateurs sont créées en appelant DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | Les objets TreeWalker sont utilisés pour naviguer dans un arbre ou un sous-arbre de document en utilisant la vue du document définie par leurs drapeaux whatToShow et le filtre (le cas échéant). Toute fonction qui effectue une navigation à l'aide d'un TreeWalker supportera automatiquement toute vue définie par un TreeWalker. |
