---
title: "Document.CreateDocumentType"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Document method. विधि एक DocumentType ऑब्जेक्ट लौटाती है जिसे दस्तावेज़ निर्माण के समय DOMImplementation.createDocument के साथ उपयोग किया जा सकता है या Node.insertBefore या Node.replaceChild जैसी विधियों के माध्यम से दस्तावेज़ में डाला जा सकता है।"
type: docs

url: /hi/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

विधि एक [`DocumentType`](../../documenttype/) ऑब्जेक्ट लौटाती है जिसे दस्तावेज़ निर्माण के समय DOMImplementation.createDocument के साथ उपयोग किया जा सकता है या Node.insertBefore() या Node.replaceChild() जैसी विधियों के माध्यम से दस्तावेज़ में डाला जा सकता है।

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | String | एक DOMString है जिसमें योग्य नाम शामिल है, जैसे svg:svg। |
| publicId | String | एक DOMString है जिसमें PUBLIC पहचानकर्ता शामिल है। |
| systemId | String | एक DOMString है जिसमें SYSTEM पहचानकर्ता शामिल हैं। |
| internalSubset | String | आंतरिक उपसमुच्चय। |

### रिटर्न वैल्यू

यह [`DocumentType`](../../documenttype/).

## उदाहरण

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### संबंधित देखें

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
