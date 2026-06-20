---
title: "Node.TextContent"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Node propriété. La propriété textContent de l'interface Node représente le contenu texte du nœud et de ses descendants"
type: docs

url: /fr/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

La propriété textContent de l'interface [`Node`](../) représente le contenu texte du nœud et de ses descendants.

```java
public String TextContent { get; set; }
```

### Property Value

Une chaîne, ou null. Sa valeur dépend de la situation :

Si le nœud est un document ou un doctype, textContent renvoie null. Note : pour obtenir tout le texte et les données CDATA du document entier, utilisez document.documentElement.textContent. Si le nœud est une section CDATA, un commentaire, une instruction de traitement ou un nœud texte, textContent renvoie ou définit le texte à l'intérieur du nœud, c’est‑à‑dire le [`Node.nodeValue`](../nodevalue/). Pour les autres types de nœuds, textContent renvoie la concaténation du textContent de chaque nœud enfant, à l'exclusion des commentaires et des instructions de traitement.

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Voir aussi

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
