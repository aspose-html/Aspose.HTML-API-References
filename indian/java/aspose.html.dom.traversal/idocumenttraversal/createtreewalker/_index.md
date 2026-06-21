---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "IDocumentTraversal मेथड। निर्दिष्ट नोड को रूट बनाकर उपवृक्ष पर एक नया TreeWalker बनाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

निर्दिष्ट नोड पर मूलित उपवृक्ष के ऊपर एक नया TreeWalker बनाएं।

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| रूट | Node | नोड जो TreeWalker के लिए रूट के रूप में कार्य करेगा। इस मान को सेट करते समय whatToShow फ़्लैग और NodeFilter पर विचार नहीं किया जाता; किसी भी नोड प्रकार को रूट के रूप में स्वीकार किया जाएगा। TreeWalker का currentNode इस नोड पर आरंभ किया जाता है, चाहे वह दृश्यमान हो या न हो। रूट दस्तावेज़ संरचना में ऊपर की ओर देखती traversal मेथड्स जैसे parentNode और nextNode के लिए एक रोक बिंदु के रूप में कार्य करता है। रूट null नहीं होना चाहिए। |

### रिटर्न वैल्यू

नया निर्मित TreeWalker।

### संबंधित देखें

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

निर्दिष्ट नोड पर मूलित उपवृक्ष के ऊपर एक नया TreeWalker बनाएं।

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| रूट | Node | नोड जो TreeWalker के लिए रूट के रूप में कार्य करेगा। इस मान को सेट करते समय whatToShow फ़्लैग और NodeFilter पर विचार नहीं किया जाता; किसी भी नोड प्रकार को रूट के रूप में स्वीकार किया जाएगा। TreeWalker का currentNode इस नोड पर आरंभ किया जाता है, चाहे वह दृश्यमान हो या न हो। रूट दस्तावेज़ संरचना में ऊपर की ओर देखती traversal मेथड्स जैसे parentNode और nextNode के लिए एक रोक बिंदु के रूप में कार्य करता है। रूट null नहीं होना चाहिए। |
| whatToShow | Int64 | फ़्लैग यह निर्दिष्ट करता है कि कौन से नोड प्रकार ट्री-वाल्कर द्वारा प्रस्तुत पेड़ के तर्कसंगत दृश्य में दिखाई दे सकते हैं। संभावित SHOW_ मानों के सेट के लिए NodeFilter का विवरण देखें। इन फ़्लैगों को OR का उपयोग करके संयोजित किया जा सकता है। |

### रिटर्न वैल्यू

नया निर्मित TreeWalker।

### संबंधित देखें

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

निर्दिष्ट नोड पर मूलित उपवृक्ष के ऊपर एक नया TreeWalker बनाएं।

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| रूट | Node | नोड जो TreeWalker के लिए रूट के रूप में कार्य करेगा। इस मान को सेट करते समय whatToShow फ़्लैग और NodeFilter पर विचार नहीं किया जाता; किसी भी नोड प्रकार को रूट के रूप में स्वीकार किया जाएगा। TreeWalker का currentNode इस नोड पर आरंभ किया जाता है, चाहे वह दृश्यमान हो या न हो। रूट दस्तावेज़ संरचना में ऊपर की ओर देखती traversal मेथड्स जैसे parentNode और nextNode के लिए एक रोक बिंदु के रूप में कार्य करता है। रूट null नहीं होना चाहिए। |
| whatToShow | Int64 | फ़्लैग यह निर्दिष्ट करता है कि कौन से नोड प्रकार ट्री-वाल्कर द्वारा प्रस्तुत पेड़ के तर्कसंगत दृश्य में दिखाई दे सकते हैं। संभावित SHOW_ मानों के सेट के लिए NodeFilter का विवरण देखें। इन फ़्लैगों को OR का उपयोग करके संयोजित किया जा सकता है। |
| फ़िल्टर | INodeFilter | इस TreeWalker के साथ उपयोग किया जाने वाला NodeFilter, या कोई फ़िल्टर न होने को दर्शाने के लिए null। |

### रिटर्न वैल्यू

नया निर्मित TreeWalker।

### संबंधित देखें

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
