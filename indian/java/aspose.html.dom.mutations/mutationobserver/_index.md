---
title: "MutationObserver वर्ग"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.mutations.MutationObserver वर्ग। एक वस्तु का उपयोग वृक्ष में होने वाले परिवर्तनों को देखने के लिए किया जा सकता है।"
type: docs

url: /hi/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

एक वस्तु का उपयोग वृक्ष में होने वाले परिवर्तनों को देखने के लिए किया जा सकता है [`.`](../../com.aspose.html.dom/node/)

```java
public class MutationObserver : DOMObject
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | एक MutationObserver वस्तु बनाता है और उसकी [`MutationCallback`](../mutationcallback/) को callback पर सेट करता है। callback को पहले तर्क के रूप में MutationRecord वस्तुओं की सूची और दूसरे तर्क के रूप में निर्मित MutationObserver वस्तु के साथ बुलाया जाता है। यह उन नोड्स के पंजीकृत होने के बाद बुलाया जाता है जो !:Observe(Node, IMutationObserverInit) विधि के साथ पंजीकृत हैं, जब वे परिवर्तित होते हैं। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | पर्यवेक्षक को किसी भी परिवर्तन को देखना बंद कर देता है। जब तक observe() विधि फिर से उपयोग नहीं की जाती, पर्यवेक्षक का callback नहीं बुलाया जाएगा। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को प्राप्त करने के लिए उपयोग किया जाता है। |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | उपयोगकर्ता एजेंट को निर्देश देता है कि वह दिए गए लक्ष्य (एक नोड) को देखे और विकल्पों (एक वस्तु) द्वारा दिए गए मानदंडों के आधार पर किसी भी परिवर्तन की रिपोर्ट करे। विकल्प तर्क वस्तु के सदस्यों के माध्यम से परिवर्तन निरीक्षण विकल्प सेट करने की अनुमति देता है। |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | उपयोगकर्ता एजेंट को निर्देश देता है कि वह दिए गए लक्ष्य (एक नोड) को देखे और विकल्पों (एक वस्तु) द्वारा दिए गए मानदंडों के आधार पर किसी भी परिवर्तन की रिपोर्ट करे। विकल्प तर्क वस्तु के सदस्यों के माध्यम से परिवर्तन निरीक्षण विकल्प सेट करने की अनुमति देता है। |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | यह विधि रिकॉर्ड कतार की एक प्रति लौटाती है और फिर रिकॉर्ड कतार को खाली कर देती है। |

### संबंधित देखें

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
