---
title: "Document.CreateExpression"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Document. Crée une expression XPath analysée avec les packages résolus. Ceci est utile lorsqu'une expression sera réutilisée dans une application car cela permet de compiler la chaîne d'expression en une forme interne plus efficace et de pré‑résoudre tous les préfixes de package présents dans l'expression"
type: docs

url: /fr/java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Crée une expression XPath analysée avec les packages résolus. Ceci est utile lorsqu'une expression sera réutilisée dans une application, car cela permet de compiler la chaîne d'expression en une forme interne plus efficace et de pré‑résoudre tous les préfixes de package présents dans l'expression.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| expression | String | La chaîne d'expression XPath à analyser. |
| resolver | IXPathNSResolver | Le `resolver` permet la traduction de tous les préfixes, y compris le préfixe de package `xml`, dans l'expression XPath en URI de package appropriés. Si cela est spécifié comme `null`, tout préfixe de package dans l'expression entraînera le lancement d'une [`DOMException`](../../domexception/) avec le code `NAMESPACE_ERR`. |

### Valeur de retour

La forme compilée de l'expression XPath.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Levée si l'expression n'est pas valide selon les règles du [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [dOMException](../../domexception/) | NAMESPACE_ERR: Levée si l'expression contient des préfixes de package qui ne peuvent pas être résolus par le [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) spécifié. |

### Voir aussi

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
