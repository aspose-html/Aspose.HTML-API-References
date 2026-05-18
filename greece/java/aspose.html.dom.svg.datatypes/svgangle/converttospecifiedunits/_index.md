---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος SVGAngle. Διατηρεί την ίδια υποκείμενη αποθηκευμένη τιμή αλλά επαναφέρει το αποθηκευμένο αναγνωριστικό μονάδας στο δοθέν unitType. Τα χαρακτηριστικά του αντικειμένου unitType, valueInSpecifiedUnits και valueAsString μπορεί να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου."
type: docs

url: /el/java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Διατηρήστε την ίδια υποκείμενη αποθηκευμένη τιμή, αλλά επαναφέρετε το αποθηκευμένο αναγνωριστικό μονάδας στον δεδομένο unitType. Τα χαρακτηριστικά αντικειμένου unitType, valueInSpecifiedUnits και valueAsString μπορεί να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου.

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| unitType | UInt16 | Ο τύπος μονάδας προς αλλαγή (π.χ., SVG_ANGLETYPE_DEG). |

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Εγείρεται εάν unitType είναι SVG_ANGLETYPE_UNKNOWN ή δεν είναι έγκυρη σταθερά τύπου μονάδας (μία από τις άλλες σταθερές SVG_ANGLETYPE_* που ορίζονται σε αυτό το interface). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Εμφανίζεται όταν η γωνία αντιστοιχεί σε χαρακτηριστικό μόνο για ανάγνωση ή όταν το ίδιο το αντικείμενο είναι μόνο για ανάγνωση. |

### Δείτε επίσης

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
