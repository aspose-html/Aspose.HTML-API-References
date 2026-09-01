---
title: "TypeInfo.IsDerivedFrom"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "TypeInfo मेथड। यह मेथड यह बताता है कि क्या संदर्भ प्रकार परिभाषा (यानी वह TypeInfo जिस पर मेथड को कॉल किया जा रहा है) और अन्य प्रकार परिभाषा (जो पैरामीटर के रूप में पास किया गया है) के बीच व्युत्पन्न है या नहीं।"
type: docs

url: /hi/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

यह मेथड यह लौटाता है कि क्या रेफ़रेंस टाइप डिफ़िनिशन (अर्थात वह TypeInfo जिस पर मेथड को कॉल किया जा रहा है) और अन्य टाइप डिफ़िनिशन (अर्थात पैरामीटर के रूप में पास किया गया) के बीच डेरिवेशन है।

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| typeNamespaceArg | String | अन्य प्रकार परिभाषा का पैकेज |
| typeNameArg | String | अन्य प्रकार परिभाषा का नाम। |
| derivationMethod | UInt64 | दो प्रकारों के बीच लागू किए गए व्युत्पन्न प्रकार और शर्तें, जैसा कि इस इंटरफ़ेस में प्रदान किए गए स्थिरांक सूची में वर्णित है। |

### रिटर्न वैल्यू

यदि दस्तावेज़ की स्कीमा DTD है या दस्तावेज़ से कोई स्कीमा जुड़ा नहीं है, तो यह मेथड हमेशा false लौटाएगा। यदि दस्तावेज़ की स्कीमा XML Schema है, तो मेथड true लौटाएगा यदि संदर्भ प्रकार परिभाषा व्युत्पन्न पैरामीटर के अनुसार अन्य प्रकार परिभाषा से व्युत्पन्न है। यदि पैरामीटर का मान 0 है (derivationMethod पैरामीटर के लिए कोई बिट 1 पर सेट नहीं है), तो मेथड true लौटाएगा यदि अन्य प्रकार परिभाषा को संदर्भ प्रकार परिभाषा से {base type definition}, {item type definition} या {member type definitions} के किसी भी संयोजन के पुनरावृत्ति द्वारा पहुँचा जा सकता है।

### संबंधित देखें

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
