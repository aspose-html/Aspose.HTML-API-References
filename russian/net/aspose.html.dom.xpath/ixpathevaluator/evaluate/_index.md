---
title: Evaluate
second_title: Справочник по Aspose.HTML для .NET API
description: Вычисляет строку выражения XPath и возвращает результат указанного типа если это возможно.
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
| contextNode | Node | Контекст является контекстным узлом для оценки этого выражение XPath. Если[`IXPathEvaluator`](../../ixpathevaluator)был получен приведением [`Document`](../../../aspose.html.dom/document)то он должен принадлежать тому же документу и должен быть [`Document`](../../../aspose.html.dom/document),[`Element`](../../../aspose.html.dom/element),[`Attr`](../../../aspose.html.dom/attr),[`Text`](../../../aspose.html.dom/text), [`CDATASection`](../../../aspose.html.dom/cdatasection),[`Comment`](../../../aspose.html.dom/comment),Инструкцияпообработке, илиXPathNamespacenode. Если узел контекста является[`Text`](../../../aspose.html.dom/text)или [`CDATASection`](../../../aspose.html.dom/cdatasection), тогда контекст интерпретируется как весь логический текстовый узел как его видит XPath, если узел не пуст, и в этом случае он не может служить контекстом XPath. |
| resolver | IXPathNSResolver | Преобразователь разрешает перевод всех префиксов, включая префикс пространства имен` xml` в выражении XPath в соответствующие URI пространства имен. Если это указано как` null` , любой префикс пространства имен в выражении приведет к[`DOMException`](../../../aspose.html.dom/domexception)выбрасывается с кодом` NAMESPACE_ERR` . |
| type | XPathResultType | Если указан конкретный` тип` , то результат будет возвращен как соответствующий тип. Для результатов XPath 1.0 это должно быть одно из значений перечисления [`XPathResultType`](../../xpathresulttype)enum. |
| result | Object | Результат указывает конкретный объект результата, который может быть повторно использован и возвращается этим методом. Если это указано как` null` или реализация не повторно использует указанный результат, будет создан и возвращен новый объект результата. Для результатов XPath 1.0 этот объект будет иметь тип[`IXPathResult`](../../ixpathresult). |

### Возвращаемое значение

Результат вычисления выражения XPath. Для результатов XPath 1.0 этот объект будет иметь тип[`IXPathResult`](../../ixpathresult).

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception) | INVALID_EXPRESSION_ERR:Возникает, если выражение недопустимо в соответствии с правилами[`IXPathEvaluator`](../../ixpathevaluator). |
| [DOMException](../../../aspose.html.dom/domexception) | TYPE_ERR:Возникает, если результат не может быть преобразован для возврата указанного типа. |
| [DOMException](../../../aspose.html.dom/domexception) | NAMESPACE_ERR:Возникает, если выражение содержит префиксы пространств имен которые не могут быть разрешены указанным[`IXPathNSResolver`](../../ixpathnsresolver). |
| [DOMException](../../../aspose.html.dom/domexception) | WRONG_DOCUMENT_ERR:Узел взят из документа, который не поддерживается этим[`IXPathEvaluator`](../../ixpathevaluator). |
| [DOMException](../../../aspose.html.dom/domexception) | NOT_SUPPORTED_ERR:Тип узла не разрешен в качестве контекста XPath узел или запрос тип не разрешен этим[`IXPathEvaluator`](../../ixpathevaluator). |

### Смотрите также

* interface [IXPathResult](../../ixpathresult)
* class [Node](../../../aspose.html.dom/node)
* interface [IXPathNSResolver](../../ixpathnsresolver)
* enum [XPathResultType](../../xpathresulttype)
* interface [IXPathEvaluator](../../ixpathevaluator)
* пространство имен [Aspose.Html.Dom.XPath](../../ixpathevaluator)
* сборка [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
