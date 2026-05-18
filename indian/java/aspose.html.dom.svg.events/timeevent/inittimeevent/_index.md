---
title: "TimeEvent.InitTimeEvent"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "TimeEvent मेथड। initTimeEvent मेथड का उपयोग DocumentEvent इंटरफ़ेस के माध्यम से निर्मित TimeEvent के मान को प्रारंभ करने के लिए किया जाता है। यह मेथड केवल तब ही कॉल किया जा सकता है जब TimeEvent को dispatchEvent मेथड के द्वारा डिस्पैच किया जाना बाकी हो, हालांकि आवश्यक होने पर इस चरण के दौरान इसे कई बार कॉल किया जा सकता है। यदि कई बार कॉल किया जाता है तो अंतिम कॉल को प्राथमिकता दी जाती है।"
type: docs

url: /hi/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

initTimeEvent मेथड का उपयोग DocumentEvent इंटरफ़ेस के माध्यम से निर्मित TimeEvent के मान को इनिशियलाइज़ करने के लिए किया जाता है। यह मेथड केवल तब कॉल किया जा सकता है जब TimeEvent को dispatchEvent मेथड के द्वारा डिस्पैच किया जाना बाकी हो, हालांकि आवश्यक होने पर इसे उस चरण में कई बार कॉल किया जा सकता है। यदि कई बार कॉल किया जाता है, तो अंतिम कॉल को प्राथमिकता दी जाती है।

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| typeArg | String | इवेंट प्रकार को निर्दिष्ट करता है। |
| viewArg | IAbstractView | इवेंट के AbstractView को निर्दिष्ट करता है। |
| detailArg | Int64 | इवेंट का विवरण निर्दिष्ट करता है। |

### संबंधित देखें

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
