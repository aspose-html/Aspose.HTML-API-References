---
title: "IXPathResult इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.xpath.IXPathResult इंटरफ़ेस। XPathResult इंटरफ़ेस एक विशिष्ट नोड के संदर्भ में XPath 1.0 अभिव्यक्ति के मूल्यांकन के परिणाम का प्रतिनिधित्व करता है। चूँकि XPath अभिव्यक्ति का मूल्यांकन विभिन्न परिणाम प्रकारों में हो सकता है, यह ऑब्जेक्ट परिणाम के प्रकार और मान को खोजने और संशोधित करने की सुविधा देता है"
type: docs

url: /hi/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

`XPathResult` इंटरफ़ेस किसी विशिष्ट नोड के संदर्भ में XPath 1.0 अभिव्यक्ति के मूल्यांकन का परिणाम दर्शाता है। चूंकि XPath अभिव्यक्ति का मूल्यांकन विभिन्न परिणाम प्रकारों में हो सकता है, यह ऑब्जेक्ट परिणाम के प्रकार और मान को खोजने और संशोधित करने की सुविधा देता है।

```java
public interface IXPathResult
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) इस बूलियन परिणाम का मान। |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) दर्शाता है कि इटरेटर अमान्य हो गया है। यह सत्य है यदि `resultType` `UnorderedNodeIterator` प्रकार या `OrderedNodeIterator` प्रकार है और इस परिणाम के लौटाए जाने के बाद दस्तावेज़ संशोधित किया गया है। |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) इस संख्या परिणाम का मान। |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) इस परिणाम के प्रकार का प्रतिनिधित्व करने वाला कोड, जैसा कि http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/) एन्‍युम द्वारा निर्धारित है। |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) इस एकल नोड परिणाम का मान, जो `null` हो सकता है। |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) परिणाम स्नैपशॉट में नोड्स की संख्या। स्नैपशॉट आइटम सूचकांकों के मान `0` से `snapshotLength-1` तक वैध हैं। |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) इस स्ट्रिंग परिणाम का मान। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | नोड सेट से अगला नोड इटररेट करता है और लौटाता है, या यदि और नोड नहीं हैं तो `null` लौटाता है। |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | स्नैपशॉट संग्रह में `index`वें आइटम को लौटाता है। यदि `index` सूची में नोड्स की संख्या से बड़ा या बराबर है, तो यह मेथड `null` लौटाता है। इटररेटर परिणाम के विपरीत, स्नैपशॉट अमान्य नहीं होता, लेकिन यदि दस्तावेज़ बदलता है तो यह वर्तमान दस्तावेज़ से मेल नहीं खा सकता। |

### संबंधित देखें

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
