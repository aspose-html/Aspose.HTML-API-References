---
title: "INodeIterator интерфейс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.traversal.INodeIterator интерфейс. Итераторы используются для последовательного прохода по набору узлов, например набору узлов в NodeList, поддереву документа, управляемому определённым Node, результатам запроса или любому другому набору узлов. Набор узлов, по которым будет происходить итерация, определяется реализацией NodeIterator. DOM Level 2 определяет единственную реализацию NodeIterator для обхода поддерева документа в порядке документа. Экземпляры этих итераторов создаются вызовом DocumentTraversal.createNodeIterator."
type: docs

url: /ru/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Итераторы используются для последовательного прохода по набору узлов, например набору узлов в NodeList, поддереву документа, управляемому определённым Node, результатам запроса или любому другому набору узлов. Набор узлов для итерации определяется реализацией NodeIterator. DOM Level 2 определяет единую реализацию NodeIterator для обхода поддерева документа в порядке документа. Экземпляры этих итераторов создаются вызовом DocumentTraversal .createNodeIterator().

Смотрите также [Спецификация Traversal and Range уровня 2 модели объектного документа (DOM)](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) Значение этого флага определяет, видны ли дочерние узлы ссылок на сущности итератору. Если false, они и их потомки будут отклонены. Обратите внимание, что это отклонение имеет приоритет над whatToShow и фильтром. Также отметьте, что в настоящее время это единственная ситуация, когда NodeIterators могут отклонять целое поддерево, а не пропускать отдельные узлы. Чтобы получить представление документа с развернутыми ссылками на сущности и не показывать сам узел ссылки на сущность, используйте флаги whatToShow, чтобы скрыть узел ссылки на сущность, и установите expandEntityReferences в true при создании итератора. Чтобы получить представление документа с узлами ссылок на сущности без их развертывания, используйте флаги whatToShow, чтобы показать узел ссылки на сущность, и установите expandEntityReferences в false. |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) Текущий узел ссылки. |

## Методы

| Имя | Описание |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | Отсоединяет NodeIterator от набора, по которому он проходил, освобождая любые вычислительные ресурсы и переводя итератор в состояние INVALID. После вызова detach вызовы nextNode или previousNode вызовут исключение INVALID_STATE_ERR. |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | Возвращает следующий узел в наборе и перемещает позицию итератора вперёд в наборе. После создания NodeIterator первый вызов nextNode() возвращает первый узел в наборе. |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | Возвращает предыдущий узел в наборе и перемещает позицию NodeIterator назад в наборе. |

### См. также

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
