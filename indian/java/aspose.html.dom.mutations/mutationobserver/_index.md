---
title: "MutationObserver क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.mutations.MutationObserver क्लास। एक ऑब्जेक्ट का उपयोग ट्री में म्यूटेशन्स को निरीक्षण करने के लिए किया जा सकता है।"
type: docs

url: /hi/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

एक ऑब्जेक्ट का उपयोग ट्री में म्यूटेशन्स को निरीक्षण करने के लिए किया जा सकता है [`.`](../../com.aspose.html.dom/node/)

```java
public class MutationObserver : DOMObject
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | एक MutationObserver ऑब्जेक्ट बनाता है और उसके [`MutationCallback`](../mutationcallback/) को कॉलबैक पर सेट करता है। कॉलबैक को पहले तर्क के रूप में MutationRecord ऑब्जेक्ट्स की सूची और दूसरे तर्क के रूप में निर्मित MutationObserver ऑब्जेक्ट के साथ बुलाया जाता है। यह उन नोड्स के पंजीकृत होने के बाद बुलाया जाता है जो !:Observe(Node, IMutationObserverInit) मेथड के साथ पंजीकृत हैं, जब वे म्यूटेट होते हैं। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | ऑब्ज़र्वर को किसी भी म्यूटेशन को निरीक्षण करने से रोकता है। जब तक observe() मेथड फिर से उपयोग नहीं किया जाता, ऑब्ज़र्वर का कॉलबैक नहीं बुलाया जाएगा। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | यूज़र एजेंट को निर्देश देता है कि वह दिए गए लक्ष्य (एक नोड) को निरीक्षण करे और विकल्पों (एक ऑब्जेक्ट) द्वारा दिए गए मानदंडों के आधार पर किसी भी म्यूटेशन की रिपोर्ट करे। विकल्प तर्क ऑब्जेक्ट के सदस्यों के माध्यम से म्यूटेशन निरीक्षण विकल्प सेट करने की अनुमति देता है। |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | यूज़र एजेंट को निर्देश देता है कि वह दिए गए लक्ष्य (एक नोड) को निरीक्षण करे और विकल्पों (एक ऑब्जेक्ट) द्वारा दिए गए मानदंडों के आधार पर किसी भी म्यूटेशन की रिपोर्ट करे। विकल्प तर्क ऑब्जेक्ट के सदस्यों के माध्यम से म्यूटेशन निरीक्षण विकल्प सेट करने की अनुमति देता है। |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | यह मेथड रिकॉर्ड क्यू की एक कॉपी लौटाता है और फिर रिकॉर्ड क्यू को खाली कर देता है। |

### संबंधित देखें

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
