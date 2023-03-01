---
title: Document.CreateTreeWalker
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Document तरक. नर्दष्ट नड पर रूट कए गए सबट्र पर एक नय ट्रवकर बनएं
type: docs
weight: 940
url: /hi/net/aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

निर्दिष्ट नोड पर रूट किए गए सबट्री पर एक नया ट्रीवॉकर बनाएं।

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| root | Node | नोड जो ट्रीवॉकर के लिए रूट के रूप में काम करेगा। इस मान को सेट करते समय whatToShow फ़्लैग और NodeFilter पर विचार नहीं किया जाता; किसी भी नोड प्रकार को रूट के रूप में स्वीकार किया जाएगा। TreeWalker का the currentNode is इस नोड के लिए प्रारंभ किया गया है, चाहे वह दृश्यमान हो या नहीं। The रूट ट्रैवर्सल विधियों के लिए एक रोक बिंदु के रूप में कार्य करता है जो दस्तावेज़ संरचना में ऊपर की ओर देखते हैं, जैसे पेरेंटनोड और नेक्स्टनोड। मूल शून्य नहीं होना चाहिए। |

### प्रतिलाभ की मात्रा

नव निर्मित ट्रीवॉकर।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट is null है तो उठाया गया। |

### यह सभी देखें

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* नाम स्थान [Aspose.Html.Dom](../../document/)
* सभा [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

निर्दिष्ट नोड पर रूट किए गए सबट्री पर एक नया ट्रीवॉकर बनाएं।

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| root | Node | नोड जो ट्रीवॉकर के लिए रूट के रूप में काम करेगा। इस मान को सेट करते समय whatToShow फ़्लैग और NodeFilter पर विचार नहीं किया जाता; किसी भी नोड प्रकार को रूट के रूप में स्वीकार किया जाएगा। TreeWalker का the currentNode is इस नोड के लिए प्रारंभ किया गया है, चाहे वह दृश्यमान हो या नहीं। The रूट ट्रैवर्सल विधियों के लिए एक रोक बिंदु के रूप में कार्य करता है जो दस्तावेज़ संरचना में ऊपर की ओर देखते हैं, जैसे पेरेंटनोड और नेक्स्टनोड। मूल शून्य नहीं होना चाहिए। |
| whatToShow | Int64 | फ़्लैग निर्दिष्ट करता है कि ट्री-वॉकर द्वारा प्रस्तुत ट्री के तार्किक दृश्य में कौन से नोड प्रकार दिखाई दे सकते हैं। संभव SHOW_ मानों के सेट के लिए NodeFilter का विवरण देखें। इन झंडों को OR का उपयोग करके जोड़ा जा सकता है। |

### प्रतिलाभ की मात्रा

नव निर्मित ट्रीवॉकर।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट is null है तो उठाया गया। |

### यह सभी देखें

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* नाम स्थान [Aspose.Html.Dom](../../document/)
* सभा [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

निर्दिष्ट नोड पर रूट किए गए सबट्री पर एक नया ट्रीवॉकर बनाएं।

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| root | Node | नोड जो ट्रीवॉकर के लिए रूट के रूप में काम करेगा। इस मान को सेट करते समय whatToShow फ़्लैग और NodeFilter पर विचार नहीं किया जाता; किसी भी नोड प्रकार को रूट के रूप में स्वीकार किया जाएगा। TreeWalker का the currentNode is इस नोड के लिए प्रारंभ किया गया है, चाहे वह दृश्यमान हो या नहीं। The रूट ट्रैवर्सल विधियों के लिए एक रोक बिंदु के रूप में कार्य करता है जो दस्तावेज़ संरचना में ऊपर की ओर देखते हैं, जैसे पेरेंटनोड और नेक्स्टनोड। मूल शून्य नहीं होना चाहिए। |
| whatToShow | Int64 | फ़्लैग निर्दिष्ट करता है कि ट्री-वॉकर द्वारा प्रस्तुत ट्री के तार्किक दृश्य में कौन से नोड प्रकार दिखाई दे सकते हैं। संभव SHOW_ मानों के सेट के लिए NodeFilter का विवरण देखें। इन झंडों को OR का उपयोग करके जोड़ा जा सकता है। |
| filter | INodeFilter | NodeFilter का उपयोग this TreeWalker के साथ किया जाना चाहिए, या फ़िल्टर न होने का संकेत देने के लिए शून्य। |

### प्रतिलाभ की मात्रा

नव निर्मित ट्रीवॉकर।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट is null है तो उठाया गया। |

### यह सभी देखें

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* नाम स्थान [Aspose.Html.Dom](../../document/)
* सभा [Aspose.HTML](../../../)


