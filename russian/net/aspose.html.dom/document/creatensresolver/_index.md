---
title: Document.CreateNSResolver
second_title: Справочник по Aspose.HTML для .NET API
description: Document метод. Адаптирует любой узел DOM для разрешения пространств имен чтобы выражение XPath можно было легко оценить относительно контекста узла в котором оно появилось в документе. Этот адаптер работает как метод DOM Level 3.lookupNamespaceURI на узлах при разрешении namespaceURI из заданного префикса используя текущую информацию доступную в иерархии узла в момент вызова time lookupNamespaceURI также правильно разрешая неявный префикс xml.
type: docs
weight: 910
url: /ru/net/aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Адаптирует любой узел DOM для разрешения пространств имен, чтобы выражение XPath можно было легко оценить относительно контекста узла, в котором оно появилось в документе. Этот адаптер работает как метод DOM Level 3.`lookupNamespaceURI` на узлах при разрешении namespaceURI из заданного префикса, используя текущую информацию, доступную в иерархии узла в момент вызова time lookupNamespaceURI, также правильно разрешая неявный префикс xml.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeResolver | Node | Узел, который будет использоваться в качестве контекста для разрешения пространства имен. |

### Возвращаемое значение

[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver/) который разрешает пространства имен относительно определений в области действия для указанного узла.

### Смотрите также

* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)


