---
title: IEventTarget.AddEventListener
second_title: Aspose.HTML για Αναφορά API .NET
description: IEventTarget μέθοδος. Αυτή η μέθοδος επιτρέπει την εγγραφή των ακροατών συμβάντων στον στόχο συμβάντος.
type: docs
weight: 10
url: /el/net/aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(string, IEventListener) {#addeventlistener}

Αυτή η μέθοδος επιτρέπει την εγγραφή των ακροατών συμβάντων στον στόχο συμβάντος.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Ο τύπος συμβάντος για τον οποίο εγγράφεται ο χρήστης |
| listener | IEventListener | Λαμβάνει μια διεπαφή που υλοποιείται από τον χρήστη η οποία περιέχει τις μεθόδους που θα κληθούν όταν συμβεί το συμβάν. |

### Παρατηρήσεις

Εάν α[`IEventListener`](../../ieventlistener/) προστίθεται σε ένα[`EventTarget`](../../../aspose.html.dom/eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες, αλλά μπορεί να ενεργοποιηθεί κατά τη διάρκεια ενός μεταγενέστερου σταδίου ροής συμβάντος, όπως η φάση δημιουργίας φυσαλίδων.

Εάν είναι εγγεγραμμένοι πολλαπλοί ίδιοι ακροατές συμβάντων στο ίδιο[`EventTarget`](../../../aspose.html.dom/eventtarget/)με τις ίδιες παραμέτρους οι διπλές εμφανίσεις απορρίπτονται. Δεν προκαλούν το[`IEventListener`](../../ieventlistener/) να κληθούν δύο φορές και αφού απορρίπτονται δεν χρειάζεται να αφαιρεθούν με το [`RemoveEventListener`](../removeeventlistener/) μέθοδος.

### Δείτε επίσης

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* χώρος ονομάτων [Aspose.Html.Dom.Events](../../ieventtarget/)
* συνέλευση [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_1}

Αυτή η μέθοδος επιτρέπει την εγγραφή των ακροατών συμβάντων στον στόχο συμβάντος.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Ο τύπος συμβάντος για τον οποίο εγγράφεται ο χρήστης |
| listener | IEventListener | Λαμβάνει μια διεπαφή που υλοποιείται από τον χρήστη η οποία περιέχει τις μεθόδους που θα κληθούν όταν συμβεί το συμβάν. |
| useCapture | Boolean | Εάν ισχύει, το useCapture υποδεικνύει ότι ο χρήστης επιθυμεί να ξεκινήσει τη λήψη. Μετά την έναρξη της λήψης, όλα τα συμβάντα του καθορισμένου τύπου θα αποσταλούν στο registered [`IEventListener`](../../ieventlistener/) πριν αποσταλεί σε οποιονδήποτε στόχο συμβάντων κάτω από αυτούς στο δέντρο.[`IEventListener`](../../ieventlistener/) προορίζεται για χρήση σύλληψης. |

### Παρατηρήσεις

Εάν α[`IEventListener`](../../ieventlistener/) προστίθεται σε ένα[`EventTarget`](../../../aspose.html.dom/eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες, αλλά μπορεί να ενεργοποιηθεί κατά τη διάρκεια ενός μεταγενέστερου σταδίου ροής συμβάντος, όπως η φάση δημιουργίας φυσαλίδων.

Εάν είναι εγγεγραμμένοι πολλαπλοί ίδιοι ακροατές συμβάντων στο ίδιο[`EventTarget`](../../../aspose.html.dom/eventtarget/)με τις ίδιες παραμέτρους οι διπλές εμφανίσεις απορρίπτονται. Δεν προκαλούν το[`IEventListener`](../../ieventlistener/) να κληθούν δύο φορές και αφού απορρίπτονται δεν χρειάζεται να αφαιρεθούν με το [`RemoveEventListener`](../removeeventlistener/) μέθοδος.

### Δείτε επίσης

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* χώρος ονομάτων [Aspose.Html.Dom.Events](../../ieventtarget/)
* συνέλευση [Aspose.HTML](../../../)


