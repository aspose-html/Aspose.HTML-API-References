---
title: "IXPathEvaluator.Evaluate"
second_title: "Справочник API Aspose.HTML для Java"
description: "IXPathEvaluator метод. Оценивает строку XPath-выражения String и возвращает результат указанного типа, если это возможно."
type: docs

url: /ru/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Выполняет оценку строки XPath‑выражения и, при возможности, возвращает результат указанного типа.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| выражение | String | Строка XPath-выражения, которую нужно разобрать и оценить. |
| contextNode | Node | `context` — это контекстный узел для оценки этого XPath-выражения. Если [`IXPathEvaluator`](../) был получен путем приведения [`Document`](../../../com.aspose.html.dom/document/), то этот узел должен принадлежать тому же документу и быть [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/) или узлом XPathNamespace. Если контекстный узел является [`Text`](../../../com.aspose.html.dom/text/) или [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), то контекст интерпретируется как весь логический текстовый узел, видимый XPath, если только узел не пуст, в этом случае он не может служить контекстом XPath. |
| resolver | IXPathNSResolver | `resolver` позволяет переводить все префиксы, включая префикс пакета `xml`, внутри XPath-выражения в соответствующие URI пакетов. Если указано `null`, любой префикс пакета внутри выражения приведет к выбросу [`DOMException`](../../../com.aspose.html.dom/domexception/) с кодом `NAMESPACE_ERR`. |
| type | XPathResultType | Если указан конкретный `type`, то результат будет возвращён в соответствующем типе. Для результатов XPath 1.0 это должно быть одно из значений перечисления [`XPathResultType`](../../xpathresulttype/). |
| result | Object | `result` указывает конкретный объект результата, который может быть переиспользован и возвращён этим методом. Если указано `null` или реализация не переиспользует указанный результат, будет создан новый объект результата и возвращён. Для результатов XPath 1.0 этот объект будет типа [`IXPathResult`](../../ixpathresult/). |

### Возвращаемое значение

Результат оценки XPath-выражения. Для результатов XPath 1.0 этот объект будет типа [`IXPathResult`](../../ixpathresult/).

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Возникает, если выражение не соответствует правилам [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Возникает, если результат нельзя преобразовать к указанному типу. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Возникает, если выражение содержит префиксы пакетов, которые не могут быть разрешены указанным [`IXPathNSResolver`](../../ixpathnsresolver/). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Узел принадлежит документу, который не поддерживается этим [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Узел не является типом, разрешённым в качестве контекстного узла XPath, или запрашиваемый тип не разрешён этим [`IXPathEvaluator`](../). |

### См. также

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
