---
title: "MediaQueryList Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.window.MediaQueryList class. Ένα αντικείμενο MediaQueryList αποθηκεύει πληροφορίες σχετικά με ένα ερώτημα μέσων που εφαρμόζεται σε ένα έγγραφο με υποστήριξη τόσο άμεσης όσο και συμβάν-οδηγούμενης αντιστοίχισης με την κατάσταση του εγγράφου. Δείτε την προδιαγραφή του CSSOM View Module https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /el/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

Ένα αντικείμενο MediaQueryList αποθηκεύει πληροφορίες σχετικά με ένα ερώτημα μέσων που εφαρμόζεται σε ένα έγγραφο, με υποστήριξη τόσο άμεσου όσο και συμβάν-βασισμένου ταίριασματος με την κατάσταση του εγγράφου. Δείτε την προδιαγραφή του CSSOM View Module: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) Σχετικό έγγραφο του αντικειμένου Context. |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) Μια λογική τιμή που επιστρέφει true εάν το έγγραφο ταιριάζει αυτή τη στιγμή με τη λίστα ερωτημάτων μέσων, ή false εάν όχι. |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) Ένα String που αντιπροσωπεύει ένα σειριοποιημένο ερώτημα μέσων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Η μέθοδος addEventListener() του interface [`EventTarget `](../../com.aspose.html.dom/eventtarget/) ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο γεγονός παραδοθεί στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Η μέθοδος addEventListener() του interface [EventTarget ](T:com.aspose.html.dom.EventTarget) ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Η μέθοδος addEventListener() του interface [EventTarget ](T:com.aspose.html.dom.EventTarget) ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στον στόχο. |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | Προσθέστε ακροατή συμβάντος αλλαγής κατάστασης matches του MediaQueryList. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Αποστέλλει ένα Event στο καθορισμένο [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (συγχρονισμένα) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένου του πλαισίου σύλληψης και του προαιρετικού φάσης φουσκώματος) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με την [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | Αφαιρέστε ακροατή συμβάντος αλλαγής κατάστασης matches του MediaQueryList. |

## Συμβάντα

| Όνομα | Περιγραφή |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | Συμβάν που εκτελείται στο MediaQueryList όταν η κατάσταση matches αλλάζει. |

### Δείτε επίσης

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
