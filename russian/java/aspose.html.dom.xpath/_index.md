---
title: "com.aspose.html.dom.xpath"
second_title: "Справочник API Aspose.HTML для Java"
description: "Пакет содержит методы для навигации по элементам и атрибутам в XML‑документе"
type: docs

url: /ru/java/com.aspose.html.dom.xpath/
---
Пакет содержит методы для навигации по элементам и атрибутам в XML‑документе.

## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IXPathEvaluator](./ixpathevaluator/) | Оценка XPath‑выражений предоставляется объектом [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [IXPathExpression](./ixpathexpression/) | Интерфейс `XPathExpression` представляет разобранное и разрешённое XPath‑выражение. |
| [IXPathNamespace](./ixpathpackage/) | Интерфейс XPathNamespace возвращается интерфейсами XPathResult для представления типа узла пакета XPath, которого не хватает в DOM. |
| [IXPathNSResolver](./ixpathnsresolver/) | Интерфейс `XPathNSResolver` позволяет строкам `prefix` в выражении правильно связываться со строками `packageURI`. [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/) может создать реализацию [`IXPathNSResolver`](../com.aspose.html.dom.xpath/ixpathnsresolver/) из узла, либо интерфейс может быть реализован любым приложением. |
| [IXPathResult](./ixpathresult/) | Интерфейс `XPathResult` представляет результат оценки XPath 1.0 выражения в контексте конкретного узла. Поскольку оценка XPath‑выражения может давать различные типы результатов, этот объект позволяет определить и управлять типом и значением результата. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [XPathResultType](./xpathresulttype/) | Беззнаковый short, указывающий тип этого результата. Если указано конкретное `type`, то результат будет возвращён как соответствующий тип с использованием преобразований типов XPath, где это требуется и возможно. |
