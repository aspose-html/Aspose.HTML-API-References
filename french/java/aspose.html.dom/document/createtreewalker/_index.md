---
title: "Document.CreateTreeWalker"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Document. Crée un nouveau TreeWalker sur le sous-arbre enraciné au nœud spécifié."
type: docs

url: /fr/java/com.aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Crée un nouveau TreeWalker sur le sous-arbre enraciné au nœud spécifié.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| racine | Node | nœud qui servira de racine au TreeWalker. Les indicateurs whatToShow et le NodeFilter ne sont pas pris en compte lors du réglage de cette valeur ; tout type de nœud sera accepté comme racine. Le currentNode du TreeWalker est initialisé à ce nœud, qu'il soit visible ou non. La racine sert de point d'arrêt pour les méthodes de traversée qui remontent dans la structure du document, comme parentNode et nextNode. La racine ne doit pas être null. |

### Valeur de retour

Le TreeWalker nouvellement créé.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR : Levé si la racine spécifiée est null. |

### Voir aussi

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Crée un nouveau TreeWalker sur le sous-arbre enraciné au nœud spécifié.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| racine | Node | nœud qui servira de racine au TreeWalker. Les indicateurs whatToShow et le NodeFilter ne sont pas pris en compte lors du réglage de cette valeur ; tout type de nœud sera accepté comme racine. Le currentNode du TreeWalker est initialisé à ce nœud, qu'il soit visible ou non. La racine sert de point d'arrêt pour les méthodes de traversée qui remontent dans la structure du document, comme parentNode et nextNode. La racine ne doit pas être null. |
| whatToShow | Int64 | Le drapeau spécifie quels types de nœuds peuvent apparaître dans la vue logique de l'arbre présenté par le parcourir-arbre. Voir la description de NodeFilter pour l'ensemble des valeurs SHOW_ possibles. Ces drapeaux peuvent être combinés à l'aide de OR. |

### Valeur de retour

Le TreeWalker nouvellement créé.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR : Levé si la racine spécifiée est null. |

### Voir aussi

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Crée un nouveau TreeWalker sur le sous-arbre enraciné au nœud spécifié.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| racine | Node | nœud qui servira de racine au TreeWalker. Les indicateurs whatToShow et le NodeFilter ne sont pas pris en compte lors du réglage de cette valeur ; tout type de nœud sera accepté comme racine. Le currentNode du TreeWalker est initialisé à ce nœud, qu'il soit visible ou non. La racine sert de point d'arrêt pour les méthodes de traversée qui remontent dans la structure du document, comme parentNode et nextNode. La racine ne doit pas être null. |
| whatToShow | Int64 | Le drapeau spécifie quels types de nœuds peuvent apparaître dans la vue logique de l'arbre présenté par le parcourir-arbre. Voir la description de NodeFilter pour l'ensemble des valeurs SHOW_ possibles. Ces drapeaux peuvent être combinés à l'aide de OR. |
| filtre | INodeFilter | NodeFilter à utiliser avec ce TreeWalker, ou null pour indiquer aucun filtre. |

### Valeur de retour

Le TreeWalker nouvellement créé.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR : Levé si la racine spécifiée est null. |

### Voir aussi

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
