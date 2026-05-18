---
title: "Διεπαφή IWindow"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.window.IWindow. Το αντικείμενο window αντιπροσωπεύει ένα παράθυρο που περιέχει ένα έγγραφο DOM"
type: docs

url: /el/java/com.aspose.html.window/iwindow/
---
## IWindow interface

Το αντικείμενο window αντιπροσωπεύει ένα παράθυρο που περιέχει ένα έγγραφο DOM.

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) Το χαρακτηριστικό document πρέπει να επιστρέφει το πιο πρόσφατο αντικείμενο Document του αντικειμένου Window. |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) Το αντικείμενο frameElement ενός Document. |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) Επιστρέφει ένα αντικείμενο Storage που σας επιτρέπει να αποθηκεύετε ζεύγη κλειδί/τιμή στον user agent. |
| [getLocation](../../com.aspose.html.window/iwindow/location/) Το χαρακτηριστικό location της διεπαφής Window πρέπει να επιστρέφει το αντικείμενο Location για το Document του αντίστοιχου αντικειμένου Window. |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) Το χαρακτηριστικό opener IDL στο αντικείμενο Window, κατά την ανάγνωση, πρέπει να επιστρέφει το αντικείμενο WindowProxy του περιβάλλοντος περιήγησης από το οποίο δημιουργήθηκε το τρέχον περιβάλλον περιήγησης (το περιβάλλον περιήγησης opener), εάν υπάρχει, εάν είναι ακόμη διαθέσιμο, και εάν το τρέχον περιβάλλον περιήγησης δεν έχει αποχωρήσει από το opener του· διαφορετικά, πρέπει να επιστρέφει null. Κατά τη ρύθμιση, εάν η νέα τιμή είναι null τότε το τρέχον περιβάλλον περιήγησης πρέπει να αποχωρήσει από το opener του· εάν η νέα τιμή είναι κάτι άλλο, τότε ο user agent πρέπει να καλέσει τη εσωτερική μέθοδο [[DefineOwnProperty]] του αντικειμένου Window, περνώντας το όνομα ιδιότητας "opener" ως κλειδί ιδιότητας, και τον Περιγραφέα Ιδιότητας { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } ως περιγραφέα ιδιότητας, όπου value είναι η νέα τιμή. |
| [getParent](../../com.aspose.html.window/iwindow/parent/) Το χαρακτηριστικό parent IDL στο αντικείμενο Window ενός Document σε ένα περιβάλλον περιήγησης b πρέπει να επιστρέφει το αντικείμενο WindowProxy του γονικού περιβάλλοντος περιήγησης, εάν υπάρχει (π.χ. εάν το b είναι παιδικό περιβάλλον περιήγησης), ή το αντικείμενο WindowProxy του ίδιου περιβάλλοντος περιήγησης b, διαφορετικά (π.χ. εάν είναι ένα ανώτερο επίπεδο περιβάλλοντος περιήγησης ή ένα αποσυνδεδεμένο ένθετο περιβάλλον περιήγησης). |
| [getSelf](../../com.aspose.html.window/iwindow/self/) Επιστρέφει το αντικείμενο WindowProxy του περιβάλλοντος περιήγησης του αντικειμένου Window. |
| [getTop](../../com.aspose.html.window/iwindow/top/) Το χαρακτηριστικό top IDL στο αντικείμενο Window ενός Document σε ένα περιβάλλον περιήγησης b πρέπει να επιστρέφει το αντικείμενο WindowProxy του ανώτερου επιπέδου περιβάλλοντος περιήγησης (που θα ήταν το δικό του αντικείμενο WindowProxy εάν ήταν ανώτερο επίπεδο περιβάλλοντος περιήγησης), εάν υπάρχει, ή το δικό του αντικείμενο WindowProxy διαφορετικά (π.χ. εάν ήταν αποσυνδεδεμένο ένθετο περιβάλλον περιήγησης). |
| [getWindow](../../com.aspose.html.window/iwindow/window/) Επιστρέφει το αντικείμενο WindowProxy του περιβάλλοντος περιήγησης του αντικειμένου Window. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | Εμφανίζει μια μοντέλα ειδοποίηση με το δοσμένο μήνυμα και περιμένει ο χρήστης να την κλείσει. |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | Δέχεται τα δεδομένα εισόδου, με τη μορφή Unicode String που περιέχει δυαδικά δεδομένα κωδικοποιημένα σε base64, τα αποκωδικοποιεί και επιστρέφει ένα String που αποτελείται από χαρακτήρες στο εύρος U+0000 έως U+00FF, ο καθένας αντιπροσωπεύει ένα δυαδικό byte με τιμές 0x00 έως 0xFF αντίστοιχα, που αντιστοιχούν σε αυτά τα δυαδικά δεδομένα. |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | Δέχεται τα δεδομένα εισόδου, με τη μορφή Unicode String που περιέχει μόνο χαρακτήρες στο εύρος U+0000 έως U+00FF, ο καθένας αντιπροσωπεύει ένα δυαδικό byte με τιμές 0x00 έως 0xFF αντίστοιχα, και τα μετατρέπει στην αναπαράστασή τους σε base64, την οποία επιστρέφει. |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | Εμφανίζει ένα μοντέλο παράθυρο προτροπής OK/Cancel με το δοσμένο μήνυμα, περιμένει ο χρήστης να το κλείσει και επιστρέφει true εάν ο χρήστης κάνει κλικ στο OK και false εάν κάνει κλικ στο Cancel. |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | Επιστρέφει ένα νέο αντικείμενο MediaQueryList που μπορεί στη συνέχεια να χρησιμοποιηθεί για να προσδιορίσει εάν το έγγραφο ταιριάζει με τη συμβολοσειρά ερωτήματος μέσου (media query), καθώς και για να παρακολουθεί το έγγραφο ώστε να εντοπίζει πότε ταιριάζει (ή σταματά να ταιριάζει) με αυτό το ερώτημα μέσου. Δείτε την προδιαγραφή του CSSOM View Module: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | Εμφανίζει ένα μοντέλο παράθυρο προτροπής κειμενικού πεδίου με το δοσμένο μήνυμα, περιμένει ο χρήστης να το κλείσει και επιστρέφει την τιμή που εισήγαγε ο χρήστης. Εάν ο χρήστης ακυρώσει την προτροπή, τότε επιστρέφει null. Εάν υπάρχει το δεύτερο όρισμα, τότε η δοσμένη τιμή χρησιμοποιείται ως προεπιλογή. |

### Δείτε επίσης

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
