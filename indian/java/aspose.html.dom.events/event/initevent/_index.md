---
title: "Event.InitEvent"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "इवेंट मेथड। InitEvent मेथड का उपयोग theIDocumentEvent इंटरफ़ेस के माध्यम से बनाए गए इवेंट के मान को प्रारंभ करने के लिए किया जाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

`InitEvent` मेथड का उपयोग एक [`Event`](../) के मान को प्रारंभ करने के लिए किया जाता है जो [`IDocumentEvent`](../../idocumentevent/) इंटरफ़ेस के माध्यम से बनाया गया है।

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | String | इवेंट प्रकार। |
| bubbles | Boolean | यदि `true` पर सेट किया गया है तो [bubbles]. |
| cancelable | Boolean | यदि `true` पर सेट किया गया है तो [cancelable]. |

## Remarks

यह मेथड केवल तब बुलाया जा सकता है जब तक Event को [`DispatchEvent`](../../ieventtarget/dispatchevent/) मेथड के माध्यम से डिस्पैच नहीं किया गया हो, हालांकि आवश्यक होने पर इसे उस चरण के दौरान कई बार बुलाया जा सकता है। यदि कई बार बुलाया जाता है तो अंतिम कॉल को प्राथमिकता दी जाती है। यदि Event इंटरफ़ेस के उपवर्ग से बुलाया जाता है तो केवल initEvent मेथड में निर्दिष्ट मानों को संशोधित किया जाता है, अन्य सभी गुण अपरिवर्तित रहते हैं।

### संबंधित देखें

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
