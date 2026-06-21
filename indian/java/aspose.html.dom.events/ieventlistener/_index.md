---
title: "IEventListener Interface"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.events.IEventListener interface. The interface is the primary method for handling events. Users implement the interface and register their listener on an using the method. The users should also remove their from its after they have completed using the listener"
type: docs

url: /hi/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

इंटरफ़ेस इवेंट्स को संभालने की मुख्य विधि है। उपयोगकर्ता इंटरफ़ेस को लागू करते हैं और विधि का उपयोग करके अपना लिस्नर पंजीकृत करते हैं। उपयोगकर्ताओं को लिस्नर के उपयोग को समाप्त करने के बाद उसे हटाना भी चाहिए।

```java
public interface IEventListener
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | This method is called whenever an event occurs of the type for which the interface was registered. |

## Remarks

When a Node is copied using the cloneNode method the Event Listeners attached to the source Node are not attached to the copied Node. If the user wishes the same Event Listeners to be added to the newly created copy the user must add them manually.

### संबंधित देखें

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
