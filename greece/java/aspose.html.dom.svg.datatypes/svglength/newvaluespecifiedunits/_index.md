---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "SVGLength μέθοδος. Επαναφέρει την τιμή ως αριθμό με συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου."
type: docs

url: /el/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Επαναφέρετε την τιμή ως αριθμό με συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου.

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| unitType | UInt16 | Ο τύπος μονάδας για την τιμή. |
| valueInSpecifiedUnits | Single | Η νέα τιμή.. |

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Ενδείκνυται εάν το unitType είναι SVG_LENGTHTYPE_UNKNOWN ή δεν είναι έγκυρη σταθερά τύπου μονάδας (μία από τις άλλες σταθερές SVG_LENGTHTYPE_* που ορίζονται σε αυτό το interface). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Εγείρεται όταν το μήκος αντιστοιχεί σε μια ιδιότητα μόνο για ανάγνωση ή όταν το ίδιο το αντικείμενο είναι μόνο για ανάγνωση. |

### Δείτε επίσης

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
