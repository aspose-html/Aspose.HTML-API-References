---
title: IXPathExpression.Evaluate
second_title: Справочник по Aspose.HTML для .NET API
description: IXPathExpression метод. Оценивает это выражение XPath и возвращает результат.
type: docs
weight: 10
url: /ru/net/aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Оценивает это выражение XPath и возвращает результат.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| contextNode | Node | `контекст` является контекстным узлом для оценки этого выражения XPath. Если[`IXPathEvaluator`](../../ixpathevaluator/) был получен отливкой[`Document`](../../../aspose.html.dom/document/) то он должен принадлежать тому же документу и должен быть[`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) , [`Text`](../../../aspose.html.dom/text/) ,[`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , илиXPathNamespace узел. Если узел контекста является[`Text`](../../../aspose.html.dom/text/) или[`CDATASection`](../../../aspose.html.dom/cdatasection/), , то контекст интерпретируется как весь логический текстовый узел, видимый XPath, если только узел не является пустым , и в этом случае он не может служить контекстом XPath. |
| type | XPathResultType | Если конкретный`тип` указан, то результат будет принудительно возвращать указанный тип , полагаясь на преобразования XPath, и потерпит неудачу, если желаемое принуждение невозможно. Это должно быть одним из значений[`XPathResultType`](../../xpathresulttype/). |
| result | Object | `результат` указывает конкретный объект результата, который может быть повторно использован и возвращен этим методом. Если это указано как`нулевой`или реализация не использует повторно указанный результат , будет создан и возвращен новый объект результата. Для результатов XPath 1.0 этот объект будет иметь тип [`IXPathResult`](../../ixpathresult/). |

### Возвращаемое значение

Результат вычисления выражения XPath. Для результатов XPath 1.0 этот объект будет иметь тип [`IXPathResult`](../../ixpathresult/).

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: Возникает, если результат не может быть преобразован для возврата указанного типа. |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: узел взят из документа, который не поддерживается [`IXPathEvaluator`](../../ixpathevaluator/) который создал это[`IXPathExpression`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Тип узла не разрешен в качестве узла контекста XPath , или тип запроса не разрешен этим[`IXPathExpression`](../). |

### Смотрите также

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* пространство имен [Aspose.Html.Dom.XPath](../../ixpathexpression/)
* сборка [Aspose.HTML](../../../)


