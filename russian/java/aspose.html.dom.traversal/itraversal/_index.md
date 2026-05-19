---
title: "Интерфейс ITraversal"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.dom.traversal.ITraversal. Итераторы используются для последовательного прохода по набору узлов, например, по набору узлов в NodeList, по поддереву документа, управляемому определённым Node, по результатам запроса или любому другому набору узлов. Набор узлов для итерации определяется реализацией NodeIterator. DOM Level 2 определяет единую реализацию NodeIterator для обхода поддерева документа в порядке документа. Экземпляры этих итераторов создаются вызовом DocumentTraversal .createNodeIterator."
type: docs

url: /ru/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Итераторы используются для последовательного прохода по набору узлов, например набору узлов в NodeList, поддереву документа, управляемому определённым Node, результатам запроса или любому другому набору узлов. Набор узлов для итерации определяется реализацией NodeIterator. DOM Level 2 определяет единую реализацию NodeIterator для обхода поддерева документа в порядке документа. Экземпляры этих итераторов создаются вызовом DocumentTraversal .createNodeIterator().

Смотрите также [Спецификация Traversal and Range уровня 2 модели объектного документа (DOM)](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) NodeFilter, используемый для фильтрации узлов. |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) Корневой узел NodeIterator, указанный при его создании. |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) Этот атрибут определяет, какие типы узлов представлены через итератор. Доступный набор констант определён в интерфейсе NodeFilter. Узлы, не принятые whatToShow, будут пропущены, но их дочерние узлы могут всё ещё учитываться. Обратите внимание, что это пропуск имеет приоритет над фильтром, если он присутствует. |

### См. также

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
