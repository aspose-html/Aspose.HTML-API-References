---
title: "Node.CloneNode"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Node. La méthode cloneNode de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre contrôle si le sous‑arbre contenu dans un nœud est également cloné ou non."
type: docs

url: /fr/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non.

Cloner un nœud copie tous ses attributs et leurs valeurs, y compris les écouteurs intrinsèques (en ligne). Il ne copie pas les écouteurs d'événements ajoutés à l'aide de [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) ou ceux assignés aux propriétés d'élément (par ex., node.onclick = someFunction). De plus, pour un élément [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/), l'image peinte n'est pas copiée.

```java
public Node CloneNode()
```

### Valeur de retour

Le nouveau [`Node`](../) cloné. Le nœud cloné n'a pas de parent et ne fait pas partie du document, jusqu'à ce qu'il soit ajouté à un autre nœud qui fait partie du document, en utilisant [`Node.appendChild()`](../appendchild/) ou une méthode similaire.

### Voir aussi

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non.

Cloner un nœud copie tous ses attributs et leurs valeurs, y compris les écouteurs intrinsèques (en ligne). Il ne copie pas les écouteurs d'événements ajoutés à l'aide de [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) ou ceux assignés aux propriétés d'élément (par ex., node.onclick = someFunction). De plus, pour un élément [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement), l'image peinte n'est pas copiée.

```java
public Node CloneNode(bool deep)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| deep | Boolean | Si vrai, alors le nœud et tout son sous‑arbre, y compris le texte pouvant se trouver dans les nœuds enfants [`Text`](../../text/), sont également copiés. |

### Valeur de retour

Le nouveau [Node](T:com.aspose.html.dom.Node) cloné. Le nœud cloné n'a pas de parent et ne fait pas partie du document, jusqu'à ce qu'il soit ajouté à un autre nœud qui fait partie du document, en utilisant [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) ou une méthode similaire.

### Voir aussi

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
