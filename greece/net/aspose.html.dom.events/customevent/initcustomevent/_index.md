---
title: CustomEvent.InitCustomEvent
second_title: Aspose.HTML για Αναφορά API .NET
description: CustomEvent μέθοδος. /// ΤοInitEvent Η μέθοδος χρησιμοποιείται για την προετοιμασία της τιμής του anEvent δημιουργήθηκε μέσω τουIDocumentEvent διεπαφή.
type: docs
weight: 30
url: /el/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Το[`InitEvent`](../../event/initevent/) Η μέθοδος χρησιμοποιείται για την προετοιμασία της τιμής του an[`Event`](../../event/) δημιουργήθηκε μέσω του[`IDocumentEvent`](../../idocumentevent/) διεπαφή.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | String | Ο τύπος εκδήλωσης. |
| bubbles | Boolean | εάν έχει οριστεί σε`αληθής` [φυσαλίδες]. |
| cancelable | Boolean | εάν έχει οριστεί σε`αληθής` [ακυρώσιμο]. |
| detail | Object | Τα προσαρμοσμένα δεδομένα. |

### Παρατηρήσεις

Αυτή η μέθοδος μπορεί να κληθεί μόνο πριν από την αποστολή του συμβάντος μέσω του[`DispatchEvent`](../../ieventtarget/dispatchevent/) μέθοδος, αν και μπορεί να κληθεί πολλές φορές κατά τη διάρκεια αυτής της φάσης εάν είναι απαραίτητο. Εάν καλείται πολλές φορές, η τελική επίκληση έχει προτεραιότητα. Εάν καλείται από μια υποκλάση της διεπαφής συμβάντος τροποποιούνται μόνο οι τιμές που καθορίζονται στη μέθοδο initEvent, όλα τα άλλα χαρακτηριστικά παραμένουν αμετάβλητα.

### Δείτε επίσης

* class [CustomEvent](../)
* χώρος ονομάτων [Aspose.Html.Dom.Events](../../customevent/)
* συνέλευση [Aspose.HTML](../../../)


