---
title: CustomEvent.InitCustomEvent
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: CustomEvent तरक. /// दInitEvent वध क उपयग कस के मन क प्ररंभ करने के लए कय जत हैEvent के मध्यम से बनय गय हैIDocumentEvent इंटरफ़ेस.
type: docs
weight: 30
url: /hi/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// द[`InitEvent`](../../event/initevent/) विधि का उपयोग किसी के मान को प्रारंभ करने के लिए किया जाता है[`Event`](../../event/) के माध्यम से बनाया गया है[`IDocumentEvent`](../../idocumentevent/) इंटरफ़ेस.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | String | घटना प्रकार। |
| bubbles | Boolean | अगर सेट है`सत्य` [बुलबुले]। |
| cancelable | Boolean | अगर सेट है`सत्य` [रद्द करने योग्य]। |
| detail | Object | कस्टम डेटा। |

### टिप्पणियों

इस विधि को केवल ईवेंट के माध्यम से भेजे जाने से पहले ही कॉल किया जा सकता है[`DispatchEvent`](../../ieventtarget/dispatchevent/) विधि, हालांकि यदि आवश्यक हो तो उस चरण के दौरान इसे कई बार कॉल किया जा सकता है। यदि कई बार कॉल किया जाता है तो अंतिम आमंत्रण पूर्वता लेता है। यदि ईवेंट इंटरफ़ेस के उप-वर्ग से कॉल किया जाता है तो केवल initEvent विधि में निर्दिष्ट मान संशोधित किए जाते हैं, अन्य सभी विशेषताएँ अपरिवर्तित छोड़ दिया जाता है।

### यह सभी देखें

* class [CustomEvent](../)
* नाम स्थान [Aspose.Html.Dom.Events](../../customevent/)
* सभा [Aspose.HTML](../../../)


