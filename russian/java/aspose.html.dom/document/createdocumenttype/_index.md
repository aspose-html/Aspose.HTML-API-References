---
title: "Document.CreateDocumentType"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Document. Этот метод возвращает объект DocumentType, который может быть использован с DOMImplementation.createDocument при создании документа или может быть помещён в документ с помощью методов, таких как Node.insertBefore и Node.replaceChild."
type: docs

url: /ru/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

Метод возвращает объект [`DocumentType`](../../documenttype/), который может быть использован с DOMImplementation.createDocument при создании документа или может быть помещён в документ с помощью методов, таких как Node.insertBefore() и Node.replaceChild().

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | String | Является DOMString, содержащей квалифицированное имя, например svg:svg. |
| publicId | String | Является DOMString, содержащей PUBLIC-идентификатор. |
| systemId | String | Является DOMString, содержащей SYSTEM-идентификаторы. |
| internalSubset | String | Внутреннее подмножество. |

### Возвращаемое значение

Элемент [`DocumentType`](../../documenttype/).

## Примеры

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### См. также

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
