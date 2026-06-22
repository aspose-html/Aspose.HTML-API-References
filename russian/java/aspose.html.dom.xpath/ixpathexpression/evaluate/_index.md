---
title: "IXPathExpression.Evaluate"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод IXPathExpression. Выполняет это XPath-выражение и возвращает результат."
type: docs

url: /ru/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Выполняет оценку этого XPath-выражения и возвращает результат.

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| contextNode | Node | `context` — это контекстный узел для оценки этого XPath-выражения. Если [`IXPathEvaluator`](../../ixpathevaluator/) был получен путём приведения типа [`Document`](../../../com.aspose.html.dom/document/), то этот узел должен принадлежать тому же документу и должен быть [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/) или узлом XPathNamespace. Если контекстный узел является [`Text`](../../../com.aspose.html.dom/text/) или [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), то контекст интерпретируется как весь логический текстовый узел, видимый XPath, если только узел не пуст, в этом случае он не может служить контекстом XPath. |
| type | XPathResultType | Если указано конкретное `type`, то результат будет приведён к указанному типу с использованием преобразований XPath и завершится ошибкой, если требуемое приведение невозможно. Это должно быть одно из значений [`XPathResultType`](../../xpathresulttype/). |
| result | Object | `result` указывает конкретный объект результата, который может быть переиспользован и возвращён этим методом. Если он указан как `null` или реализация не переиспользует указанный результат, будет создан новый объект результата и возвращён. Для результатов XPath 1.0 этот объект будет типа [`IXPathResult`](../../ixpathresult/). |

### Возвращаемое значение

Результат оценки XPath-выражения. Для результатов XPath 1.0 этот объект будет типа [`IXPathResult`](../../ixpathresult/).

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Возникает, если результат нельзя преобразовать к указанному типу. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Узел принадлежит документу, не поддерживаемому [`IXPathEvaluator`](../../ixpathevaluator/), который создал эту [`IXPathExpression`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Узел не является типом, разрешённым в качестве контекстного узла XPath, или запрашиваемый тип не разрешён этой [`IXPathExpression`](../). |

### См. также

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
