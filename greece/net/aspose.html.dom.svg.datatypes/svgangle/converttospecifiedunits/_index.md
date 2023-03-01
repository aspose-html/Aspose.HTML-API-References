---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: Aspose.HTML για Αναφορά API .NET
description: SVGAngle μέθοδος. Διατηρήστε την ίδια υποκείμενη αποθηκευμένη τιμή αλλά επαναφέρετε το αναγνωριστικό αποθηκευμένης μονάδας στο δεδομένο unitType. Χαρακτηριστικά αντικειμένου unitType valueInSpecifiedUnits και valueAsString ενδέχεται να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου.
type: docs
weight: 50
url: /el/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Διατηρήστε την ίδια υποκείμενη αποθηκευμένη τιμή, αλλά επαναφέρετε το αναγνωριστικό αποθηκευμένης μονάδας στο δεδομένο unitType. Χαρακτηριστικά αντικειμένου unitType, valueInSpecifiedUnits και valueAsString ενδέχεται να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| unitType | UInt16 | Ο τύπος μονάδας στον οποίο θέλετε να αλλάξετε (π.χ. SVG_ANGLETYPE_DEG). |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Κωδ[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Αυξάνεται εάν το unitType είναι SVG_ANGLETYPE_UNKNOWN ή δεν είναι έγκυρη σταθερά τύπου μονάδας (μία από τις άλλες σταθερές SVG_ANGLETYPE_* που ορίζονται σε αυτήν τη διεπαφή). |
| [DOMException](../../../aspose.html.dom/domexception/) | Κωδ[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Ανυψώνεται όταν η γωνία αντιστοιχεί σε ένα χαρακτηριστικό μόνο για ανάγνωση ή όταν το ίδιο το αντικείμενο είναι μόνο για ανάγνωση. |

### Δείτε επίσης

* class [SVGAngle](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* συνέλευση [Aspose.HTML](../../../)


