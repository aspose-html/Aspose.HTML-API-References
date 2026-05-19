---
title: "Document.CreateAttribute"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Document. Метод Document.createAttribute создаёт новый узел атрибута и возвращает его. Созданный объект является узлом, реализующим интерфейс Attr. DOM не ограничивает, какие типы атрибутов могут быть добавлены к конкретному элементу таким способом."
type: docs

url: /ru/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

Метод Document.createAttribute() создаёт новый узел атрибута и возвращает его. Созданный объект является узлом, реализующим интерфейс [`Attr`](../../attr/). DOM не ограничивает, какие типы атрибутов могут быть добавлены к конкретному элементу таким способом.

```java
public Attr CreateAttribute(String localName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | name — это строка, содержащая имя атрибута. |

### Возвращаемое значение

Узел [`Attr`](../../attr/).

## Примеры

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### См. также

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
