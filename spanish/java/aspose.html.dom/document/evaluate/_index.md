---
title: "Document.Evaluate"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Document. Evalúa una cadena de expresión XPath y devuelve un resultado del tipo especificado si es posible"
type: docs

url: /es/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Evalúa una cadena de expresión XPath y devuelve un resultado del tipo especificado si es posible.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expresión | String | La cadena de expresión XPath que se debe analizar y evaluar. |
| contextNode | Node | El contexto es el nodo de contexto para la evaluación de esta expresión XPath. |
| resolver | IXPathNSResolver | El resolvedor permite la traducción de todos los prefijos, incluido el prefijo del paquete xml, dentro de la expresión XPath a URIs de paquete apropiados. |
| tipo | XPathResultType | Si se especifica un tipo específico, entonces el resultado se devolverá como el tipo correspondiente. |
| result | Objeto | El resultado especifica un objeto de resultado específico que puede ser reutilizado y devuelto por este método. |

### Valor de retorno

El resultado de la evaluación de la expresión XPath.

### Ver también

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
