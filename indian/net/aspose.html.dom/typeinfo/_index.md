---
title: Class TypeInfo
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.TypeInfo कक्ष. TypeInfo दस्तवेज़ से जुड़े स्कम में नर्दष्ट तत्व य Attr नड्स से संदर्भत प्रकर क प्रतनधत्व करत है
type: docs
weight: 2530
url: /hi/net/aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo दस्तावेज़ से जुड़े स्कीमा में निर्दिष्ट तत्व या Attr नोड्स से संदर्भित प्रकार का प्रतिनिधित्व करता है।

```csharp
public class TypeInfo : DOMObject
```

## गुण

| नाम | विवरण |
| --- | --- |
| [TypeName](../../aspose.html.dom/typeinfo/typename/) { get; } | संबंधित तत्व या विशेषता के लिए घोषित प्रकार का नाम, या अज्ञात होने पर शून्य। |
| [TypeNamespace](../../aspose.html.dom/typeinfo/typenamespace/) { get; } | प्रकार का नामस्थान प्राप्त करता है। संबंधित तत्व या विशेषता या शून्य के लिए घोषित प्रकार का नामस्थान यदि तत्व में घोषणा नहीं है या यदि कोई नामस्थान जानकारी उपलब्ध नहीं है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| [IsDerivedFrom](../../aspose.html.dom/typeinfo/isderivedfrom/)(string, string, ulong) | यह विधि तब वापस आती है जब संदर्भ प्रकार की परिभाषा के बीच कोई व्युत्पत्ति होती है, यानी टाइपइन्फो जिस पर विधि को कॉल किया जा रहा है, और अन्य प्रकार की परिभाषा, यानी पैरामीटर के रूप में पास की गई। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.html.dom/typeinfo/derivation_extension/) | यदि दस्तावेज़ का स्कीमा एक XML स्कीमा [XML स्कीमा भाग 1] है, तो यह स्थिरांक विस्तार द्वारा व्युत्पत्ति का प्रतिनिधित्व करता है। |
| const [DERIVATION_LIST](../../aspose.html.dom/typeinfo/derivation_list/) | यदि दस्तावेज़ का स्कीमा एक XML स्कीमा [XML स्कीमा भाग 1] है, तो यह स्थिरांक सूची का प्रतिनिधित्व करता है। |
| const [DERIVATION_RESTRICTION](../../aspose.html.dom/typeinfo/derivation_restriction/) | यदि दस्तावेज़ का स्कीमा एक XML स्कीमा [XML स्कीमा भाग 1] है, तो यह स्थिरांक जटिल प्रकार शामिल होने पर प्रतिबंध द्वारा व्युत्पत्ति का प्रतिनिधित्व करता है, या सरल प्रकार शामिल होने पर प्रतिबंध। |
| const [DERIVATION_UNION](../../aspose.html.dom/typeinfo/derivation_union/) | यदि दस्तावेज़ का स्कीमा एक XML स्कीमा [XML स्कीमा भाग 1] है, तो यह स्थिरांक संघ का प्रतिनिधित्व करता है यदि सरल प्रकार शामिल हैं। |

### यह सभी देखें

* class [DOMObject](../domobject/)
* नाम स्थान [Aspose.Html.Dom](../../aspose.html.dom/)
* सभा [Aspose.HTML](../../)


