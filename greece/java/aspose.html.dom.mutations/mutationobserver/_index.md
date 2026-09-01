---
title: "MutationObserver Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.mutations.MutationObserver κλάση. Ένα αντικείμενο μπορεί να χρησιμοποιηθεί για την παρακολούθηση μεταβολών στο δέντρο του"
type: docs

url: /el/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

Ένα αντικείμενο μπορεί να χρησιμοποιηθεί για την παρακολούθηση μεταβολών στο δέντρο του [`.`](../../com.aspose.html.dom/node/)

```java
public class MutationObserver : DOMObject
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Δημιουργεί ένα αντικείμενο MutationObserver και ορίζει το [`MutationCallback`](../mutationcallback/) του ως callback. Το callback καλείται με μια λίστα αντικειμένων MutationRecord ως πρώτο όρισμα και το κατασκευασμένο αντικείμενο MutationObserver ως δεύτερο όρισμα. Καλείται μετά από κόμβους που έχουν εγγραφεί με τη μέθοδο !:Observe(Node, IMutationObserverInit), όταν μεταβάλλονται. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | Σταματά τον παρατηρητή από το να παρακολουθεί οποιεσδήποτε μεταβολές. Μέχρι να χρησιμοποιηθεί ξανά η μέθοδος observe(), το callback του παρατηρητή δεν θα κληθεί. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Διευθύνει τον πράκτορα χρήστη να παρακολουθεί έναν συγκεκριμένο στόχο (κόμβο) και να αναφέρει οποιεσδήποτε μεταβολές βάσει των κριτηρίων που δίνονται από τις επιλογές (αντικείμενο). Το όρισμα options επιτρέπει τον ορισμό επιλογών παρακολούθησης μεταβολών μέσω μελών του αντικειμένου. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Διευθύνει τον πράκτορα χρήστη να παρακολουθεί έναν συγκεκριμένο στόχο (κόμβο) και να αναφέρει οποιεσδήποτε μεταβολές βάσει των κριτηρίων που δίνονται από τις επιλογές (αντικείμενο). Το όρισμα options επιτρέπει τον ορισμό επιλογών παρακολούθησης μεταβολών μέσω μελών του αντικειμένου. |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | Η μέθοδος επιστρέφει ένα αντίγραφο της ουράς εγγραφών και στη συνέχεια αδειάζει την ουρά εγγραφών. |

### Δείτε επίσης

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
