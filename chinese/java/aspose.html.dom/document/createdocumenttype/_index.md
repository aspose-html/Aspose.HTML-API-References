---
title: "Document.CreateDocumentType"
second_title: "Aspose.HTML for Java API 参考"
description: "Document 方法。该方法返回一个 DocumentType 对象，该对象既可以在文档创建时与 DOMImplementation.createDocument 一起使用，也可以通过诸如 Node.insertBefore 或 Node.replaceChild 等方法放入文档中"
type: docs

url: /zh/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

该方法返回一个 [`DocumentType`](../../documenttype/) 对象，该对象既可以在文档创建时与 DOMImplementation.createDocument 一起使用，也可以通过诸如 Node.insertBefore() 或 Node.replaceChild() 等方法放入文档中。

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 是一个包含限定名称的 DOMString，例如 svg:svg。 |
| publicId | String | 是一个包含 PUBLIC 标识符的 DOMString。 |
| systemId | String | 是一个包含 SYSTEM 标识符的 DOMString。 |
| internalSubset | String | 内部子集。 |

### 返回值

该 [`DocumentType`](../../documenttype/)。

## 示例

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### 另请参见

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
