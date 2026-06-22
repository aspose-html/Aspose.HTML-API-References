---
title: "Интерфейс IElementTraversal"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.traversal.IElementTraversal interface. Интерфейс ElementTraversal представляет набор только для чтения атрибутов, позволяющих автору легко перемещаться между элементами в документе. В соответствующих реализациях Element Traversal все объекты, реализующие Element, также должны реализовать интерфейс ElementTraversal."
type: docs

url: /ru/java/com.aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

Интерфейс ElementTraversal представляет набор только для чтения атрибутов, позволяющих автору легко перемещаться между элементами в документе. В соответствующих реализациях Element Traversal все объекты, реализующие Element, также должны реализовать интерфейс ElementTraversal.

```java
public interface IElementTraversal
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) Возвращает текущее количество элементных узлов, являющихся дочерними для этого элемента. 0, если у этого элемента нет дочерних узлов типа nodeType 1. |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) Возвращает первый дочерний элементный узел этого элемента. null, если у этого элемента нет дочерних элементов. |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) Возвращает последний дочерний элементный узел этого элемента. null, если у этого элемента нет дочерних элементов. |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) Возвращает следующий соседний элементный узел этого элемента. null, если у этого элемента нет соседних элементных узлов, идущих после него в дереве документа. |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) Возвращает предыдущий соседний элементный узел этого элемента. null, если у этого элемента нет соседних элементных узлов, идущих перед ним в дереве документа. |

### См. также

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
