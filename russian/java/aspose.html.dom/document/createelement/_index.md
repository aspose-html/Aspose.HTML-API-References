---
title: "Document.CreateElement"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Document. В HTML‑документе метод document.createElement создает HTML‑элемент, указанный в tagName, или HTMLUnknownElement, если tagName не распознан."
type: docs

url: /ru/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

В HTML‑документе метод document.createElement() создает HTML‑элемент, указанный в tagName, или [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/), если tagName не распознан.

```java
public Element CreateElement(String localName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | String | Строка, указывающая тип создаваемого элемента. Свойство nodeName созданного элемента инициализируется значением tagName. Не используйте квалифицированные имена (например, "html:a") с этим методом. При вызове в HTML‑документе createElement() преобразует tagName в нижний регистр перед созданием элемента. |

### Возвращаемое значение

Новый [`Element`](../../element/).

## Примеры

```java
var element = document.CreateElement(tagName);
```

### См. также

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
