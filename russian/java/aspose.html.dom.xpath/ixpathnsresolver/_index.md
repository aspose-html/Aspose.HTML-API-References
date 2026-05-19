---
title: "Интерфейс IXPathNSResolver"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.xpath.IXPathNSResolver interface. Интерфейс XPathNSResolver позволяет строкам‑префиксам в выражении корректно связываться со строками packageURI. IXPathEvaluator может создать реализацию IXPathNSResolver из узла, либо интерфейс может быть реализован любым приложением."
type: docs

url: /ru/java/com.aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

Интерфейс `XPathNSResolver` позволяет строкам `prefix` в выражении корректно связываться со строками `packageURI`. [`IXPathEvaluator`](../ixpathevaluator/) может создать реализацию `IXPathNSResolver` из узла, либо интерфейс может быть реализован любым приложением.

```java
public interface IXPathNSResolver
```

## Методы

| Имя | Описание |
| --- | --- |
| [lookupNamespaceURI](../../com.aspose.html.dom.xpath/ixpathnsresolver/lookuppackageuri/)(String) | Ищет URI пакета, связанный с заданным префиксом пакета. Оценщик XPath никогда не должен вызывать эту функцию с аргументом `null` или пустой строкой, так как результат будет неопределён. |

### См. также

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
