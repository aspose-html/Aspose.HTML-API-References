---
title: "IDocumentTraversal इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.traversal.IDocumentTraversal इंटरफ़ेस। DocumentTraversal में ऐसे मेथड होते हैं जो इटरेटर और ट्री‑वॉकर बनाते हैं ताकि एक नोड और उसके बच्चों को दस्तावेज़ क्रम में गहराई‑पहले प्री‑ऑर्डर ट्रैवर्सल के साथ पार किया जा सके, जो दस्तावेज़ के टेक्स्ट प्रतिनिधित्व में प्रारंभिक टैगों के क्रम के समान होता है। उन DOM में जो Traversal सुविधा का समर्थन करते हैं, DocumentTraversal को वही ऑब्जेक्ट्स लागू करेंगे जो Document इंटरफ़ेस को लागू करते हैं।"
type: docs

url: /hi/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal में ऐसी विधियाँ हैं जो इटरेटर और ट्री-वॉकर बनाती हैं ताकि एक नोड और उसके बच्चों को दस्तावेज़ क्रम में (गहराई‑पहले, प्री‑ऑर्डर ट्रैवर्सल, जो दस्तावेज़ के टेक्स्ट प्रतिनिधित्व में प्रारंभिक टैगों के क्रम के बराबर है) पार किया जा सके। उन DOM में जो Traversal फीचर का समर्थन करते हैं, DocumentTraversal को वही ऑब्जेक्ट्स लागू करेंगे जो Document इंटरफ़ेस को लागू करते हैं।

इसके अलावा देखें [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)। @since DOM Level 2

```java
public interface IDocumentTraversal
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया NodeIterator बनाएं। |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया NodeIterator बनाएं। |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया NodeIterator बनाएं। |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया TreeWalker बनाएं। |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया TreeWalker बनाएं। |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया TreeWalker बनाएं। |

### संबंधित देखें

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
