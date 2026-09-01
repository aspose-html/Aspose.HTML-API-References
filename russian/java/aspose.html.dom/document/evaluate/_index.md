---
title: "Document.Evaluate"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Document. Оценивает строку XPath‑выражения и возвращает результат указанного типа, если это возможно."
type: docs

url: /ru/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Выполняет оценку строки XPath‑выражения и, при возможности, возвращает результат указанного типа.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| выражение | String | Строка XPath‑выражения, которую нужно разобрать и оценить. |
| contextNode | Узел | Контекст — это контекстный узел для оценки данного XPath‑выражения. |
| resolver | IXPathNSResolver | Разрешитель позволяет переводить все префиксы, включая префикс пакета xml, внутри XPath‑выражения в соответствующие URI пакетов. |
| тип | XPathResultType | Если указан конкретный тип, результат будет возвращён в виде соответствующего типа. |
| result | Объект | Результат указывает конкретный объект результата, который может быть переиспользован и возвращён этим методом. |

### Возвращаемое значение

Результат оценки XPath‑выражения.

### См. также

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
