---
title: "IStyleSheet.OwnerNode"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство IStyleSheet. Узел, связывающий эту таблицу стилей с документом. Для HTML это может быть соответствующий элемент LINK или STYLE. Для XML это может быть инструкция обработки ссылки. Для таблиц стилей, включаемых другими таблицами стилей, значение этого атрибута равно null."
type: docs

url: /ru/java/com.aspose.html.dom.css/istylesheet/ownernode/
---
## IStyleSheet.OwnerNode property

Узел, связывающий эту таблицу стилей с документом. Для HTML это может быть соответствующий элемент LINK или STYLE. Для XML это может быть инструкция обработки ссылки. Для таблиц стилей, включаемых другими таблицами стилей, значение этого атрибута равно null.

```java
public Node OwnerNode { get; }
```

### Property Value

Атрибут ownerNode должен возвращать узел‑владельца.

## Примечания

Для таблиц стилей, включаемых другими таблицами стилей, например с помощью @import, значение этого свойства равно null.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-ownernode](https://drafts.csswg.org/cssom/#dom-stylesheet-ownernode) – The CSSOM definition.

### См. также

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
