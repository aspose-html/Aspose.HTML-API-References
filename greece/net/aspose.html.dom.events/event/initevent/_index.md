---
title: Event.InitEvent
second_title: Aspose.HTML για Αναφορά API .NET
description: Event μέθοδος. ΤοInitEvent Η μέθοδος χρησιμοποιείται για την προετοιμασία της τιμής του anEvent δημιουργήθηκε μέσω του IDocumentEvent διεπαφή.
type: docs
weight: 110
url: /el/net/aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

Το`InitEvent` Η μέθοδος χρησιμοποιείται για την προετοιμασία της τιμής του an[`Event`](../) δημιουργήθηκε μέσω του [`IDocumentEvent`](../../idocumentevent/) διεπαφή.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Ο τύπος εκδήλωσης. |
| bubbles | Boolean | εάν έχει οριστεί σε`αληθής` [φυσαλίδες]. |
| cancelable | Boolean | εάν έχει οριστεί σε`αληθής` [ακυρώσιμο]. |

### Παρατηρήσεις

Αυτή η μέθοδος μπορεί να κληθεί μόνο πριν από την αποστολή του συμβάντος μέσω του[`DispatchEvent`](../../ieventtarget/dispatchevent/) μέθοδος, αν και μπορεί να κληθεί πολλές φορές κατά τη διάρκεια αυτής της φάσης εάν είναι απαραίτητο. Εάν καλείται πολλές φορές, η τελική επίκληση έχει προτεραιότητα. Εάν καλείται από μια υποκλάση της διεπαφής συμβάντος τροποποιούνται μόνο οι τιμές που καθορίζονται στη μέθοδο initEvent, όλα τα άλλα χαρακτηριστικά παραμένουν αμετάβλητα.

### Δείτε επίσης

* class [Event](../)
* χώρος ονομάτων [Aspose.Html.Dom.Events](../../event/)
* συνέλευση [Aspose.HTML](../../../)


