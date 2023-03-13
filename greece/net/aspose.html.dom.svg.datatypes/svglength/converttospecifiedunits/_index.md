---
title: SVGLength.ConvertToSpecifiedUnits
second_title: Aspose.HTML για Αναφορά API .NET
description: SVGLength μέθοδος. Διατηρήστε την ίδια υποκείμενη αποθηκευμένη τιμή αλλά επαναφέρετε το αναγνωριστικό αποθηκευμένης μονάδας στο δεδομένο unitType. Χαρακτηριστικά αντικειμένου unitType valueInSpecifiedUnits και valueAsString ενδέχεται να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου. Για παράδειγμα εάν η αρχική τιμή ήταν 05cm και η μέθοδος χρησιμοποιήθηκε για μετατροπή σε χιλιοστά τότε το unitType θα άλλαζε σε SVG_LENGTHTYPE_MM το valueInSpecifiedUnits θα άλλαζε στην αριθμητική τιμή 5 και το valueAsString θα άλλαζε σε 5mm.
type: docs
weight: 50
url: /el/net/aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Διατηρήστε την ίδια υποκείμενη αποθηκευμένη τιμή, αλλά επαναφέρετε το αναγνωριστικό αποθηκευμένης μονάδας στο δεδομένο unitType. Χαρακτηριστικά αντικειμένου unitType, valueInSpecifiedUnits και valueAsString ενδέχεται να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου. Για παράδειγμα, εάν η αρχική τιμή ήταν "0,5cm" και η μέθοδος χρησιμοποιήθηκε για μετατροπή σε χιλιοστά, τότε το unitType θα άλλαζε σε SVG_LENGTHTYPE_MM, το valueInSpecifiedUnits θα άλλαζε στην αριθμητική τιμή 5 και το valueAsString θα άλλαζε σε "5mm".

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| unitType | UInt16 | Ο τύπος μονάδας στον οποίο θέλετε να αλλάξετε (π.χ. SVG_LENGTHTYPE_MM). |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Κωδ[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Αυξάνεται εάν το unitType είναι SVG_LENGTHTYPE_UNKNOWN ή δεν είναι έγκυρη σταθερά τύπου μονάδας (μία από τις άλλες σταθερές SVG_LENGTHTYPE_* που ορίζονται σε αυτήν τη διεπαφή). |
| [DOMException](../../../aspose.html.dom/domexception/) | Κωδ[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Αυξάνεται όταν το μήκος αντιστοιχεί σε ένα χαρακτηριστικό μόνο για ανάγνωση ή όταν το ίδιο το αντικείμενο είναι μόνο για ανάγνωση. |

### Δείτε επίσης

* class [SVGLength](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* συνέλευση [Aspose.HTML](../../../)


