---
title: "Node.Normalize"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Node. Перемещает все узлы Text на полную глубину поддерева под этим Node, включая узлы атрибутов, в нормальную форму, где только структура, например элементы, комментарии, инструкции обработки, секции CDATA и ссылки на сущности, разделяют узлы Text, т. е. нет соседних узлов Text и нет пустых узлов Text. Это может использоваться для обеспечения того, что представление DOM документа совпадает с тем, как оно выглядело бы после сохранения и повторной загрузки, и полезно, когда операции, такие как поиск XPointer, зависят от определённой структуры дерева документа. Если параметр normalize-characters объекта DOMConfiguration, привязанного к Node.ownerDocument, установлен в true, этот метод также полностью нормализует символы узлов Text."
type: docs

url: /ru/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

Перемещает все узлы [`Text`](../../text/) на полную глубину поддерева под этим Node, включая узлы атрибутов, в "нормальную" форму, где только структура (например, [`elements`](../../element/), [`comments`](../../comment/), [`processing instructions`](../../processinginstruction/), [`CDATA sections`](../../cdatasection/), и [`entity references`](../../entityreference/)) разделяет узлы [`Text`](../../text/), т. е. нет соседних узлов Text и нет пустых узлов Text. Это может использоваться для обеспечения того, что представление DOM документа совпадает с тем, как оно выглядело бы после сохранения и повторной загрузки, и полезно, когда операции (например, поиск XPointer [XPointer]) зависят от определённой структуры дерева документа. Если параметр "normalize-characters" объекта [`DOMConfiguration`](../../../com.aspose.html/configuration/), привязанного к [`Node.ownerDocument`](../ownerdocument/), установлен в true, этот метод также полностью нормализует символы узлов Text.

```java
public void Normalize()
```

### См. также

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
