---
title: Interface ICSSStyleDeclaration
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration इंटरफेस. CSSStyleDeclaration इंटरफ़ेस एकल CSS घषण ब्लक क प्रतनधत्व करत है इस इंटरफ़ेस क उपयग कस ब्लक में वर्तमन में सेट क गई शैल के गुणं क नर्धरत करने य ब्लक के भतर स्पष्ट रूप से शैल के गुणं क सेट करने के लए कय ज सकत है
type: docs
weight: 490
url: /hi/net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration इंटरफ़ेस एकल CSS घोषणा ब्लॉक का प्रतिनिधित्व करता है। इस इंटरफ़ेस का उपयोग किसी ब्लॉक में वर्तमान में सेट की गई शैली के गुणों को निर्धारित करने या ब्लॉक के भीतर स्पष्ट रूप से शैली के गुणों को सेट करने के लिए किया जा सकता है।

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | डिक्लेरेशन ब्लॉक (आसपास के घुंघराले ब्रेसिज़ को छोड़कर) का पार्स करने योग्य टेक्स्टुअल प्रतिनिधित्व। इस एट्रिब्यूट को सेट करने से नए मान की पार्सिंग और डिक्लेरेशन ब्लॉक में सभी संपत्तियों को हटाने या जोड़ने सहित रीसेट करने का परिणाम होगा। |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | उन गुणों को पुनः प्राप्त करने के लिए उपयोग किया जाता है जिन्हें इस घोषणा ब्लॉक में स्पष्ट रूप से सेट किया गया है। इस पद्धति का उपयोग करके प्राप्त गुणों के क्रम को वह क्रम नहीं होना चाहिए जिसमें वे सेट किए गए थे। इस विधि का उपयोग इस घोषणा ब्लॉक में सभी संपत्तियों पर पुनरावृति करने के लिए किया जा सकता है। |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | इस घोषणा ब्लॉक में स्पष्ट रूप से सेट की गई संपत्तियों की संख्या। मान्य सूचकांकों की सीमा 0 से लेकर लंबाई-1 सहित है। |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | सीएसएस नियम जिसमें यह घोषणा ब्लॉक या शून्य है यदि यह CSSStyleDeclaration CSSRule. से जुड़ा नहीं है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | सीएसएस संपत्ति के मूल्य के वस्तु प्रतिनिधित्व को पुनः प्राप्त करने के लिए उपयोग किया जाता है अगर इसे इस घोषणा ब्लॉक के भीतर स्पष्ट रूप से सेट किया गया हो। यदि संपत्ति शॉर्टहैंड संपत्ति है तो यह विधि शून्य हो जाती है। आशुलिपि संपत्ति मूल्यों को केवल getPropertyValue और setProperty विधियों का उपयोग करके स्ट्रिंग्स के रूप में एक्सेस और संशोधित किया जा सकता है। |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(string) | सीएसएस संपत्ति की प्राथमिकता को पुनः प्राप्त करने के लिए उपयोग किया जाता है (उदाहरण के लिए "महत्वपूर्ण" योग्यता) अगर संपत्ति को स्पष्ट रूप से इस घोषणा ब्लॉक में सेट किया गया है। |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | एक सीएसएस संपत्ति के मूल्य को पुनः प्राप्त करने के लिए उपयोग किया जाता है अगर इसे इस घोषणा ब्लॉक के भीतर स्पष्ट रूप से सेट किया गया हो। |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(string) | एक सीएसएस संपत्ति को हटाने के लिए प्रयुक्त होता है अगर इसे स्पष्ट रूप से इस घोषणा ब्लॉक के भीतर सेट किया गया हो। |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | इस घोषणा ब्लॉक के भीतर डिफ़ॉल्ट प्राथमिकता के साथ एक संपत्ति मूल्य सेट करने के लिए उपयोग किया जाता है। डिफ़ॉल्ट प्राथमिकता "महत्वपूर्ण" नहीं है यानी String.Empty |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | इस घोषणा ब्लॉक के भीतर संपत्ति मूल्य और प्राथमिकता निर्धारित करने के लिए उपयोग किया जाता है। |

### यह सभी देखें

* interface [ICSS2Properties](../icss2properties/)
* नाम स्थान [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* सभा [Aspose.HTML](../../)


