---
title: "MediaQueryList Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.window.MediaQueryList κλάση. Ένα αντικείμενο MediaQueryList αποθηκεύει πληροφορίες σχετικά με ένα ερώτημα μέσου που εφαρμόζεται σε ένα έγγραφο με υποστήριξη τόσο άμεσης όσο και συμβάν-βασισμένης αντιστοίχισης με την κατάσταση του εγγράφου. Δείτε την προδιαγραφή του CSSOM View Module https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /el/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

Ένα αντικείμενο MediaQueryList αποθηκεύει πληροφορίες σχετικά με ένα ερώτημα μέσων που εφαρμόζεται σε ένα έγγραφο, με υποστήριξη τόσο για άμεση όσο και για γεγονότα‑βασισμένη αντιστοίχιση με την κατάσταση του εγγράφου. Δείτε την προδιαγραφή του CSSOM View Module: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) Το σχετικό έγγραφο του αντικειμένου Context. |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) Μια boolean τιμή που επιστρέφει true εάν το έγγραφο τρέχοντα ταιριάζει με τη λίστα ερωτημάτων μέσου, ή false αν όχι. |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) Μια String που αντιπροσωπεύει ένα σειριοποιημένο ερώτημα μέσου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() method of the [`EventTarget `](../../com.aspose.html.dom/eventtarget/)interface sets up a function that will be called whenever the specified event is delivered to the target. Η μέθοδος addEventListener() της διεπαφής [`EventTarget`](../../com.aspose.html.dom/eventtarget/) ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο γεγονός παραδοθεί στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Η μέθοδος addEventListener() του [EventTarget ](T:com.aspose.html.dom.EventTarget)interface ρυθμίζει μια λειτουργία που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Η μέθοδος addEventListener() του [EventTarget ](T:com.aspose.html.dom.EventTarget)interface ρυθμίζει μια λειτουργία που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | Προσθέστε ακροατή συμβάντος αλλαγής κατάστασης matches του MediaQueryList. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Αποστέλλει ένα Event στο καθορισμένο [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (συγχρονισμένα) καλώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένης της φάσης σύλληψης και της προαιρετικής φάσης διάδοσης) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με το [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένας αφαιρεθεί από ένα ενώ επεξεργάζεται ένα event, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένας αφαιρεθεί από ένα ενώ επεξεργάζεται ένα event, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένας αφαιρεθεί από ένα ενώ επεξεργάζεται ένα event, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | Αφαιρέστε ακροατή συμβάντος αλλαγής κατάστασης matches του MediaQueryList. |

## Συμβάντα

| Όνομα | Περιγραφή |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | Συμβάν που εκτελείται στο MediaQueryList όταν η κατάσταση matches αλλάζει. |

### Δείτε επίσης

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
