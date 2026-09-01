---
title: "IXPathEvaluator.Evaluate"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode IXPathEvaluator. Évalue une chaîne d'expression XPath et renvoie un résultat du type spécifié si possible."
type: docs

url: /fr/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Évalue une chaîne d'expression XPath et renvoie un résultat du type spécifié si possible.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| expression | String | La chaîne d'expression XPath à analyser et évaluer. |
| contextNode | Node | Le `context` est le nœud de contexte pour l'évaluation de cette expression XPath. Si le [`IXPathEvaluator`](../) a été obtenu en castant le [`Document`](../../../com.aspose.html.dom/document/) alors celui‑ci doit appartenir au même document et doit être un [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), ou un nœud XPathNamespace. Si le nœud de contexte est un [`Text`](../../../com.aspose.html.dom/text/) ou un [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), alors le contexte est interprété comme l'ensemble du nœud texte logique vu par XPath, à moins que le nœud ne soit vide, auquel cas il ne peut pas servir de contexte XPath. |
| resolver | IXPathNSResolver | Le `resolver` permet la traduction de tous les préfixes, y compris le préfixe de package `xml`, dans l'expression XPath en URI de package appropriés. Si cela est spécifié comme `null`, tout préfixe de package dans l'expression entraînera le lancement de [`DOMException`](../../../com.aspose.html.dom/domexception/) avec le code `NAMESPACE_ERR`. |
| type | XPathResultType | Si un `type` spécifique est indiqué, le résultat sera renvoyé sous le type correspondant. Pour les résultats XPath 1.0, cela doit être l'une des valeurs de l'énumération [`XPathResultType`](../../xpathresulttype/). |
| result | Object | Le `result` spécifie un objet résultat spécifique qui peut être réutilisé et renvoyé par cette méthode. Si celui‑ci est indiqué comme `null` ou si l'implémentation ne réutilise pas le résultat spécifié, un nouvel objet résultat sera construit et renvoyé. Pour les résultats XPath 1.0, cet objet sera de type [`IXPathResult`](../../ixpathresult/). |

### Valeur de retour

Le résultat de l'évaluation de l'expression XPath. Pour les résultats XPath 1.0, cet objet sera de type [`IXPathResult`](../../ixpathresult/).

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR : Levée si l'expression n'est pas valide selon les règles du [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR : Levé si le résultat ne peut pas être converti pour renvoyer le type spécifié. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR : Levée si l'expression contient des préfixes de package qui ne peuvent pas être résolus par le [`IXPathNSResolver`](../../ixpathnsresolver/) spécifié. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR : Le nœud provient d'un document qui n'est pas pris en charge par ce [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR : Le nœud n'est pas d'un type autorisé comme nœud de contexte XPath ou le type de requête n'est pas autorisé par ce [`IXPathEvaluator`](../). |

### Voir aussi

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
