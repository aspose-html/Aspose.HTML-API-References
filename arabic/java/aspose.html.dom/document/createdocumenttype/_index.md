---
title: "Document.CreateDocumentType"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Document. تُعيد الطريقة كائن DocumentType يمكن إما استخدامه مع DOMImplementation.createDocument عند إنشاء المستند أو يمكن وضعه في المستند عبر طرق مثل Node.insertBefore أو Node.replaceChild"
type: docs

url: /ar/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

تُعيد الطريقة كائنًا [`DocumentType`](../../documenttype/) يمكن إما استخدامه مع DOMImplementation.createDocument عند إنشاء المستند أو يمكن وضعه في المستند عبر طرق مثل Node.insertBefore() أو Node.replaceChild().

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | String | هي DOMString تحتوي على الاسم المؤهل، مثل svg:svg. |
| publicId | String | هي DOMString تحتوي على المعرف PUBLIC. |
| systemId | String | هي DOMString تحتوي على المعرفات SYSTEM. |
| internalSubset | String | المجموعة الداخلية. |

### قيمة الإرجاع

الـ [`DocumentType`](../../documenttype/).

## أمثلة

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### انظر أيضًا

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
