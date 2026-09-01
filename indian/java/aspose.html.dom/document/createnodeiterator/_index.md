---
title: "Document.CreateNodeIterator"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Document मेथड। निर्दिष्ट नोड पर मूलित उपवृक्ष के ऊपर एक नया NodeIterator बनाएं"
type: docs

url: /hi/java/com.aspose.html.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

निर्दिष्ट नोड पर मूलित उपवृक्ष के ऊपर एक नया NodeIterator बनाएं।

```java
public INodeIterator CreateNodeIterator(Node root)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| रूट | Node | नोड जिसे उसके बच्चों के साथ इटरेट किया जाएगा। इटरेटर प्रारंभ में इस नोड से ठीक पहले स्थित होता है। whatToShow फ़्लैग और फ़िल्टर, यदि कोई हो, इस स्थिति को सेट करते समय विचार नहीं किए जाते। रूट null नहीं होना चाहिए। |

### रिटर्न वैल्यू

नया निर्मित NodeIterator।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट null है तो उत्पन्न होता है। |

### संबंधित देखें

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

निर्दिष्ट नोड पर मूलित उपवृक्ष के ऊपर एक नया NodeIterator बनाएं।

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| रूट | Node | नोड जिसे उसके बच्चों के साथ इटरेट किया जाएगा। इटरेटर प्रारंभ में इस नोड से ठीक पहले स्थित होता है। whatToShow फ़्लैग और फ़िल्टर, यदि कोई हो, इस स्थिति को सेट करते समय विचार नहीं किए जाते। रूट null नहीं होना चाहिए। |
| whatToShow | Int64 | फ़्लैग यह निर्दिष्ट करता है कि इटरेटर द्वारा प्रस्तुत पेड़ के लॉजिकल व्यू में कौन से नोड प्रकार दिखाई दे सकते हैं। संभावित SHOW_ मानों के सेट के लिए NodeFilter का विवरण देखें। इन फ़्लैग को OR का उपयोग करके संयोजित किया जा सकता है। |

### रिटर्न वैल्यू

नया निर्मित NodeIterator।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट null है तो उत्पन्न होता है। |

### संबंधित देखें

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

निर्दिष्ट नोड पर मूलित उपवृक्ष के ऊपर एक नया NodeIterator बनाएं।

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| रूट | Node | नोड जिसे उसके बच्चों के साथ इटरेट किया जाएगा। इटरेटर प्रारंभ में इस नोड से ठीक पहले स्थित होता है। whatToShow फ़्लैग और फ़िल्टर, यदि कोई हो, इस स्थिति को सेट करते समय विचार नहीं किए जाते। रूट null नहीं होना चाहिए। |
| whatToShow | Int64 | फ़्लैग यह निर्दिष्ट करता है कि इटरेटर द्वारा प्रस्तुत पेड़ के लॉजिकल व्यू में कौन से नोड प्रकार दिखाई दे सकते हैं। संभावित SHOW_ मानों के सेट के लिए NodeFilter का विवरण देखें। इन फ़्लैग को OR का उपयोग करके संयोजित किया जा सकता है। |
| फ़िल्टर | INodeFilter | इस TreeWalker के साथ उपयोग किया जाने वाला NodeFilter, या कोई फ़िल्टर न होने को दर्शाने के लिए null। |

### रिटर्न वैल्यू

नया निर्मित NodeIterator।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट null है तो उत्पन्न होता है। |

### संबंधित देखें

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
