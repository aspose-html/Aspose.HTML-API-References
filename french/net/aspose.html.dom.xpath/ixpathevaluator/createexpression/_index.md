---
title: IXPathEvaluator.CreateExpression
second_title: Référence de l'API Aspose.HTML pour .NET
description: IXPathEvaluator méthode. Crée une expression XPath analysée avec des espaces de noms résolus. Ceci est utile lorsquune expression sera réutilisée dans une application car cela permet de compiler la chaîne dexpression dans une forme interne plus efficace et de prérésoudre tous les préfixes despace de noms qui se produisent dans lexpression.
type: docs
weight: 10
url: /fr/net/aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Crée une expression XPath analysée avec des espaces de noms résolus. Ceci est utile lorsqu'une expression sera réutilisée dans une application car cela permet de compiler la chaîne d'expression dans une forme interne plus efficace et de pré-résoudre tous les préfixes d'espace de noms qui se produisent dans l'expression.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| expression | String | Chaîne d'expression XPath à analyser. |
| resolver | IXPathNSResolver | Le`résolveur` permet la traduction de tous les préfixes, y compris le`XML` préfixe d'espace de noms, dans l'expression XPath dans les URI d'espace de noms appropriés . Si cela est spécifié comme`nul` , tout préfixe d'espace de noms dans l'expression entraînera[`DOMException`](../../../aspose.html.dom/domexception/) étant lancé avec le code`NAMESPACE_ERR`. |

### Return_Value

Forme compilée de l'expression XPath.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR : déclenché si l'expression n'est pas légale selon les règles de[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR : déclenché si l'expression contient des préfixes d'espace de noms qui ne peuvent pas être résolus par le[`IXPathNSResolver`](../../ixpathnsresolver/). |

### Voir également

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* espace de noms [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* Assemblée [Aspose.HTML](../../../)


