---
title: "ITreeWalker.CurrentNode"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство ITreeWalker. Узел, в котором TreeWalker в данный момент находится. Изменения в дереве DOM могут привести к тому, что текущий узел больше не будет принят связанным с TreeWalker фильтром. currentNode также может быть явно установлен на любой узел, независимо от того, находится ли он в поддереве, указанном корневым узлом, или будет принят фильтром и флагами whatToShow. Дальнейшее перемещение происходит относительно currentNode, даже если он не является частью текущего представления, путем применения фильтров в запрошенном направлении; если перемещение невозможно, currentNode не изменяется."
type: docs

url: /ru/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Узел, в котором TreeWalker в данный момент находится. Изменения в дереве DOM могут привести к тому, что текущий узел больше не будет принят связанным с TreeWalker фильтром. currentNode также может быть явно установлен на любой узел, независимо от того, находится ли он в поддереве, указанном корневым узлом, или будет принят фильтром и флагами whatToShow. Дальнейшее перемещение происходит относительно currentNode, даже если он не является частью текущего представления, путем применения фильтров в запрошенном направлении; если перемещение невозможно, currentNode не изменяется.

```java
public Node CurrentNode { get; set; }
```

### Property Value

Текущий узел.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Возникает, если попытаться установить currentNode в null. |

### См. также

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
