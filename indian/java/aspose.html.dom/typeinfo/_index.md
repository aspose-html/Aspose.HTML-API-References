---
title: "TypeInfo क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.TypeInfo क्लास। TypeInfo वह प्रकार दर्शाता है जो Element या Attr नोड्स से संदर्भित है, जो दस्तावेज़ से जुड़े स्कीमा में निर्दिष्ट हैं।"
type: docs

url: /hi/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo वह प्रकार दर्शाता है जो Element या Attr नोड्स से संदर्भित होता है, जो दस्तावेज़ से जुड़े स्कीमा में निर्दिष्ट होता है।

```java
public class TypeInfo : DOMObject
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) संबंधित तत्व या attribute के लिए घोषित प्रकार का नाम, या यदि अज्ञात हो तो null। |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) प्रकार पैकेज प्राप्त करता है। प्रकार पैकेज वह पैकेज है जो संबंधित तत्व या attribute के लिए घोषित प्रकार का है, या यदि तत्व के पास घोषणा नहीं है या पैकेज जानकारी उपलब्ध नहीं है तो null। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | यह मेथड यह लौटाता है कि क्या संदर्भ प्रकार परिभाषा (यानी वह TypeInfo जिस पर मेथड को कॉल किया जा रहा है) और अन्य प्रकार परिभाषा (यानी पैरामीटर के रूप में पास किया गया) के बीच कोई व्युत्पत्ति है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | यदि दस्तावेज़ का स्कीमा XML Schema [XML Schema Part 1] है, तो यह स्थिरांक विस्तार द्वारा व्युत्पत्ति को दर्शाता है। |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | यदि दस्तावेज़ का स्कीमा XML Schema [XML Schema Part 1] है, तो यह स्थिरांक सूची को दर्शाता है। |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | यदि दस्तावेज़ का स्कीमा XML Schema [XML Schema Part 1] है, तो यह स्थिरांक प्रतिबंध द्वारा व्युत्पत्ति को दर्शाता है यदि जटिल प्रकार शामिल हैं, या सरल प्रकार शामिल होने पर प्रतिबंध को दर्शाता है। |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | यदि दस्तावेज़ का स्कीमा XML Schema [XML Schema Part 1] है, तो यह स्थिरांक संघ (union) को दर्शाता है यदि सरल प्रकार शामिल हैं। |

### संबंधित देखें

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
