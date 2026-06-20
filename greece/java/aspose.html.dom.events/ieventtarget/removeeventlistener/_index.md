---
title: "IEventTarget.RemoveEventListener"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "IEventTarget method. Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών γεγονότων από τον στόχο του γεγονότος. Εάν ένας αφαιρεθεί από έναν ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές γεγονότων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους"
type: docs

url: /el/java/com.aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(String, IEventListener) {#removeeventlistener}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένας αφαιρεθεί από ένα ενώ επεξεργάζεται ένα event, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | String | Καθορίζει τον τύπο του γεγονότος που αφαιρείται. |
| listener | IEventListener | Η παράμετρος υποδεικνύει το/την που πρέπει να αφαιρεθεί. |

### Δείτε επίσης

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_1}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένας αφαιρεθεί από ένα ενώ επεξεργάζεται ένα event, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | String | Καθορίζει τον τύπο του γεγονότος που αφαιρείται. |
| listener | IEventListener | Η παράμετρος υποδεικνύει το/την που πρέπει να αφαιρεθεί. |
| useCapture | Boolean | Καθορίζει εάν ο EventListener που αφαιρείται είχε καταχωρηθεί ως listener σύλληψης ή όχι. Εάν ένας listener είχε καταχωρηθεί δύο φορές, ένας με σύλληψη και ένας χωρίς, πρέπει να αφαιρεθούν ξεχωριστά. Η αφαίρεση ενός listener σύλληψης δεν επηρεάζει μια μη‑συλλήπτη έκδοση του ίδιου listener, και αντίστροφα. |

### Δείτε επίσης

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
