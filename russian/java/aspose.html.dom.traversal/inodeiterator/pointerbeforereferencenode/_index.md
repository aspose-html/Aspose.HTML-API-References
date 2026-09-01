---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство INodeIterator. Значение этого флага определяет, видимы ли дочерние узлы узлов ссылок сущностей для итератора. Если false, они и их потомки будут отклонены. Обратите внимание, что это отклонение имеет приоритет над whatToShow и фильтром. Также обратите внимание, что в настоящее время это единственная ситуация, когда NodeIterators могут отклонять целое поддерево, а не пропускать отдельные узлы. Чтобы получить представление документа с развернутыми ссылками сущностей и не показывать сам узел ссылки сущности, используйте флаги whatToShow, чтобы скрыть узел ссылки сущности, и установите expandEntityReferences в true при создании итератора. Чтобы получить представление документа с узлами ссылок сущностей без их развертывания, используйте флаги whatToShow, чтобы показать узел ссылки сущности, и установите expandEntityReferences в false."
type: docs

url: /ru/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

Значение этого флага определяет, видимы ли дочерние узлы узлов ссылок сущностей для итератора. Если false, они и их потомки будут отклонены. Обратите внимание, что это отклонение имеет приоритет над whatToShow и фильтром. Также обратите внимание, что в настоящее время это единственная ситуация, когда NodeIterators могут отклонять целое поддерево, а не пропускать отдельные узлы. Чтобы получить представление документа с развернутыми ссылками сущностей и не показывать сам узел ссылки сущности, используйте флаги whatToShow, чтобы скрыть узел ссылки сущности, и установите expandEntityReferences в true при создании итератора. Чтобы получить представление документа с узлами ссылок сущностей без их развертывания, используйте флаги whatToShow, чтобы показать узел ссылки сущности, и установите expandEntityReferences в false.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` если [expand entity references]; иначе, `false`.

### См. также

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
