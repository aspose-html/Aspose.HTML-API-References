---
title: "Document.CreateTreeWalker"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Document मेथड। निर्दिष्ट नोड पर मूलित सबट्री के ऊपर एक नया TreeWalker बनाता है"
type: docs

url: /hi/java/com.aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया TreeWalker बनाएं।

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| रूट | Node | नोड जो TreeWalker के रूट के रूप में कार्य करेगा। इस मान को सेट करते समय whatToShow फ़्लैग और NodeFilter पर विचार नहीं किया जाता; किसी भी नोड प्रकार को रूट के रूप में स्वीकार किया जाएगा। TreeWalker का currentNode इस नोड पर प्रारंभ किया जाता है, चाहे वह दृश्यमान हो या न हो। रूट दस्तावेज़ संरचना में ऊपर की ओर देखती traversal मेथड्स जैसे parentNode और nextNode के लिए एक रोक बिंदु के रूप में कार्य करता है। रूट null नहीं होना चाहिए। |

### रिटर्न वैल्यू

नया बनाया गया TreeWalker।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट null है तो उत्पन्न होता है। |

### संबंधित देखें

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया TreeWalker बनाएं।

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| रूट | Node | नोड जो TreeWalker के रूट के रूप में कार्य करेगा। इस मान को सेट करते समय whatToShow फ़्लैग और NodeFilter पर विचार नहीं किया जाता; किसी भी नोड प्रकार को रूट के रूप में स्वीकार किया जाएगा। TreeWalker का currentNode इस नोड पर प्रारंभ किया जाता है, चाहे वह दृश्यमान हो या न हो। रूट दस्तावेज़ संरचना में ऊपर की ओर देखती traversal मेथड्स जैसे parentNode और nextNode के लिए एक रोक बिंदु के रूप में कार्य करता है। रूट null नहीं होना चाहिए। |
| whatToShow | Int64 | फ़्लैग निर्दिष्ट करता है कि कौन से नोड प्रकार लॉजिकल व्यू में दिखाई दे सकते हैं जो ट्री‑वॉकर द्वारा प्रस्तुत ट्री में हैं। संभावित SHOW_ मानों के सेट के लिए NodeFilter का विवरण देखें। इन फ़्लैग को OR का उपयोग करके संयोजित किया जा सकता है। |

### रिटर्न वैल्यू

नया बनाया गया TreeWalker।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट null है तो उत्पन्न होता है। |

### संबंधित देखें

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया TreeWalker बनाएं।

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| रूट | Node | नोड जो TreeWalker के रूट के रूप में कार्य करेगा। इस मान को सेट करते समय whatToShow फ़्लैग और NodeFilter पर विचार नहीं किया जाता; किसी भी नोड प्रकार को रूट के रूप में स्वीकार किया जाएगा। TreeWalker का currentNode इस नोड पर प्रारंभ किया जाता है, चाहे वह दृश्यमान हो या न हो। रूट दस्तावेज़ संरचना में ऊपर की ओर देखती traversal मेथड्स जैसे parentNode और nextNode के लिए एक रोक बिंदु के रूप में कार्य करता है। रूट null नहीं होना चाहिए। |
| whatToShow | Int64 | फ़्लैग निर्दिष्ट करता है कि कौन से नोड प्रकार लॉजिकल व्यू में दिखाई दे सकते हैं जो ट्री‑वॉकर द्वारा प्रस्तुत ट्री में हैं। संभावित SHOW_ मानों के सेट के लिए NodeFilter का विवरण देखें। इन फ़्लैग को OR का उपयोग करके संयोजित किया जा सकता है। |
| फ़िल्टर | INodeFilter | इस TreeWalker के साथ उपयोग किया जाने वाला NodeFilter, या कोई फ़िल्टर न होने के संकेत के लिए null। |

### रिटर्न वैल्यू

नया बनाया गया TreeWalker।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट null है तो उत्पन्न होता है। |

### संबंधित देखें

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
