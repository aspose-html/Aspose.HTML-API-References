---
title: Class NamedNodeMap
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Collections.NamedNodeMap сорт. Представляет коллекции атрибутов доступ к которым можно получить по имени.
type: docs
weight: 40
url: /ru/net/aspose.html.collections/namednodemap/
---
## NamedNodeMap class

Представляет коллекции атрибутов, доступ к которым можно получить по имени.

```csharp
public class NamedNodeMap : DOMObject, IDisposable, IEnumerable<Attr>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.html.collections/namednodemap/item/) { get; } | Возвращает индексный элемент на карте. Если индекс больше или равен количеству узлов на этой карте, возвращается null. (2 indexers) |
| [Length](../../aspose.html.collections/namednodemap/length/) { get; } | Количество узлов на этой карте. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetEnumerator](../../aspose.html.collections/namednodemap/getenumerator/)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| [GetNamedItem](../../aspose.html.collections/namednodemap/getnameditem/)(string) | Извлекает узел, указанный по имени. |
| [GetNamedItemNS](../../aspose.html.collections/namednodemap/getnameditemns/)(string, string) | Извлекает узел, указанный локальным именем и URI пространства имен. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| [RemoveNamedItem](../../aspose.html.collections/namednodemap/removenameditem/)(string) | Удаляет узел, указанный по имени. |
| [RemoveNamedItemNS](../../aspose.html.collections/namednodemap/removenameditemns/)(string, string) | Удаляет узел, указанный локальным именем и URI пространства имен. |
| [SetNamedItem](../../aspose.html.collections/namednodemap/setnameditem/)(Attr) | Добавляет узел, используя его атрибут nodeName. Если узел с таким именем уже присутствует на этой карте, он заменяется новым. Замена узла сама по себе не имеет никакого эффекта. |
| [SetNamedItemNS](../../aspose.html.collections/namednodemap/setnameditemns/)(Attr) | Добавляет узел, используя его namespaceURI и localName. Если узел с этим URI пространства имен и этим локальным именем уже присутствует на этой карте, он заменяется новым. Замена узла сама по себе не имеет никакого эффекта. |

### Смотрите также

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Attr](../../aspose.html.dom/attr/)
* пространство имен [Aspose.Html.Collections](../../aspose.html.collections/)
* сборка [Aspose.HTML](../../)


