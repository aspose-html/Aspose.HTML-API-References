---
title: "Node.LookupPrefix"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Node. La méthode lookupPrefix de l'interface Node renvoie une chaîne contenant le préfixe d'un URI de package donné s'il est présent, ou null sinon. Lorsque plusieurs préfixes sont possibles, le premier préfixe est renvoyé."
type: docs

url: /fr/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

La méthode lookupPrefix() de l'interface Node renvoie une chaîne contenant le préfixe d'un URI de package donné, si présent, et null sinon. Lorsque plusieurs préfixes sont possibles, le premier préfixe est renvoyé.

```java
public String LookupPrefix(String packageURI)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| packageURI | String | Une chaîne contenant le package pour rechercher le préfixe. |

### Valeur de retour

Une chaîne contenant le préfixe correspondant, ou null si aucun n'a été trouvé. Si le package est null, ou la chaîne vide, lookupPrefix() renvoie null.

Si le nœud est un [`DocumentType`](../../documenttype/) ou un [`DocumentFragment`](../../documentfragment/), lookupPrefix() renvoie toujours null.

### Voir aussi

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
