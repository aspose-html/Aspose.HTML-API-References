---
title: Interface IXPathEvaluator
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.XPath.IXPathEvaluator интерфейс. Оценка выражений XPath обеспечиваетсяIXPathEvaluator .
type: docs
weight: 2560
url: /ru/net/aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Оценка выражений XPath обеспечивается`IXPathEvaluator` .

```csharp
public interface IXPathEvaluator
```

## Методы

| Имя | Описание |
| --- | --- |
| [CreateExpression](../../aspose.html.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | Создает проанализированное выражение XPath с разрешенными пространствами имен. Это полезно , когда выражение будет повторно использоваться в приложении, поскольку позволяет скомпилировать строку выражения в более эффективную внутреннюю форму и предварительно разрешить все префиксы пространства имен, которые встречаются в выражении. |
| [CreateNSResolver](../../aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Адаптирует любой узел DOM для разрешения пространств имен, чтобы выражение XPath можно было легко оценить относительно контекста узла, в котором оно появилось в документе. Этот адаптер работает как метод DOM Level 3.`lookupNamespaceURI` на узлах при разрешении namespaceURI из заданного префикса, используя текущую информацию, доступную в иерархии узла в момент вызова time lookupNamespaceURI, также правильно разрешая неявный префикс xml. |
| [Evaluate](../../aspose.html.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Вычисляет строку выражения XPath и возвращает результат указанного типа, если это возможно. |

### Смотрите также

* пространство имен [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* сборка [Aspose.HTML](../../)


