---
title: "IStyleSheet.Disabled"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Ιδιότητα IStyleSheet. Η ιδιότητα disabled του διεπαφής StyleSheet καθορίζει εάν το φύλλο στυλ αποτρέπεται από την εφαρμογή στο έγγραφο."
type: docs

url: /el/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

Η ιδιότητα disabled του διεπαφής [`StyleSheet`](../) καθορίζει εάν το φύλλο στυλ αποτρέπεται από την εφαρμογή στο έγγραφο.

Ένα φύλλο στυλ μπορεί να απενεργοποιηθεί ορίζοντας χειροκίνητα αυτή την ιδιότητα σε true ή εάν είναι ένα ανενεργό εναλλακτικό φύλλο στυλ. Σημειώστε ότι disabled == false δεν εγγυάται ότι το φύλλο στυλ θα εφαρμοστεί (μπορεί, για παράδειγμα, να έχει αφαιρεθεί από το έγγραφο).

Η τροποποίηση αυτού του χαρακτηριστικού μπορεί να προκαλέσει νέα ανάλυση στυλ για το έγγραφο. Ένα φύλλο στυλ εφαρμόζεται μόνο εάν υπάρχει τόσο μια κατάλληλη ορισμός μέσου όσο και το χαρακτηριστικό disabled είναι false. Έτσι, εάν το μέσο δεν εφαρμόζεται στον τρέχοντα χρήστη-πράκτορα, το χαρακτηριστικό disabled αγνοείται.

```java
public bool Disabled { get; set; }
```

### Τιμή Επιστροφής

Το χαρακτηριστικό disabled, κατά την ανάγνωση, πρέπει να επιστρέφει true εάν η σημαία disabled είναι ορισμένη, ή false διαφορετικά. Κατά τη ρύθμιση, το χαρακτηριστικό disabled πρέπει να ορίζει τη σημαία disabled εάν η νέα τιμή είναι true, ή να αφαιρεί τη σημαία disabled διαφορετικά.

### Property Value

Το χαρακτηριστικό disabled, κατά την ανάγνωση, πρέπει να επιστρέφει true εάν η σημαία disabled είναι ορισμένη, ή false διαφορετικά. Κατά τη ρύθμιση, το χαρακτηριστικό disabled πρέπει να ορίζει τη σημαία disabled εάν η νέα τιμή είναι true, ή να αφαιρεί τη σημαία disabled διαφορετικά.

## Παρατηρήσεις

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Αναφορά

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### Δείτε επίσης

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
