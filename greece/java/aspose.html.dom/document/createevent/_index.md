---
title: "Document.CreateEvent"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Document. Δημιουργεί ένα Event τύπου που υποστηρίζεται από την υλοποίηση"
type: docs

url: /el/java/com.aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Δημιουργεί ένα [`Event`](../../../com.aspose.html.dom.events/event/) τύπου που υποστηρίζεται από την υλοποίηση.

```java
public Event CreateEvent(String eventType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eventType | String | Η παράμετρος eventType καθορίζει τον τύπο της διεπαφής [`Event`](../../../com.aspose.html.dom.events/event/) που θα δημιουργηθεί. Εάν η καθορισμένη διεπαφή [`Event`](../../../com.aspose.html.dom.events/event/) υποστηρίζεται από την υλοποίηση, αυτή η μέθοδος θα επιστρέψει ένα νέο [`Event`](../../../com.aspose.html.dom.events/event/) του ζητούμενου τύπου διεπαφής. Εάν το [`Event`](../../../com.aspose.html.dom.events/event/) πρόκειται να διανεμηθεί μέσω της μεθόδου [`DispatchEvent`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/), πρέπει να κληθεί η κατάλληλη μέθοδος [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) μετά τη δημιουργία, προκειμένου να αρχικοποιηθούν οι τιμές του [`Event`](../../../com.aspose.html.dom.events/event/). |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [`Event`](../../../com.aspose.html.dom.events/event/)

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν η υλοποίηση δεν υποστηρίζει τον τύπο της διεπαφής [`Event`](../../../com.aspose.html.dom.events/event/) που ζητήθηκε |

### Δείτε επίσης

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
