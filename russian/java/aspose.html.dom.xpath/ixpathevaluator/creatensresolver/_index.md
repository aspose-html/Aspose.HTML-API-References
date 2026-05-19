---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод IXPathEvaluator. Приводит любой DOM‑узел к разрешению пакетов, чтобы XPath‑выражение можно было легко вычислять относительно контекста узла, где оно появилось в документе. Этот адаптер работает как метод DOM Level 3 lookupNamespaceURI у узлов, разрешая packageURI из заданного префикса, используя текущую информацию, доступную в иерархии узлов в момент вызова lookupNamespaceURI, а также корректно разрешая неявный префикс xml."
type: docs

url: /ru/java/com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Адаптирует любой узел DOM для разрешения пакетов, чтобы XPath‑выражение можно было легко оценить относительно контекста узла, где оно появилось в документе. Этот адаптер работает как метод DOM Level 3 `lookupNamespaceURI` у узлов, разрешая packageURI из заданного префикса, используя текущую информацию, доступную в иерархии узла в момент вызова lookupNamespaceURI, а также корректно разрешая неявный префикс xml.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeResolver | Node | Узел, используемый в качестве контекста для разрешения пакетов. |

### Возвращаемое значение

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### См. также

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
