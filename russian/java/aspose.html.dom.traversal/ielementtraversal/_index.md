---
title: "IElementTraversal интерфейс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.traversal.IElementTraversal интерфейс. Интерфейс ElementTraversal представляет набор только для чтения атрибутов, позволяющих автору легко перемещаться между элементами в документе. В соответствующих реализациях Element Traversal все объекты, реализующие Element, также должны реализовать интерфейс ElementTraversal."
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
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) Возвращает текущее количество узлов‑элементов, являющихся дочерними для данного элемента. 0, если у этого элемента нет дочерних узлов типа nodeType 1. |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) Возвращает первый дочерний элемент данного элемента. null, если у этого элемента нет дочерних элементов. |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) Возвращает последний дочерний элемент данного элемента. null, если у этого элемента нет дочерних элементов. |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) Возвращает следующий соседний элемент данного элемента. null, если у этого элемента нет соседних элементов, идущих после него в дереве документа. |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) Возвращает предыдущий соседний элемент данного элемента. null, если у этого элемента нет соседних элементов, идущих перед ним в дереве документа. |

### См. также

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
