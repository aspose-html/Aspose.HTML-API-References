---
title: "IXPathResult.SnapshotItem"
second_title: "Справочник API Aspose.HTML для Java"
description: "IXPathResult method. Возвращает элемент с индексом index в коллекции снимков. Если index больше или равен количеству узлов в списке, этот метод возвращает null. В отличие от результата итератора, снимок не становится недействительным, но может не соответствовать текущему документу, если он изменён."
type: docs

url: /ru/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Возвращает элемент с индексом `index` в коллекции снимка. Если `index` больше или равен количеству узлов в списке, метод возвращает `null`. В отличие от результата итератора, снимок не становится недействительным, но может не соответствовать текущему документу, если он изменён.

```java
public Node SnapshotItem(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс в коллекцию снимков. |

### Возвращаемое значение

Узел на позиции `index`th в `NodeList`, или `null`, если такой индекс недействителен.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: вызывается, если `resultType` не является типом `UnorderedNodeSnapshot` или `OrderedNodeSnapshot`. |

### См. также

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
