---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος SVGAngle. Επαναφέρει την τιμή ως αριθμό με συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές όλων των χαρακτηριστικών του αντικειμένου."
type: docs

url: /el/java/com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Επαναφέρετε την τιμή ως αριθμό με συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου.

```java
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newUnitType | UInt16 | Ο τύπος μονάδας για την τιμή (π.χ., SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Η τιμή της γωνίας. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Εμφανίζεται εάν unitType είναι SVG_ANGLETYPE_UNKNOWN ή δεν είναι έγκυρη σταθερά τύπου μονάδας (μία από τις άλλες σταθερές SVG_ANGLETYPE_* που ορίζονται σε αυτό το interface). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Αναφέρεται όταν η γωνία αντιστοιχεί σε χαρακτηριστικό μόνο για ανάγνωση ή όταν το ίδιο το αντικείμενο είναι μόνο για ανάγνωση. |

### Δείτε επίσης

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
