---
title: "Document.Evaluate"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Document. Évalue une chaîne d'expression XPath et renvoie un résultat du type spécifié si possible"
type: docs

url: /fr/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Évalue une chaîne d'expression XPath et renvoie un résultat du type spécifié si possible.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| expression | String | La chaîne d'expression XPath à analyser et évaluer. |
| contextNode | Node | Le contexte est le nœud de contexte pour l'évaluation de cette expression XPath. |
| resolver | IXPathNSResolver | Le résolveur permet la traduction de tous les préfixes, y compris le préfixe du package xml, dans l'expression XPath en URI de package appropriés. |
| type | XPathResultType | Si un type spécifique est indiqué, le résultat sera renvoyé sous le type correspondant. |
| result | Objet | Le résultat spécifie un objet résultat spécifique qui peut être réutilisé et renvoyé par cette méthode. |

### Valeur de retour

Le résultat de l'évaluation de l'expression XPath.

### Voir aussi

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
