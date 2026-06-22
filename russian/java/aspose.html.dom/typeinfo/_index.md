---
title: "Класс TypeInfo"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.TypeInfo. TypeInfo представляет тип, на который ссылаются узлы Element или Attr, указанные в схемах, связанных с документом."
type: docs

url: /ru/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo представляет тип, на который ссылаются узлы Element или Attr, указанный в схемах, связанных с документом.

```java
public class TypeInfo : DOMObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) Имя типа, объявленного для связанного элемента или атрибута, или null, если неизвестно. |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) Получает пакет типа. Пакет типа, объявленного для связанного элемента или атрибута, или null, если элемент не имеет объявления или информация о пакете недоступна. |

## Методы

| Имя | Описание |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | Этот метод возвращает, существует ли производное отношение между определением ссылочного типа, т.е. TypeInfo, на котором вызывается метод, и другим определением типа, т.е. переданным в параметрах. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | Если схема документа является XML Schema [XML Schema Part 1], эта константа представляет производное отношение по расширению. |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | Если схема документа является XML Schema [XML Schema Part 1], эта константа представляет список. |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | Если схема документа является XML Schema [XML Schema Part 1], эта константа представляет производное отношение по ограничению, если задействованы сложные типы, или ограничение, если задействованы простые типы. |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | Если схема документа является XML Schema [XML Schema Part 1], эта константа представляет объединение, если задействованы простые типы. |

### См. также

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
