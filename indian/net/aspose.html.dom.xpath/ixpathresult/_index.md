---
title: Interface IXPathResult
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.XPath.IXPathResult इंटरफेस. दXPathResult इंटरफ़ेस एक वशेष नड के संदर्भ में एक XPath 1.0 अभव्यक्त के मूल्यंकन के परणम क प्रतनधत्व करत है चूँक XPath व्यंजक के मूल्यंकन के परणमस्वरूप वभन्न प्रकर के परणम ह सकते हैं यह ऑब्जेक्ट क परणम के प्रकर और मन क खज और हेरफेर करन संभव बनत है.
type: docs
weight: 2600
url: /hi/net/aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

द`XPathResult` इंटरफ़ेस एक विशेष नोड के संदर्भ में एक XPath 1.0 अभिव्यक्ति के मूल्यांकन के परिणाम का प्रतिनिधित्व करता है। चूँकि XPath व्यंजक के मूल्यांकन के परिणामस्वरूप विभिन्न प्रकार के परिणाम हो सकते हैं, यह ऑब्जेक्ट को परिणाम के प्रकार और मान की खोज और हेरफेर करना संभव बनाता है.

```csharp
public interface IXPathResult
```

## गुण

| नाम | विवरण |
| --- | --- |
| [BooleanValue](../../aspose.html.dom.xpath/ixpathresult/booleanvalue/) { get; } | इस बूलियन परिणाम का मान। |
| [InvalidIteratorState](../../aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | दर्शाता है कि इटरेटर अमान्य हो गया है। सच है अगर`परिणाम प्रकार` है`अनऑर्डर्ड नोड इटरेटर` टाइप करें या`ऑर्डर किया गया नोड इटरेटर` प्रकार और इस परिणाम के वापस आने के बाद से दस्तावेज़ को संशोधित किया गया है। |
| [NumberValue](../../aspose.html.dom.xpath/ixpathresult/numbervalue/) { get; } | इस संख्या परिणाम का मान। |
| [ResultType](../../aspose.html.dom.xpath/ixpathresult/resulttype/) { get; } | इस परिणाम के प्रकार का प्रतिनिधित्व करने वाला एक कोड, जैसा कि http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult द्वारा परिभाषित किया गया है[`XPathResultType`](../xpathresulttype/) गणना. |
| [SingleNodeValue](../../aspose.html.dom.xpath/ixpathresult/singlenodevalue/) { get; } | इस एकल नोड परिणाम का मान, जो हो सकता है`व्यर्थ` . |
| [SnapshotLength](../../aspose.html.dom.xpath/ixpathresult/snapshotlength/) { get; } | परिणाम स्नैपशॉट में नोड्स की संख्या। स्नैपशॉटआइटम सूचकांकों के लिए मान्य मान हैं`0` को`स्नैपशॉट लंबाई -1` समावेशी. |
| [StringValue](../../aspose.html.dom.xpath/ixpathresult/stringvalue/) { get; } | इस स्ट्रिंग परिणाम का मान। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [IterateNext](../../aspose.html.dom.xpath/ixpathresult/iteratenext/)() | नोड सेट या से अगले नोड को दोहराता है और वापस करता है`व्यर्थ` अगर कोई और नोड नहीं हैं। |
| [SnapshotItem](../../aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | लौटाता है`अनुक्रमणिका` स्नैपशॉट संग्रह में वें आइटम। अगर`अनुक्रमणिका` से अधिक है या सूची में नोड्स की संख्या के बराबर है, यह विधि वापस आती है`व्यर्थ` . पुनरावर्तक परिणाम के विपरीत, स्नैपशॉट अमान्य नहीं होता है, लेकिन वर्तमान दस्तावेज़ के अनुरूप नहीं हो सकता है यदि यह उत्परिवर्तित है। |

### यह सभी देखें

* नाम स्थान [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* सभा [Aspose.HTML](../../)


