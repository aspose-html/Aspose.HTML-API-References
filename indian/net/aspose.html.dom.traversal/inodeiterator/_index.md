---
title: Interface INodeIterator
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Traversal.INodeIterator इंटरफेस. Iterators क उपयग नड्स के एक सेट के मध्यम से कदम उठने के लए कय जत है उदहरण के लए नडलस्ट में नड्स क सेट द्वर नयंत्रत दस्तवेज़ सबट्र एक वशेष नड एक क्वेर के परणम य कस अन्य सेट नड्स क पुनरवृत्त कए जने वले नड्स क सेट NodeIterator के कर्यन्वयन द्वर नर्धरत कय जत है DOM लेवल 2 दस्तवेज़ सबट्र के दस्तवेज़ऑर्डर ट्रैवर्सल के लए एक संगल नडइटरेटर कर्यन्वयन नर्दष्ट करत है DocumentTraversal .createNodeIterator. क कल करके इन पुनरवृत्तयं के उदहरण बनए जते हैं
type: docs
weight: 2500
url: /hi/net/aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iterators का उपयोग नोड्स के एक सेट के माध्यम से कदम उठाने के लिए किया जाता है, उदाहरण के लिए नोडलिस्ट में नोड्स का सेट, द्वारा नियंत्रित दस्तावेज़ सबट्री एक विशेष नोड, एक क्वेरी के परिणाम, या किसी अन्य सेट नोड्स का। पुनरावृत्त किए जाने वाले नोड्स का सेट NodeIterator के कार्यान्वयन द्वारा निर्धारित किया जाता है। DOM लेवल 2 दस्तावेज़ सबट्री के दस्तावेज़-ऑर्डर ट्रैवर्सल के लिए एक सिंगल नोडइटरेटर कार्यान्वयन निर्दिष्ट करता है। DocumentTraversal .createNodeIterator(). को कॉल करके इन पुनरावृत्तियों के उदाहरण बनाए जाते हैं

यह भी देखें[दस्तावेज़ ऑब्जेक्ट मॉडल (DOM) स्तर 2 ट्रैवर्सल और रेंज विशिष्टता](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @DOM लेवल 2 के बाद से

```csharp
public interface INodeIterator : ITraversal
```

## गुण

| नाम | विवरण |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | इस ध्वज का मान निर्धारित करता है कि क्या entity संदर्भ नोड के बच्चे पुनरावर्तक को दिखाई दे रहे हैं। अगर झूठा है, तो वे और उनके वंशज खारिज कर दिए जाएंगे। ध्यान दें कि यह अस्वीकृति whatToShow और फ़िल्टर पर पूर्वता लेती है। साथ ही ध्यान दें कि यह वर्तमान में एकमात्र ऐसी स्थिति है जहां नोडइटरेटर अलग-अलग नोड्स को छोड़कर के बजाय एक पूर्ण उपट्री को अस्वीकार कर सकते हैं। the iterator बनाते समय इकाई संदर्भ node को छुपाएं और विस्तृत EntityReferences को सही पर सेट करें। उस दस्तावेज़ का एक दृश्य बनाने के लिए जिसमें इकाई संदर्भ नोड है, लेकिन कोई इकाई विस्तार नहीं है, इकाई संदर्भ नोड दिखाने के लिए whatToShow फ़्लैग का उपयोग करें और गलत पर सेट विस्तृत EntityReferences का उपयोग करें। |
| [ReferenceNode](../../aspose.html.dom.traversal/inodeiterator/referencenode/) { get; } | वर्तमान संदर्भ नोड. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Detach](../../aspose.html.dom.traversal/inodeiterator/detach/)() | NodeIterator को उस सेट से अलग करता है जिसे इसने ओवर किया, किसी भी कम्प्यूटेशनल संसाधनों को जारी किया और iterator को INVALID स्थिति में रखा। डिटैच होने के बाद, नेक्स्टनोड या पिछलेनोड को कॉल करेगा अपवाद INVALID_STATE_ERR. बढ़ा देगा |
| [NextNode](../../aspose.html.dom.traversal/inodeiterator/nextnode/)() | सेट में अगला नोड लौटाता है और सेट में इटरेटर की स्थिति को आगे बढ़ाता है। NodeIterator बनने के बाद, नेक्स्टनोड () के लिए पहला कॉल सेट में पहला नोड लौटाता है। |
| [PreviousNode](../../aspose.html.dom.traversal/inodeiterator/previousnode/)() | सेट में पिछला नोड लौटाता है और सेट में NodeIterator की स्थिति को पीछे की ओर ले जाता है। |

### यह सभी देखें

* interface [ITraversal](../itraversal/)
* नाम स्थान [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* सभा [Aspose.HTML](../../)


