---
title: Evaluate
second_title: Référence de l'API Aspose.HTML pour .NET
description: Évalue cette expression XPath et renvoie un résultat.
type: docs
weight: 10
url: /fr/net/aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Évalue cette expression XPath et renvoie un résultat.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| contextNode | Node | La`le contexte` est le nœud de contexte pour l'évaluation de cette expression XPath. Si le[`IXPathEvaluator`](../../ixpathevaluator) a été obtenu en coulant le[`Document`](../../../aspose.html.dom/document) alors cela doit appartenir au même document et doit être un[`Document`](../../../aspose.html.dom/document) ,[`Element`](../../../aspose.html.dom/element) ,[`Attr`](../../../aspose.html.dom/attr) , [`Text`](../../../aspose.html.dom/text) ,[`CDATASection`](../../../aspose.html.dom/cdatasection) ,[`Comment`](../../../aspose.html.dom/comment) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction) , ouXPathNamespace nœud. Si le nœud de contexte est un[`Text`](../../../aspose.html.dom/text) ou un[`CDATASection`](../../../aspose.html.dom/cdatasection), alors le contexte est interprété comme l'ensemble du nœud de texte logique tel qu'il est vu par XPath, sauf si le nœud est vide auquel cas il ne peut pas servir de contexte XPath. |
| type | XPathResultType | Si un spécifique`taper` est spécifié, le résultat sera contraint de renvoyer le type spécifié en s'appuyant sur les conversions XPath et échouera si la coercition souhaitée n'est pas possible. Cela doit être l'une des valeurs de[`XPathResultType`](../../xpathresulttype). |
| result | Object | La`résultat` spécifie un objet de résultat spécifique qui peut être réutilisé et renvoyé par cette méthode. Si cela est spécifié comme`nul`ou si l'implémentation ne réutilise pas le résultat spécifié, un nouvel objet de résultat sera construit et renvoyé. Pour les résultats XPath 1.0, cet objet sera de type[`IXPathResult`](../../ixpathresult). |

### Return_Value

Résultat de l'évaluation de l'expression XPath. Pour les résultats XPath 1.0, cet objet sera de type[`IXPathResult`](../../ixpathresult).

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception) | TYPE_ERR : déclenché si le résultat ne peut pas être converti pour renvoyer le type spécifié. |
| [DOMException](../../../aspose.html.dom/domexception) | WRONG_DOCUMENT_ERR : le nœud provient d'un document qui n'est pas pris en charge par le[`IXPathEvaluator`](../../ixpathevaluator) qui a créé ce[`IXPathExpression`](../../ixpathexpression). |
| [DOMException](../../../aspose.html.dom/domexception) | NOT_SUPPORTED_ERR : le nœud n'est pas un type autorisé en tant que nœud de contexte XPath ou le type de requête n'est pas autorisé par cette[`IXPathExpression`](../../ixpathexpression). |

### Voir également

* interface [IXPathResult](../../ixpathresult)
* class [Node](../../../aspose.html.dom/node)
* enum [XPathResultType](../../xpathresulttype)
* interface [IXPathExpression](../../ixpathexpression)
* espace de noms [Aspose.Html.Dom.XPath](../../ixpathexpression)
* Assemblée [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->