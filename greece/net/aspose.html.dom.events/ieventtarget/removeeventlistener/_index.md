---
title: IEventTarget.RemoveEventListener
second_title: Aspose.HTML για Αναφορά API .NET
description: IEventTarget μέθοδος. Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο συμβάντος. ΕάνIEventListener αφαιρείται από έναEventTarget ενώ επεξεργάζεται ένα συμβάν δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Δεν είναι δυνατή η επίκληση των Ακροατών συμβάντων μετά την αφαίρεση.
type: docs
weight: 30
url: /el/net/aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο συμβάντος. Εάν[`IEventListener`](../../ieventlistener/) αφαιρείται από ένα[`EventTarget`](../../../aspose.html.dom/eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Δεν είναι δυνατή η επίκληση των Ακροατών συμβάντων μετά την αφαίρεση.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Καθορίζει τον τύπο συμβάντος του[`IEventListener`](../../ieventlistener/) που αφαιρείται. |
| listener | IEventListener | ο[`IEventListener`](../../ieventlistener/) παράμετρος δείχνει το[`IEventListener`](../../ieventlistener/) να αφαιρεθεί. |

### Δείτε επίσης

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* χώρος ονομάτων [Aspose.Html.Dom.Events](../../ieventtarget/)
* συνέλευση [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο συμβάντος. Εάν[`IEventListener`](../../ieventlistener/) αφαιρείται από ένα[`EventTarget`](../../../aspose.html.dom/eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Δεν είναι δυνατή η επίκληση των Ακροατών συμβάντων μετά την αφαίρεση.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Καθορίζει τον τύπο συμβάντος του[`IEventListener`](../../ieventlistener/) που αφαιρείται. |
| listener | IEventListener | ο[`IEventListener`](../../ieventlistener/) παράμετρος δείχνει το[`IEventListener`](../../ieventlistener/) να αφαιρεθεί. |
| useCapture | Boolean | Καθορίζει εάν το EventListener που καταργείται έχει καταχωρηθεί ως ακροατής λήψης ή όχι. Εάν ένας ακροατής έχει εγγραφεί δύο φορές, ένας με καταγραφή και ένας χωρίς, το καθένα πρέπει να αφαιρεθεί ξεχωριστά. Η αφαίρεση ενός ακροατή που καταγράφει δεν επηρεάζει την έκδοση που δεν καταγράφει του ίδιου ακροατή, και αντίστροφα. |

### Δείτε επίσης

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* χώρος ονομάτων [Aspose.Html.Dom.Events](../../ieventtarget/)
* συνέλευση [Aspose.HTML](../../../)


