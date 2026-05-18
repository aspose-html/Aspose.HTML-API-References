---
title: "IXPathEvaluator.CreateExpression"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode IXPathEvaluator. Crée une expression XPath analysée avec les packages résolus. Cela est utile lorsqu'une expression sera réutilisée dans une application car cela permet de compiler la chaîne d'expression String en une forme interne plus efficace et de pré‑résoudre tous les préfixes de packages qui apparaissent dans l'expression."
type: docs

url: /fr/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Crée une expression XPath analysée avec les packages résolus. Ceci est utile lorsqu'une expression sera réutilisée dans une application, car cela permet de compiler la chaîne d'expression en une forme interne plus efficace et de pré‑résoudre tous les préfixes de package présents dans l'expression.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| expression | String | La chaîne d'expression XPath String à analyser. |
| resolver | IXPathNSResolver | Le `resolver` permet la traduction de tous les préfixes, y compris le préfixe de package `xml`, dans l'expression XPath en URI de package appropriés. Si cette valeur est spécifiée comme `null`, tout préfixe de package dans l'expression entraînera le déclenchement de [`DOMException`](../../../com.aspose.html.dom/domexception/) avec le code `NAMESPACE_ERR`. |

### Valeur de retour

La forme compilée de l'expression XPath.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR : Levée si l'expression n'est pas valide selon les règles du [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR : Levée si l'expression contient des préfixes de package qui ne peuvent pas être résolus par le [`IXPathNSResolver`](../../ixpathnsresolver/) spécifié. |

### Voir aussi

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
