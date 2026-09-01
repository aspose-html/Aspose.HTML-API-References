---
title: "ICSSRule.ParentRule"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété ICSSRule. Si cette règle est contenue dans une autre règle, par exemple une règle de style à l'intérieur d'un bloc média, il s'agit de la règle contenant. Si cette règle n'est imbriquée dans aucune autre règle, elle renvoie null."
type: docs

url: /fr/java/com.aspose.html.dom.css/icssrule/parentrule/
---
## ICSSRule.ParentRule property

Si cette règle est contenue dans une autre règle (par exemple une règle de style à l'intérieur d'un bloc @media), il s'agit de la règle contenant. Si cette règle n'est imbriquée dans aucune autre règle, elle renvoie null.

```java
public ICSSRule ParentRule { get; }
```

### Property Value

Un [`CSSRule`](../) qui est le type des règles contenant. Si la règle actuelle se trouve dans une requête média, cela renverra [`CSSMediaRule`](../../icssmediarule/). Sinon, cela renvoie null.

### Voir aussi

* interface [ICSSRule](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
