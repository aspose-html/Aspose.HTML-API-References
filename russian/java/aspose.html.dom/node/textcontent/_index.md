---
title: "Node.TextContent"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство Node. Свойство textContent интерфейса Node представляет текстовое содержимое узла и его потомков"
type: docs

url: /ru/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

Свойство textContent интерфейса [`Node`](../) представляет текстовое содержимое узла и его потомков.

```java
public String TextContent { get; set; }
```

### Property Value

Строка или null. Ее значение зависит от ситуации:

Если узел является документом или типом документа, textContent возвращает null. Примечание: Чтобы получить весь текст и данные CDATA для всего документа, используйте document.documentElement.textContent. Если узел представляет собой секцию CDATA, комментарий, инструкцию обработки или текстовый узел, textContent возвращает или задает текст внутри узла, то есть [`Node.nodeValue`](../nodevalue/). Для других типов узлов textContent возвращает конкатенацию textContent всех дочерних узлов, исключая комментарии и инструкции обработки.

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### См. также

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
