---
title: "Интерфейс IXPathResult"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.dom.xpath.IXPathResult. Интерфейс XPathResult представляет результат оценки XPath 1.0 выражения в контексте конкретного узла. Поскольку оценка XPath-выражения может давать различные типы результатов, этот объект позволяет обнаруживать и управлять типом и значением результата"
type: docs

url: /ru/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

Интерфейс `XPathResult` представляет результат оценки XPath 1.0 выражения в контексте конкретного узла. Поскольку оценка XPath‑выражения может давать различные типы результатов, этот объект позволяет определить и управлять типом и значением результата.

```java
public interface IXPathResult
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) Значение этого логического результата. |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) Указывает, что итератор стал недействительным. Истина, если `resultType` имеет тип `UnorderedNodeIterator` или `OrderedNodeIterator` и документ был изменён с момента возврата этого результата. |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) Значение этого числового результата. |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) Код, представляющий тип этого результата, как определено перечислением http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/) enum. |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) Значение этого результата единственного узла, которое может быть `null`. |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) Количество узлов в снимке результата. Допустимые значения индексов snapshotItem — от `0` до `snapshotLength-1` включительно. |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) Значение этого строкового результата. |

## Методы

| Имя | Описание |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Итерирует и возвращает следующий узел из набора узлов или `null`, если узлов больше нет. |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Возвращает элемент с индексом `index` в коллекции снимка. Если `index` больше или равен количеству узлов в списке, метод возвращает `null`. В отличие от результата итератора, снимок не становится недействительным, но может не соответствовать текущему документу, если он изменён. |

### См. также

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
