---
title: "SVGSVGElement.CreateEvent"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος SVGSVGElement. Δημιουργεί ένα Event τύπου που υποστηρίζεται από την υλοποίηση."
type: docs

url: /el/java/com.aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Δημιουργεί ένα [`Event`](../../../com.aspose.html.dom.events/event/) τύπου που υποστηρίζεται από την υλοποίηση.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| eventType | String | Η παράμετρος eventType καθορίζει τον τύπο της διεπαφής [`Event`](../../../com.aspose.html.dom.events/event/) που θα δημιουργηθεί. Εάν η διεπαφή [`Event`](../../../com.aspose.html.dom.events/event/) που καθορίζεται υποστηρίζεται από την υλοποίηση, αυτή η μέθοδος θα επιστρέψει ένα νέο[`Event`](../../../com.aspose.html.dom.events/event/) του ζητούμενου τύπου διεπαφής. Εάν το [`Event`](../../../com.aspose.html.dom.events/event/) πρέπει να διανεμηθεί μέσω της μεθόδου [`DispatchEvent`](../../../com.aspose.html.dom/eventtarget/dispatchevent/) η κατάλληλη μέθοδος [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) πρέπει να κληθεί μετά τη δημιουργία ώστε να αρχικοποιηθούν οι τιμές του [`Event`](../../../com.aspose.html.dom.events/event/). |

### Τιμή επιστροφής

Το νεοδημιουργημένο [`Event`](../../../com.aspose.html.dom.events/event/)

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν η υλοποίηση δεν υποστηρίζει τον τύπο της ζητούμενης διεπαφής [`Event`](../../../com.aspose.html.dom.events/event/) |

### Δείτε επίσης

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
