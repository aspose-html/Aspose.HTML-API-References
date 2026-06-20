---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος SVGLength. Διατηρεί την ίδια υποκείμενη αποθηκευμένη τιμή αλλά επαναφέρει το αποθηκευμένο αναγνωριστικό μονάδας στο δοσμένο unitType. Τα χαρακτηριστικά του αντικειμένου unitType, valueInSpecifiedUnits και valueAsString μπορεί να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου. Για παράδειγμα, εάν η αρχική τιμή ήταν 0.5cm και η μέθοδος κληθεί για μετατροπή σε χιλιοστά, τότε το unitType θα αλλάξει σε SVG_LENGTHTYPE_MM, το valueInSpecifiedUnits θα αλλάξει στην αριθμητική τιμή 5 και το valueAsString θα αλλάξει σε 5mm."
type: docs

url: /el/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Διατηρήστε την ίδια υποκείμενη αποθηκευμένη τιμή, αλλά επαναφέρετε το αποθηκευμένο αναγνωριστικό μονάδας στο δοσμένο unitType. Τα χαρακτηριστικά αντικειμένου unitType, valueInSpecifiedUnits και valueAsString ενδέχεται να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου. Για παράδειγμα, εάν η αρχική τιμή ήταν "0.5cm" και η μέθοδος κληθεί για μετατροπή σε χιλιοστά, τότε το unitType θα αλλάξει σε SVG_LENGTHTYPE_MM, το valueInSpecifiedUnits θα αλλάξει στην αριθμητική τιμή 5 και το valueAsString θα αλλάξει σε "5mm".

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| unitType | UInt16 | Ο τύπος μονάδας προς αλλαγή (π.χ., SVG_LENGTHTYPE_MM). |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Εγείρεται εάν το unitType είναι SVG_LENGTHTYPE_UNKNOWN ή δεν είναι έγκυρη σταθερά τύπου μονάδας (μία από τις άλλες σταθερές SVG_LENGTHTYPE_* που ορίζονται σε αυτό το interface). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Αναφέρεται όταν το μήκος αντιστοιχεί σε χαρακτηριστικό μόνο για ανάγνωση ή όταν το ίδιο το αντικείμενο είναι μόνο για ανάγνωση. |

### Δείτε επίσης

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
