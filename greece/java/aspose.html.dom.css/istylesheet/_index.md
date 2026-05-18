---
title: "Διεπαφή IStyleSheet"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.css.IStyleSheet διεπαφή. Η διεπαφή StyleSheet είναι η αφηρημένη βασική διεπαφή για οποιοδήποτε τύπο φύλλου στυλ. Αντιπροσωπεύει ένα μοναδικό φύλλο στυλ που συνδέεται με ένα δομημένο έγγραφο. Σε HTML η διεπαφή StyleSheet αντιπροσωπεύει είτε ένα εξωτερικό φύλλο στυλ που περιλαμβάνεται μέσω του στοιχείου HTML LINK είτε ένα ενσωματωμένο στοιχείο STYLE. Σε XML αυτή η διεπαφή αντιπροσωπεύει ένα εξωτερικό φύλλο στυλ που περιλαμβάνεται μέσω μιας οδηγίας επεξεργασίας φύλλου στυλ. Τα φύλλα στυλ CSS θα υλοποιήσουν περαιτέρω τη πιο εξειδικευμένη διεπαφή CSSStyleSheet."
type: docs

url: /el/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

Η διεπαφή StyleSheet είναι η αφηρημένη βασική διεπαφή για οποιοδήποτε τύπο φύλλου στυλ. Αντιπροσωπεύει ένα μοναδικό φύλλο στυλ που συνδέεται με ένα δομημένο έγγραφο. Σε HTML, η διεπαφή StyleSheet αντιπροσωπεύει είτε ένα εξωτερικό φύλλο στυλ, που περιλαμβάνεται μέσω του στοιχείου HTML LINK, είτε ένα ενσωματωμένο στοιχείο STYLE. Σε XML, αυτή η διεπαφή αντιπροσωπεύει ένα εξωτερικό φύλλο στυλ, που περιλαμβάνεται μέσω μιας οδηγίας επεξεργασίας φύλλου στυλ. Τα φύλλα στυλ CSS θα υλοποιήσουν περαιτέρω τη πιο εξειδικευμένη διεπαφή [`CSSStyleSheet`](../icssstylesheet/).

Δείτε επίσης το [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface).

```java
public interface IStyleSheet
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) Η ιδιότητα href της διεπαφής `StyleSheet` επιστρέφει τη θέση του φύλλου στυλ. |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) Η ιδιότητα media της διεπαφής `StyleSheet` καθορίζει τα προοριζόμενα μέσα για τις πληροφορίες στυλ. Είναι ένα αντικείμενο μόνο για ανάγνωση, παρόμοιο με πίνακα [`MediaList`](../imedialist/) και μπορεί να αφαιρεθεί με τη deleteMedium() και να προστεθεί με την appendMedium(). |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) Ο κόμβος που συσχετίζει αυτό το φύλλο στυλ με το έγγραφο. Για HTML, μπορεί να είναι το αντίστοιχο στοιχείο LINK ή STYLE. Για XML, μπορεί να είναι η οδηγία σύνδεσης. Για φύλλα στυλ που περιλαμβάνονται από άλλα φύλλα στυλ, η τιμή αυτού του χαρακτηριστικού είναι null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) Για γλώσσες φύλλων στυλ που υποστηρίζουν την έννοια της ένταξης φύλλου στυλ, αυτό το χαρακτηριστικό αντιπροσωπεύει το φύλλο στυλ που περιλαμβάνει, εάν υπάρχει. Εάν το φύλλο στυλ είναι φύλλο στυλ ανώτερου επιπέδου, ή η γλώσσα του φύλλου στυλ δεν υποστηρίζει ένταξη, η τιμή αυτού του χαρακτηριστικού είναι null. |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) Η ιδιότητα title της διεπαφής `StyleSheet` επιστρέφει τον συμβουλευτικό τίτλο του τρέχοντος φύλλου στυλ. |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) Αυτό καθορίζει τη γλώσσα του φύλλου στυλ για αυτό το φύλλο στυλ. Η γλώσσα του φύλλου στυλ ορίζεται ως τύπος περιεχομένου (π.χ. "text/css"). |

## Παρατηρήσεις

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Αναφορά

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### Δείτε επίσης

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
