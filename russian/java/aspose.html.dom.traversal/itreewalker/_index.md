---
title: "Интерфейс ITreeWalker"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.dom.traversal.ITreeWalker. Объекты TreeWalker используются для навигации по дереву документа или поддереву, используя представление документа, определённое их флагами whatToShow и при наличии фильтром. Любая функция, выполняющая навигацию с помощью TreeWalker, автоматически поддерживает любое представление, определённое TreeWalker."
type: docs

url: /ru/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

Объекты TreeWalker используются для навигации по дереву документа или поддереву, используя представление документа, определённое их флагами whatToShow и фильтром (если имеется). Любая функция, выполняющая навигацию с помощью TreeWalker, автоматически поддерживает любое представление, определённое TreeWalker.

Исключение узлов из логического представления поддерева может привести к структуре, существенно отличающейся от того же поддерева в полном, нефильтрованном документе. Узлы, являющиеся соседями в представлении TreeWalker, могут быть дочерними элементами разных, сильно разнесённых узлов в оригинальном представлении. Например, рассмотрим NodeFilter, который пропускает все узлы, кроме текстовых узлов и корневого узла документа. В получающемся логическом представлении все текстовые узлы будут соседями и появятся как прямые дочерние элементы корневого узла, независимо от того, насколько глубоко вложена структура оригинального документа.

Смотрите также [Спецификация Traversal and Range уровня 2 модели объектного документа (DOM)](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## Свойства

| Имя | Описание |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## Методы

| Имя | Описание |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | Перемещает TreeWalker к первому видимому дочернему узлу текущего узла и возвращает новый узел. Если у текущего узла нет видимых дочерних узлов, возвращает null и сохраняет текущий узел. |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | Перемещает TreeWalker к последнему видимому дочернему узлу текущего узла и возвращает новый узел. Если у текущего узла нет видимых дочерних узлов, возвращает null и сохраняет текущий узел. |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | Перемещает TreeWalker к следующему видимому узлу в порядке документа относительно текущего узла и возвращает новый узел. Если у текущего узла нет следующего узла, или если поиск nextNode пытается подняться выше корневого узла TreeWalker, возвращает null и сохраняет текущий узел. |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | Перемещает TreeWalker к следующему соседнему узлу текущего узла и возвращает новый узел. Если у текущего узла нет видимого следующего соседа, возвращает null и сохраняет текущий узел. |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | Перемещает к ближайшему видимому предку текущего узла и возвращает его. Если поиск parentNode пытается подняться выше корневого узла TreeWalker или не находит видимого предка, метод сохраняет текущую позицию и возвращает null. |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | Перемещает TreeWalker к предыдущему видимому узлу в порядке документа относительно текущего узла и возвращает новый узел. Если у текущего узла нет предыдущего узла или если поиск previousNode пытается подняться выше корневого узла TreeWalker, возвращает null и сохраняет текущий узел. |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | Перемещает TreeWalker к предыдущему соседнему узлу текущего узла и возвращает новый узел. Если у текущего узла нет видимого предыдущего соседнего узла, возвращает null и сохраняет текущий узел. |

### См. также

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
