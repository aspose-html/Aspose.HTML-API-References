---
title: "Event.InitEvent"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Event मेथड। InitEvent मेथड का उपयोग उस Event के मान को प्रारम्भ करने के लिए किया जाता है जो IDocumentEvent इंटरफ़ेस के माध्यम से बनाया गया है।"
type: docs

url: /hi/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

`InitEvent` मेथड का उपयोग उस [`Event`](../) के मान को प्रारम्भ करने के लिए किया जाता है जो [`IDocumentEvent`](../../idocumentevent/) इंटरफ़ेस के माध्यम से बनाया गया है।

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रकार | String | इवेंट प्रकार। |
| bubbles | Boolean | यदि `true` पर सेट किया गया है तो [bubbles]। |
| cancelable | Boolean | यदि `true` पर सेट किया गया है तो [cancelable]। |

## टिप्पणियाँ

यह मेथड केवल तब ही कॉल किया जा सकता है जब Event को [`DispatchEvent`](../../ieventtarget/dispatchevent/) मेथड के माध्यम से डिस्पैच किया जाना बाकी हो, हालांकि आवश्यक होने पर इसे उस चरण के दौरान कई बार कॉल किया जा सकता है। यदि कई बार कॉल किया जाता है तो अंतिम कॉल को प्राथमिकता दी जाती है। यदि Event इंटरफ़ेस के सबक्लास से कॉल किया जाता है तो केवल initEvent मेथड में निर्दिष्ट मानों को संशोधित किया जाता है, अन्य सभी गुण अपरिवर्तित रहते हैं।

### संबंधित देखें

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
