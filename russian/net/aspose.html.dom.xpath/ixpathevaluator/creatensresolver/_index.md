---
title: IXPathEvaluator.CreateNSResolver
second_title: Справочник по Aspose.HTML для .NET API
description: IXPathEvaluator метод. Адаптирует любой узел DOM для разрешения пространств имен чтобы выражение XPath можно было легко оценить относительно контекста узла в котором оно появилось в документе. Этот адаптер работает как метод DOM Level 3.lookupNamespaceURI на узлах при разрешении namespaceURI из заданного префикса используя текущую информацию доступную в иерархии узла в момент вызова time lookupNamespaceURI также правильно разрешая неявный префикс xml.
type: docs
weight: 20
url: /ru/net/aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Адаптирует любой узел DOM для разрешения пространств имен, чтобы выражение XPath можно было легко оценить относительно контекста узла, в котором оно появилось в документе. Этот адаптер работает как метод DOM Level 3.`lookupNamespaceURI` на узлах при разрешении namespaceURI из заданного префикса, используя текущую информацию, доступную в иерархии узла в момент вызова time lookupNamespaceURI, также правильно разрешая неявный префикс xml.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeResolver | Node | Узел, который будет использоваться в качестве контекста для разрешения пространства имен. |

### Возвращаемое значение

[`IXPathNSResolver`](../../ixpathnsresolver/) который разрешает пространства имен по отношению к определениям в области действия для указанного узла.

### Смотрите также

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* пространство имен [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* сборка [Aspose.HTML](../../../)


