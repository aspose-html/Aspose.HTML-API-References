---
title: "Διεπαφή ICSSValueList"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.css.ICSSValueList διεπαφή. Η διεπαφή CSSValueList προέρχεται από τη διεπαφή CSSValue και παρέχει την αφαίρεση μιας διατεταγμένης συλλογής τιμών CSS."
type: docs

url: /el/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

Η διεπαφή CSSValueList προέρχεται από τη διεπαφή [`CSSValue`](../cssvalue/) και παρέχει την αφαίρεση μιας διατεταγμένης συλλογής τιμών CSS.

Ορισμένες ιδιότητες επιτρέπουν μια κενή λίστα στη σύνταξή τους. Σε αυτή την περίπτωση, αυτές οι ιδιότητες παίρνουν το αναγνωριστικό none. Έτσι, μια κενή λίστα σημαίνει ότι η ιδιότητα έχει την τιμή none.

Τα στοιχεία στη CSSValueList είναι προσβάσιμα μέσω ακέραιου δείκτη, ξεκινώντας από το 0.

```java
public interface ICSSValueList
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση ενός CSSValue με βάση τον διατεταγμένο δείκτη. Η σειρά σε αυτή τη συλλογή αντιπροσωπεύει τη σειρά των τιμών στην ιδιότητα στυλ CSS. Εάν ο δείκτης είναι μεγαλύτερος ή ίσος με τον αριθμό των τιμών στη λίστα, επιστρέφει null. |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) Η ιδιότητα length μόνο για ανάγνωση της διεπαφής CSSValueList αντιπροσωπεύει τον αριθμό των CSSValues στη λίστα. Το εύρος των έγκυρων τιμών των δεικτών είναι από 0 έως length-1 συμπεριλαμβανομένου. |

## Παρατηρήσεις

Αυτή η διεπαφή ήταν μέρος μιας προσπάθειας δημιουργίας ενός τυποποιημένου CSS Object Model. Η προσπάθεια αυτή έχει εγκαταλειφθεί και τα περισσότερα προγράμματα περιήγησης δεν την υλοποιούν.

Για να επιτύχετε τον σκοπό σας, μπορείτε να χρησιμοποιήσετε:

το μη τυποποιημένο [CSS Object Model](https://drafts.csswg.org/cssom/), ευρέως υποστηριζόμενο, ή το σύγχρονο [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects), λιγότερο υποστηριζόμενο και θεωρείται πειραματικό.

### Δείτε επίσης

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
