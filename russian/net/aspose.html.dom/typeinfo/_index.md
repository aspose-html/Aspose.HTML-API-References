---
title: Class TypeInfo
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.TypeInfo сорт. TypeInfo представляет тип на который ссылаются узлы Element или Attr указанные в схемах связанных с документом.
type: docs
weight: 2530
url: /ru/net/aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo представляет тип, на который ссылаются узлы Element или Attr, указанные в схемах, связанных с документом.

```csharp
public class TypeInfo : DOMObject
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [TypeName](../../aspose.html.dom/typeinfo/typename/) { get; } | Имя типа, объявленного для связанного элемента или атрибута, или null, если неизвестно. |
| [TypeNamespace](../../aspose.html.dom/typeinfo/typenamespace/) { get; } | Получает пространство имен типа. Пространство имен типа, объявленного для связанного элемента или атрибута, или null, если у элемента нет объявления или если информация о пространстве имен недоступна. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript.Type . |
| [IsDerivedFrom](../../aspose.html.dom/typeinfo/isderivedfrom/)(string, string, ulong) | Этот метод возвращает значение, если существует производное определение ссылочного типа, т. е. TypeInfo, для которого вызывается метод, и другое определение типа, т. е. то, которое передается в качестве параметров. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.html.dom/typeinfo/derivation_extension/) | Если схема документа представляет собой XML-схему [XML-схема, часть 1], эта константа представляет происхождение по расширению. |
| const [DERIVATION_LIST](../../aspose.html.dom/typeinfo/derivation_list/) | Если схема документа представляет собой XML-схему [XML-схема, часть 1], эта константа представляет список. |
| const [DERIVATION_RESTRICTION](../../aspose.html.dom/typeinfo/derivation_restriction/) | Если схема документа представляет собой XML-схему [XML-схема, часть 1], эта константа представляет происхождение по ограничению, если задействованы сложные типы, или ограничение, если задействованы простые типы. |
| const [DERIVATION_UNION](../../aspose.html.dom/typeinfo/derivation_union/) | Если схема документа представляет собой XML-схему [XML-схема, часть 1], эта константа представляет объединение, если задействованы простые типы. |

### Смотрите также

* class [DOMObject](../domobject/)
* пространство имен [Aspose.Html.Dom](../../aspose.html.dom/)
* сборка [Aspose.HTML](../../)


