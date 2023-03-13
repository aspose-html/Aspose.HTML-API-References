---
title: Event.InitEvent
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Event तरक. दInitEvent वध क उपयग कस के मन क प्ररंभ करने के लए कय जत हैEvent the द्वर बनय गयIDocumentEvent इंटरफ़ेस.
type: docs
weight: 110
url: /hi/net/aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

द`InitEvent` विधि का उपयोग किसी के मान को प्रारंभ करने के लिए किया जाता है[`Event`](../) the द्वारा बनाया गया[`IDocumentEvent`](../../idocumentevent/) इंटरफ़ेस.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | String | घटना प्रकार। |
| bubbles | Boolean | अगर सेट है`सत्य` [बुलबुले]। |
| cancelable | Boolean | अगर सेट है`सत्य` [रद्द करने योग्य]। |

### टिप्पणियों

इस विधि को केवल ईवेंट के माध्यम से भेजे जाने से पहले ही कॉल किया जा सकता है[`DispatchEvent`](../../ieventtarget/dispatchevent/) विधि, हालांकि यदि आवश्यक हो तो उस चरण के दौरान इसे कई बार कॉल किया जा सकता है। यदि कई बार कॉल किया जाता है तो अंतिम आमंत्रण पूर्वता लेता है। यदि ईवेंट इंटरफ़ेस के उप-वर्ग से कॉल किया जाता है तो केवल initEvent विधि में निर्दिष्ट मान संशोधित किए जाते हैं, अन्य सभी विशेषताएँ अपरिवर्तित छोड़ दिया जाता है।

### यह सभी देखें

* class [Event](../)
* नाम स्थान [Aspose.Html.Dom.Events](../../event/)
* सभा [Aspose.HTML](../../../)


