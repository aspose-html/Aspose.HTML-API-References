---
title: "TypeInfo.IsDerivedFrom"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "TypeInfo मेथड। यह मेथड यह बताता है कि क्या रेफ़रेंस टाइप डिफ़िनिशन (यानी वह TypeInfo जिस पर मेथड को कॉल किया जा रहा है) और अन्य टाइप डिफ़िनिशन (जो पैरामीटर के रूप में पास किया गया है) के बीच व्युत्पत्ति मौजूद है।"
type: docs

url: /hi/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

यह मेथड यह लौटाता है कि क्या संदर्भ प्रकार परिभाषा (यानी वह TypeInfo जिस पर मेथड को कॉल किया जा रहा है) और अन्य प्रकार परिभाषा (यानी पैरामीटर के रूप में पास किया गया) के बीच कोई व्युत्पत्ति है।

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| typeNamespaceArg | String | अन्य टाइप डिफ़िनिशन का पैकेज |
| typeNameArg | String | अन्य टाइप डिफ़िनिशन का नाम। |
| derivationMethod | UInt64 | दो प्रकारों के बीच लागू की गई व्युत्पत्ति का प्रकार और शर्तें, जैसा कि इस इंटरफ़ेस में प्रदान किए गए स्थिरांकों की सूची में वर्णित है। |

### रिटर्न वैल्यू

यदि दस्तावेज़ की स्कीमा DTD है या दस्तावेज़ से कोई स्कीमा जुड़ा नहीं है, तो यह मेथड हमेशा false लौटाएगा। यदि दस्तावेज़ की स्कीमा XML Schema है, तो यह मेथड true लौटाएगा यदि रेफ़रेंस टाइप डिफ़िनिशन, व्युत्पत्ति पैरामीटर के अनुसार, अन्य टाइप डिफ़िनिशन से व्युत्पन्न है। यदि पैरामीटर का मान 0 है (derivationMethod पैरामीटर के लिए कोई बिट 1 पर सेट नहीं है), तो मेथड true लौटाएगा यदि अन्य टाइप डिफ़िनिशन को रेफ़रेंस टाइप डिफ़िनिशन से {base type definition}, {item type definition} या {member type definitions} के किसी भी संयोजन को पुनरावृत्ति करके पहुँचा जा सकता है।

### संबंधित देखें

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
