---
title: "EventTarget.RemoveEventListener"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος EventTarget. Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο του συμβάντος. Εάν ένας αφαιρεθεί ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι ακροατές συμβάντων δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους"
type: docs

url: /el/java/com.aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(String, DOMEventHandler, bool) {#removeeventlistener}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους.

```java
public void RemoveEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τύπος | String | Καθορίζει τον τύπο του γεγονότος που αφαιρείται. |
| διαχειριστής | DOMEventHandler | Η παράμετρος υποδεικνύει το προς αφαίρεση. |
| useCapture | Boolean | Καθορίζει εάν ο EventListener που αφαιρείται είχε καταχωρηθεί ως listener σύλληψης ή όχι. Εάν ένας listener είχε καταχωρηθεί δύο φορές, ένας με σύλληψη και ένας χωρίς, πρέπει να αφαιρεθεί ξεχωριστά. Η αφαίρεση ενός listener σύλληψης δεν επηρεάζει μια μη-συλλήπτη έκδοση του ίδιου listener, και αντίστροφα. |

### Δείτε επίσης

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener) {#removeeventlistener_1}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τύπος | String | Καθορίζει τον τύπο του γεγονότος που αφαιρείται. |
| listener | IEventListener | Η παράμετρος υποδεικνύει το προς αφαίρεση. |

### Δείτε επίσης

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_2}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τύπος | String | Καθορίζει τον τύπο του γεγονότος που αφαιρείται. |
| listener | IEventListener | Η παράμετρος υποδεικνύει το προς αφαίρεση. |
| useCapture | Boolean | Καθορίζει εάν ο EventListener που αφαιρείται είχε καταχωρηθεί ως listener σύλληψης ή όχι. Εάν ένας listener είχε καταχωρηθεί δύο φορές, ένας με σύλληψη και ένας χωρίς, πρέπει να αφαιρεθεί ξεχωριστά. Η αφαίρεση ενός listener σύλληψης δεν επηρεάζει μια μη-συλλήπτη έκδοση του ίδιου listener, και αντίστροφα. |

### Δείτε επίσης

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
