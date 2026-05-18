---
title: "IDocumentCSS Διεπαφή"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.dom.css.IDocumentCSS. Αυτή η διεπαφή αντιπροσωπεύει ένα έγγραφο με προβολή CSS."
type: docs

url: /el/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

Αυτή η διεπαφή αντιπροσωπεύει ένα έγγραφο με προβολή CSS.

Η μέθοδος getOverrideStyle παρέχει έναν μηχανισμό μέσω του οποίου ένας δημιουργός DOM μπορεί να επιφέρει άμεση αλλαγή στο στυλ ενός στοιχείου χωρίς να τροποποιήσει τα ρητά συνδεδεμένα φύλλα στυλ ενός εγγράφου ή το ενσωματωμένο στυλ των στοιχείων στα φύλλα στυλ. Αυτό το φύλλο στυλ έρχεται μετά το φύλλο στυλ του δημιουργού στον αλγόριθμο κατάρρευσης και ονομάζεται φύλλο στυλ παράκαμψης (override style sheet). Το φύλλο στυλ παράκαμψης έχει προτεραιότητα έναντι των φύλλων στυλ του δημιουργού. Μια δήλωση "!important" εξακολουθεί να έχει προτεραιότητα έναντι μιας κανονικής δήλωσης. Τα φύλλα στυλ παράκαμψης, δημιουργού και χρήστη μπορούν όλα να περιέχουν δηλώσεις "!important". Οι κανόνες "!important" του χρήστη έχουν προτεραιότητα έναντι τόσο των κανόνων "!important" του παράκαμψης όσο και των κανόνων "!important" του δημιουργού, και οι κανόνες "!important" του παράκαμψης έχουν προτεραιότητα έναντι των κανόνων "!important" του δημιουργού.

Η προσδοκία είναι ότι ένα στιγμιότυπο της διεπαφής DocumentCSS μπορεί να ληφθεί χρησιμοποιώντας μεθόδους μετατροπής ειδικές για το binding σε ένα στιγμιότυπο της διεπαφής Document.

Δείτε επίσης την [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113).

```java
public interface IDocumentCSS : IDocumentStyle
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση της δήλωσης στυλ παράκαμψης για ένα συγκεκριμένο στοιχείο και ένα συγκεκριμένο ψευδο-στοιχείο. |

### Δείτε επίσης

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
