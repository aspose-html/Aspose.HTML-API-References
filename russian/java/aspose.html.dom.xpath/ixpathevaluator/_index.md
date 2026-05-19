---
title: "Интерфейс IXPathEvaluator"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.xpath.IXPathEvaluator interface. Оценка XPath‑выражений предоставляется IXPathEvaluator."
type: docs

url: /ru/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Оценка XPath‑выражений предоставляется `IXPathEvaluator`.

```java
public interface IXPathEvaluator
```

## Методы

| Имя | Описание |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | Создаёт разобранное XPath‑выражение с разрешёнными пакетами. Это полезно, когда выражение будет переиспользоваться в приложении, так как позволяет компилировать строку выражения во более эффективную внутреннюю форму и предварительно разрешать все префиксы пакетов, встречающиеся в выражении. |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Адаптирует любой узел DOM для разрешения пакетов, чтобы XPath‑выражение можно было легко оценить относительно контекста узла, где оно появилось в документе. Этот адаптер работает как метод DOM Level 3 `lookupNamespaceURI` у узлов, разрешая packageURI из заданного префикса, используя текущую информацию, доступную в иерархии узла в момент вызова lookupNamespaceURI, а также корректно разрешая неявный префикс xml. |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Выполняет оценку строки XPath‑выражения и, при возможности, возвращает результат указанного типа. |

### См. также

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
