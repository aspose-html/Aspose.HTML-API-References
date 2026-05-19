---
title: "Document.CreateDocumentType"
second_title: "Aspose.HTML for Java API 참조"
description: "Document 메서드. 이 메서드는 DocumentType 객체를 반환하며, 이 객체는 문서 생성 시 DOMImplementation.createDocument와 함께 사용할 수 있거나 Node.insertBefore 또는 Node.replaceChild와 같은 메서드를 통해 문서에 삽입될 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

이 메서드는 [`DocumentType`](../../documenttype/) 객체를 반환하며, 이 객체는 문서 생성 시 DOMImplementation.createDocument와 함께 사용할 수 있거나 Node.insertBefore() 또는 Node.replaceChild()와 같은 메서드를 통해 문서에 삽입될 수 있습니다.

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | String | DOMString이며, svg:svg와 같은 정규화된 이름을 포함합니다. |
| publicId | String | PUBLIC 식별자를 포함하는 DOMString입니다. |
| systemId | String | SYSTEM 식별자를 포함하는 DOMString입니다. |
| internalSubset | String | 내부 서브셋. |

### 반환 값

다음 [`DocumentType`](../../documenttype/).

## 예제

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### 또 보기

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
