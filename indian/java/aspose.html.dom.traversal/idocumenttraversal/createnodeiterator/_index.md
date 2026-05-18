---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "IDocumentTraversal मेथड। निर्दिष्ट नोड को मूल बनाकर उपवृक्ष पर एक नया NodeIterator बनाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया NodeIterator बनाएं।

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| रूट | Node | नोड जिसे उसके बच्चों के साथ इटरेट किया जाएगा। इटरेटर प्रारंभ में इस नोड से ठीक पहले स्थित होता है। whatToShow फ़्लैग और फ़िल्टर, यदि कोई हो, इस स्थिति को सेट करते समय विचार नहीं किए जाते। रूट null नहीं होना चाहिए। |

### रिटर्न वैल्यू

नया बनाया गया NodeIterator।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट null है तो उत्पन्न होता है। |

### संबंधित देखें

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया NodeIterator बनाएं।

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| रूट | Node | नोड जिसे उसके बच्चों के साथ इटरेट किया जाएगा। इटरेटर प्रारंभ में इस नोड से ठीक पहले स्थित होता है। whatToShow फ़्लैग और फ़िल्टर, यदि कोई हो, इस स्थिति को सेट करते समय विचार नहीं किए जाते। रूट null नहीं होना चाहिए। |
| whatToShow | Int64 | फ़्लैग यह निर्दिष्ट करता है कि इटरेटर द्वारा प्रस्तुत पेड़ के तार्किक दृश्य में कौन से नोड प्रकार दिखाई दे सकते हैं। संभावित SHOW_ मानों के सेट के लिए NodeFilter का विवरण देखें। इन फ़्लैग को OR का उपयोग करके संयोजित किया जा सकता है। |

### रिटर्न वैल्यू

नया बनाया गया NodeIterator।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट null है तो उत्पन्न होता है। |

### संबंधित देखें

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया NodeIterator बनाएं।

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| रूट | Node | नोड जिसे उसके बच्चों के साथ इटरेट किया जाएगा। इटरेटर प्रारंभ में इस नोड से ठीक पहले स्थित होता है। whatToShow फ़्लैग और फ़िल्टर, यदि कोई हो, इस स्थिति को सेट करते समय विचार नहीं किए जाते। रूट null नहीं होना चाहिए। |
| whatToShow | Int64 | फ़्लैग यह निर्दिष्ट करता है कि इटरेटर द्वारा प्रस्तुत पेड़ के तार्किक दृश्य में कौन से नोड प्रकार दिखाई दे सकते हैं। संभावित SHOW_ मानों के सेट के लिए NodeFilter का विवरण देखें। इन फ़्लैग को OR का उपयोग करके संयोजित किया जा सकता है। |
| फ़िल्टर | INodeFilter | इस TreeWalker के साथ उपयोग किया जाने वाला NodeFilter, या कोई फ़िल्टर न होने के संकेत के लिए null। |

### रिटर्न वैल्यू

नया बनाया गया NodeIterator।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट null है तो उत्पन्न होता है। |

### संबंधित देखें

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
