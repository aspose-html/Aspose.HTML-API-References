---
title: "IXPathExpression.Evaluate"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "IXPathExpression method. Évalue cette expression XPath et renvoie un résultat."
type: docs

url: /fr/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Évalue cette expression XPath et retourne un résultat.

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contextNode | Node | Le `context` est le nœud de contexte pour l'évaluation de cette expression XPath. Si le [`IXPathEvaluator`](../../ixpathevaluator/) a été obtenu en castant le [`Document`](../../../com.aspose.html.dom/document/), alors il doit appartenir au même document et doit être un [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), ou un nœud XPathNamespace. Si le nœud de contexte est un [`Text`](../../../com.aspose.html.dom/text/) ou un [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), alors le contexte est interprété comme l'ensemble du nœud texte logique vu par XPath, sauf si le nœud est vide, auquel cas il ne peut pas servir de contexte XPath. |
| type | XPathResultType | Si un `type` spécifique est indiqué, le résultat sera converti pour renvoyer le type spécifié en s'appuyant sur les conversions XPath et échouera si la coercition souhaitée n'est pas possible. Cela doit être l'une des valeurs de [`XPathResultType`](../../xpathresulttype/). |
| result | Object | Le `result` spécifie un objet résultat spécifique qui peut être réutilisé et renvoyé par cette méthode. Si celui‑ci est indiqué comme `null` ou si l'implémentation ne réutilise pas le résultat spécifié, un nouvel objet résultat sera créé et renvoyé. Pour les résultats XPath 1.0, cet objet sera du type [`IXPathResult`](../../ixpathresult/). |

### Valeur de retour

Le résultat de l'évaluation de l'expression XPath. Pour les résultats XPath 1.0, cet objet sera du type [`IXPathResult`](../../ixpathresult/).

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR : Levé si le résultat ne peut pas être converti pour renvoyer le type spécifié. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR : Le nœud provient d'un document qui n'est pas pris en charge par le [`IXPathEvaluator`](../../ixpathevaluator/) qui a créé cette [`IXPathExpression`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR : Le nœud n'est pas d'un type autorisé comme nœud de contexte XPath ou le type de requête n'est pas autorisé par cette [`IXPathExpression`](../). |

### Voir aussi

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
