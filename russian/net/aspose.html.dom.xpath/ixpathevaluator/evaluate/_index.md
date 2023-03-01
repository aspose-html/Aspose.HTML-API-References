---
title: IXPathEvaluator.Evaluate
second_title: Справочник по Aspose.HTML для .NET API
description: IXPathEvaluator метод. Вычисляет строку выражения XPath и возвращает результат указанного типа если это возможно.
type: docs
weight: 30
url: /ru/net/aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Вычисляет строку выражения XPath и возвращает результат указанного типа, если это возможно.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| expression | String | Строка выражения XPath для анализа и оценки. |
| contextNode | Node | `контекст` является контекстным узлом для оценки этого выражения XPath. Если[`IXPathEvaluator`](../) был получен путем литья [`Document`](../../../aspose.html.dom/document/) то он должен принадлежать тому же документу и должен быть [`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) ,[`Text`](../../../aspose.html.dom/text/) , [`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , илиXPathNamespace узел. Если узел контекста является[`Text`](../../../aspose.html.dom/text/) или [`CDATASection`](../../../aspose.html.dom/cdatasection/)тогда контекст интерпретируется как весь логический текстовый узел , видимый XPath, если узел не пуст, и в этом случае он не может служить контекстом XPath. |
| resolver | IXPathNSResolver | `резольвер` разрешает перевод всех префиксов, включая `XML` префикс пространства имен в выражении XPath в соответствующие URI пространства имен. Если это указано как`нулевой` , любой префикс пространства имен в выражении приведет к в[`DOMException`](../../../aspose.html.dom/domexception/) бросают с кодом`NAMESPACE_ERR`. |
| type | XPathResultType | Если конкретный`тип` указан, то результат будет возвращен как соответствующего типа. Для результатов XPath 1.0 это должно быть одно из значений [`XPathResultType`](../../xpathresulttype/) перечисление |
| result | Object | `результат` указывает конкретный объект результата, который может быть повторно использован и возвращен этим методом. Если это указано как`нулевой`или реализация не повторно использует указанный результат, будет создан и возвращен новый объект результата. Для результатов XPath 1.0 этот объект будет иметь тип[`IXPathResult`](../../ixpathresult/). |

### Возвращаемое значение

Результат вычисления выражения XPath. Для результатов XPath 1.0 этот объект будет иметь тип[`IXPathResult`](../../ixpathresult/).

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Возникает, если выражение недопустимо в соответствии с правилами[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: Возникает, если результат не может быть преобразован для возврата указанного типа . |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: Возникает, если выражение содержит префиксы пространств имен , которые не могут быть разрешены указанным[`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: узел взят из документа, который не поддерживается этим[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Тип узла не разрешен в качестве узла контекста XPath , или тип запроса не разрешен этим[`IXPathEvaluator`](../). |

### Смотрите также

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* пространство имен [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* сборка [Aspose.HTML](../../../)


