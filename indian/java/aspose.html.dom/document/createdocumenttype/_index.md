---
title: "Document.CreateDocumentType"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Document मेथड। यह मेथड एक DocumentType ऑब्जेक्ट लौटाता है जिसे या तो दस्तावेज़ निर्माण के समय DOMImplementation.createDocument के साथ उपयोग किया जा सकता है या Node.insertBefore या Node.replaceChild जैसी विधियों के द्वारा दस्तावेज़ में डाला जा सकता है।"
type: docs

url: /hi/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

यह मेथड एक [`DocumentType`](../../documenttype/) ऑब्जेक्ट लौटाता है जिसे या तो दस्तावेज़ निर्माण के समय DOMImplementation.createDocument के साथ उपयोग किया जा सकता है या Node.insertBefore() या Node.replaceChild() जैसी विधियों के द्वारा दस्तावेज़ में डाला जा सकता है।

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| नाम | String | यह एक DOMString है जिसमें योग्य नाम होता है, जैसे svg:svg। |
| publicId | String | यह एक DOMString है जिसमें PUBLIC पहचानकर्ता होता है। |
| systemId | String | यह एक DOMString है जिसमें SYSTEM पहचानकर्ता होते हैं। |
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
