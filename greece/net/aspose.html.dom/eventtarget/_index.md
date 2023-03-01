---
title: Class EventTarget
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.EventTarget τάξη. ΤοEventTarget Η διασύνδεση υλοποιείται από όλους τους κόμβους σε μια υλοποίηση που υποστηρίζει το μοντέλο συμβάντων DOM. Επομένως αυτή η διεπαφή μπορεί να αποκτηθεί χρησιμοποιώντας μεθόδους casting ειδικά για δέσμευση σε μια παρουσία της διεπαφής του κόμβου. Η διεπαφή επιτρέπει την εγγραφή και την αφαίρεση των ακρόασης συμβάντων σε έναEventTarget και αποστολή εκδηλώσεων σε αυτόIEventTarget .
type: docs
weight: 720
url: /el/net/aspose.html.dom/eventtarget/
---
## EventTarget class

Το`EventTarget` Η διασύνδεση υλοποιείται από όλους τους κόμβους σε μια υλοποίηση που υποστηρίζει το μοντέλο συμβάντων DOM. Επομένως, αυτή η διεπαφή μπορεί να αποκτηθεί χρησιμοποιώντας μεθόδους casting ειδικά για δέσμευση σε μια παρουσία της διεπαφής του κόμβου. Η διεπαφή επιτρέπει την εγγραφή και την αφαίρεση των ακρόασης συμβάντων σε ένα`EventTarget` και αποστολή εκδηλώσεων σε αυτό[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) .

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener) | Αυτή η μέθοδος επιτρέπει την εγγραφή των ακροατών συμβάντων στον στόχο συμβάντος. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(string, DOMEventHandler, bool) | Αυτή η μέθοδος επιτρέπει την εγγραφή των ακροατών συμβάντων στον στόχο συμβάντος. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(string, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την εγγραφή των ακροατών συμβάντων στον στόχο συμβάντος. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Αυτή η μέθοδος επιτρέπει την αποστολή συμβάντων στο μοντέλο συμβάντων υλοποιήσεων. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που καθορίζονται από την εφαρμογή που σχετίζονται με την απελευθέρωση, την απελευθέρωση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση αντικειμένου ECMAScriptType . |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο συμβάντος. Εάν[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) αφαιρείται από ένα`EventTarget` ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Δεν είναι δυνατή η επίκληση των Ακροατών συμβάντων μετά την αφαίρεση. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(string, DOMEventHandler, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο συμβάντος. Εάν[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) αφαιρείται από ένα`EventTarget` ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Δεν είναι δυνατή η επίκληση των Ακροατών συμβάντων μετά την αφαίρεση. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(string, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο συμβάντος. Εάν[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) αφαιρείται από ένα`EventTarget` ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Δεν είναι δυνατή η επίκληση των Ακροατών συμβάντων μετά την αφαίρεση. |

### Δείτε επίσης

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* χώρος ονομάτων [Aspose.Html.Dom](../../aspose.html.dom/)
* συνέλευση [Aspose.HTML](../../)


