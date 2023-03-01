---
title: IDocumentTraversal.CreateNodeIterator
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: IDocumentTraversal तरक. नर्दष्ट नड पर रूट कए गए सबट्र पर एक नय नडइटरेटर बनएं
type: docs
weight: 10
url: /hi/net/aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

निर्दिष्ट नोड पर रूट किए गए सबट्री पर एक नया नोडइटरेटर बनाएं।

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| root | Node | नोड जो अपने बच्चों के साथ एक साथ पुनरावृत्त किया जाएगा। इटरेटर शुरू में इस नोड से ठीक पहले स्थित है। इस स्थिति को सेट करते समय the whatToShow फ़्लैग और फ़िल्टर, यदि कोई हो, पर विचार नहीं किया जाता है। रूट नल नहीं होना चाहिए। |

### प्रतिलाभ की मात्रा

नव निर्मित NodeIterator.

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट is null है तो उठाया गया। |

### यह सभी देखें

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* नाम स्थान [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* सभा [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

निर्दिष्ट नोड पर रूट किए गए सबट्री पर एक नया नोडइटरेटर बनाएं।

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| root | Node | नोड जो अपने बच्चों के साथ एक साथ पुनरावृत्त किया जाएगा। इटरेटर शुरू में इस नोड से ठीक पहले स्थित है। इस स्थिति को सेट करते समय the whatToShow फ़्लैग और फ़िल्टर, यदि कोई हो, पर विचार नहीं किया जाता है। रूट नल नहीं होना चाहिए। |
| whatToShow | Int64 | फ़्लैग निर्दिष्ट करता है कि कौन से नोड प्रकार में पुनरावर्तक द्वारा प्रस्तुत पेड़ के तार्किक दृश्य में दिखाई दे सकते हैं। संभव SHOW_ मानों के सेट के लिए NodeFilter का विवरण देखें। इन झंडों को या का उपयोग करके जोड़ा जा सकता है। |

### प्रतिलाभ की मात्रा

नव निर्मित NodeIterator.

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट is null है तो उठाया गया। |

### यह सभी देखें

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* नाम स्थान [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* सभा [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

निर्दिष्ट नोड पर रूट किए गए सबट्री पर एक नया नोडइटरेटर बनाएं।

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| root | Node | नोड जो अपने बच्चों के साथ एक साथ पुनरावृत्त किया जाएगा। इटरेटर शुरू में इस नोड से ठीक पहले स्थित है। इस स्थिति को सेट करते समय the whatToShow फ़्लैग और फ़िल्टर, यदि कोई हो, पर विचार नहीं किया जाता है। रूट नल नहीं होना चाहिए। |
| whatToShow | Int64 | फ़्लैग निर्दिष्ट करता है कि कौन से नोड प्रकार में पुनरावर्तक द्वारा प्रस्तुत पेड़ के तार्किक दृश्य में दिखाई दे सकते हैं। संभव SHOW_ मानों के सेट के लिए NodeFilter का विवरण देखें। इन झंडों को या का उपयोग करके जोड़ा जा सकता है। |
| filter | INodeFilter | NodeFilter का उपयोग this TreeWalker के साथ किया जाना चाहिए, या फ़िल्टर न होने का संकेत देने के लिए शून्य। |

### प्रतिलाभ की मात्रा

नव निर्मित NodeIterator.

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: यदि निर्दिष्ट रूट is null है तो उठाया गया। |

### यह सभी देखें

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* नाम स्थान [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* सभा [Aspose.HTML](../../../)


