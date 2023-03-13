---
title: Document.Evaluate
second_title: Справочник по Aspose.HTML для .NET API
description: Document метод. Вычисляет строку выражения XPath и возвращает результат указанного типа если это возможно.
type: docs
weight: 950
url: /ru/net/aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Вычисляет строку выражения XPath и возвращает результат указанного типа, если это возможно.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| expression | String | Строка выражения XPath для анализа и оценки. |
| contextNode | Node | Контекст — это узел контекста для оценки этого выражения XPath. |
| resolver | IXPathNSResolver | Преобразователь разрешает преобразование всех префиксов, включая префикс пространства имен xml , в выражении XPath в соответствующие URI пространства имен. |
| type | XPathResultType | Если указан конкретный тип, то результат будет возвращен как соответствующий тип. |
| result | Object | Результат указывает конкретный объект результата, который может быть повторно использован и возвращен этим методом. |

### Возвращаемое значение

Результат оценки выражения XPath.

### Смотрите также

* interface [IXPathResult](../../../aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)


